# Sorting Algorithm Visualizer 🎉🐍

This project is a visualization tool for sorting algorithms built with Python and Pygame. It allows users to see how sorting algorithms like Bubble Sort and Insertion Sort operate on a list of numbers in real time.

## Features ✨

- Visualizes **Bubble Sort** and **Insertion Sort** algorithms
- Interactive controls to **reset**, **start**, and **switch sorting modes**
- Supports **ascending** and **descending** order sorting
- Clean and intuitive graphical interface with color-coded bars

## Requirements 🛠️

- Python 3.x
- Pygame library

Install Pygame using pip if you haven't already:

bash
pip install pygame

## How to Run ▶️

1. Save the code in a Python file, e.g., `sorting_visualizer.py`.
   
3. Run the script:
4. 
   bash
   python sorting_visualizer.py
   
5. A window will open displaying the sorting visualization interface.

## Controls 🎮

| Key      | Action                                 |
|----------|----------------------------------------|
| R        | Reset the list with new random values 🔄 |
| SPACE    | Start sorting ▶️                      |
| A        | Set sorting to ascending order ⬆️     |
| D        | Set sorting to descending order ⬇️    |
| I        | Switch to Insertion Sort 🧩            |
| B        | Switch to Bubble Sort 🧼               |
| Close    | Exit the program ❌                    |

## How It Works 🧠

- **List Generation:** Random list of integers displayed as vertical bars.
- **Sorting Algorithms:** Choose between Bubble Sort and Insertion Sort. The sorting process is animated, showing comparisons and swaps in real time.
- **Color Coding:**
  - 🟢 *Green*: Current element being compared or swapped
  - 🔴 *Red*: Target element for comparison or swap
  - ⚪ *Gray shades*: Default bar colors for visual distinction

## Customization 🎨

- Change the number of elements (`n`), minimum (`min_val`), and maximum (`max_val`) values in the `main()` function to adjust the size and range of the list.
- Window size and padding can be modified in the `DrawInformation` class initialization.

## File Structure 📂

- **DrawInformation**: Handles drawing and window management.
- **draw() / draw_list()**: Render the current state and controls.
- **generate_starting_list()**: Creates a new randomized list.
- **bubble_sort() / insertion_sort()**: Sorting algorithm implementations with visualization hooks.
- **main()**: Program entry point and event loop.

## Requirements 🛠️
This project was developed using:

PyCharm IDE: For writing, running, and debugging Python code efficiently.

Python 3: The programming language used for all code and logic.

Pygame: The library used for visualization and graphics.

## Acknowledgments 🙏

- Inspired by classic algorithm visualizations for educational use.
