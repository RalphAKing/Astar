# A* Path Finding Algorithm

This project implements the A* (A-star) pathfinding algorithm using Pygame. The algorithm finds the shortest path from a start point to an end point, avoiding obstacles (barriers). The grid is visualized in a Pygame window where users can interact with it to set the start and end points, place barriers, and trigger the algorithm.

## Controls

- **Left Mouse Click**: Set the start point, end point, or place barriers.
- **Right Mouse Click**: Reset a spot to its default state (remove start, end, or barrier).
- **Spacebar**: Start the A* algorithm to find the shortest path.
- **D Key**: Toggle diagonal movement on/off.
- **C Key**: Clear the grid, resetting the start, end, and barriers.
- **M Key**: Generate a random maze on the grid.

## Features

- A* algorithm visualized with different colors representing various states:
  - **Red**: Closed nodes
  - **Green**: Open nodes
  - **Purple**: The final path
  - **Orange**: Start point
  - **Turquoise**: End point
  - **Black**: Barriers
  - **White**: Empty spaces

- Diagonal movement option, toggleable with the `D` key.
- Customizable grid size (default is 50x50).

## Requirements

- Python 3.x
- Pygame (can be installed using `pip install pygame`)

## Installation

1. Clone the repository or download the files.
2. Install Pygame:
   ```bash
   pip install pygame


## License

This project is open-source and available for modification and use under the MIT license.

### MIT License

```
MIT License

Copyright (c) 2024-2025 Ralph King

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
