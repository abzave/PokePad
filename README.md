# Pokedex (Pokemon catalog) in Python

This project is a Pokemon catalog using the Pokemon API developed in Python. The goal of this project is to learn about `Tkinter` (Python's UI library), API consumption, binary files and XML.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [How to Run](#how-to-run)
5. [Usage](#usage)

## Project Overview

The Pokedex requests up to 1000 pokemons from the `Pokemon API` and lets the user to search for pokemons, save favourite pokemons, see the pokemon's characteristics, and export pokemons to binary data or XML. The project uses `Tkinter` to create a GUI that the user can easily navigate. 

## Features

- **Look up to 1000 Pokemons**: Allows the user to select how many Pokemons to search for, with a limit of 1000.
- **Paginated List**: Displays the ID, name and optionally weight of 3 pokemons at a time with the option to go to the next and previous page.
- **Binary Export**: Allows the user to export the current application state to a binary file, to save API requests and favourite pokemons.
- **XML Export**: Sends the information of a single pokemon via email.
- **Weight Range Filter**: Reduces the list of pokemons to only a designated range of weights.
- **Name Aproximation Filter**: Looks for pokemons whose names are phonetically similar to the given input.
- **Pokemon profiles**: Allows the user to see the name, weight, height and an image of a single pokemon.
- **Favourite Pokemons**: Saves a pokemon into a favourite list for quick access.
- **Graphic User Interface**: Displays visually all the information and navigation of the application.
- **Uses the Pokemon API**: Gets all the pokemons' information from an external database.

## Requirements

- **Run everywhere with Python**: The project can run on any platform as long as it has a Python interpreter installed.
- **Use the Pokemon API**: Retrieve the pokemons' information from the `Pokemon REST API`.
- **Send Emails**: Use the `SMTP` protocol to send emails.
- **Graphic User Interface**: Use `Tkinter` to create a visual interface.

## How to Run

### Step 1: Clone the repository

``` bash
git clone https://github.com/abzave/PokePad.git
cd PokePad
```

### Step 2: Run the program

Open the file `principal.pyw`

## Usage

1. The first time the application is opened the user will be prompted to enter the amount of pokemons to request. This number must not be greater the 1000.
2. Look for the desired pokemon in the list by navigating with the `next` and `previous` buttons, or by applying a filter.
    -  Filter by range: Enter the minimum and maximum weight that the pokemon must have to be considered in the search.
    -  Filter by aproximation: Enter the name or aproximate name of the pokemon you are looking for, it will search for phonetically similar names.
3. Click on the name of the pokemon you want to see in order to open the profile containing the name, weight, height and image.
4. To save a favourite pokemon click on the `Save to binary` button. The pokemon will be added to the section called `My pokemons` where the user can see all the saved pokemons.
5. To get the information of a pokemon into the user's email click the `Save to XML` button, then the user will be prompted to login into their email.
