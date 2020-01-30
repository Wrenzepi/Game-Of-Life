# Game-Of-Life

Python program for simulating Conway's Game of Life made by David Kohler and designed for Python 3.6. Generates gif for user based on passed in parameters. User can choose to start the simulation using a random grid of size specified by the user, or can start the simulation using an RLE (Run Length Encoded) formatted file (with .rle file extension) with a specified minimum grid size. Once the grid has been generated or parsed from file, the program asks the user for the number of generations to run and the frame rate to use to generate the gif. Program will then generate the simulation and save a gif in a "GoL-gifs" folder. The program will then ask the user if they want to save an RLE file translating the grid it has just simulated, saving a .rle file in a "saved-RLEs" folder. Designed for use from the terminal.

## Installation

1. Copy the repository
2. Make sure you have Python version 3.6 or later
3. Make sure you have up to date versions of the following libraries: `matplotlib`, `numpy`, `seaborn`, `celluloid`

## Usage

From terminal, two options for usage.
For unspecified RLE file using a random grid: `python GameOfLife.py`
To use a specified RLE file: `python GameOfLife.py <RLEfile.rle>`
