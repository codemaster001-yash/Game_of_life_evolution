# Game of Life: Evolution

"Game of Life: Evolution" is an interactive and visually enhanced implementation of Conway's Game of Life, introducing new rules for genetics, aging, and mutations. Observe fascinating patterns of birth, survival, and death as colorful cellular species evolve and interact on the grid.

## Features

* **Interactive Grid:** Click or drag to manually create and place cells with your chosen color.
* **Genetic Inheritance:** New cells typically blend colors from their parent cells, leading to a rich diversity of hues.
* **Mutations:** A small chance (1%) for new cells to mutate into a completely new, random color, introducing novel species.
* **Aging Mechanic:** Cells have a maximum lifespan of 100 generations, preventing infinite stable patterns and promoting dynamic change.
* **Standard Game of Life Rules:**
    * **Birth:** A dead cell with exactly three live neighbors becomes a live cell.
    * **Survival:** A live cell with two or three live neighbors remains alive.
    * **Death:** A live cell with fewer than two live neighbors (underpopulation) or more than three live neighbors (overpopulation) dies.
* **Real-time Statistics:** Track generations, live cell count, unique color species, and new mutated species.
* **Pause & Resume:** Pause the simulation to manually add or remove cells, or to analyze the current state.
* **Modal Pause Summary:** When paused, a modal displays key statistics from the last simulation run, including population change, new species created, species lost, and unique surviving species.
* **Adjustable Speed:** Control the simulation speed to observe changes at your preferred pace.
* **Randomization:** Quickly populate the grid with a random arrangement of cells.
* **Reset Functionality:** Clear the grid and reset the simulation to its initial state.
* **Theming:** Toggle between a dark and light theme for a personalized viewing experience.
* **Responsive Design:** The canvas and controls adapt to different screen sizes.

## How to Use

1.  **Start the Simulation:**
    * Upon opening, you'll see an "Evolution: Game of Life" overlay with a brief description and the game rules.
    * Click the "Start Simulation" button to begin.

2.  **Interacting with the Grid (when paused):**
    * **Select a Color:** At the bottom, a color palette is available. Click on a color swatch to select your active drawing color.
    * **Add Cells:** Click on any empty space on the grid to place a live cell of the selected color.
    * **Draw Multiple Cells:** Click and drag your mouse across the grid to quickly draw multiple cells.
    * **Remove Cells:** Clicking on an existing live cell will toggle it off (make it dead).

3.  **Controlling the Simulation:**
    * **Start/Pause:** The large central button at the bottom toggles the simulation.
        * When paused, it says "Resume" and shows a play icon.
        * When running, it says "Pause" and shows a pause icon.
        * **Note:** You can only add/remove cells when the simulation is paused.
    * **Speed Slider:** Use the "Speed" slider to adjust how fast the generations evolve. Dragging it to the right makes the simulation faster.
    * **Randomize Button (🎲):** Click this button to clear the current grid and fill it with a random assortment of live cells. This will also pause the simulation.
    * **Reset Button (🔄):** Click this button to clear the entire grid, reset the generation count, and pause the simulation.

4.  **Viewing Statistics:**
    * **Top Right Card:** A "Stats Card" continuously displays:
        * **Generation:** The current simulation generation.
        * **Live Cells:** The total number of living cells on the grid.
        * **Unique Color Species:** The number of distinct colors (species) currently alive.
        * **New Species:** The number of unique colors that have arisen due to mutations.
    * **Pause Modal:** When you pause the simulation, a "Simulation Paused" modal appears, providing a summary of changes since the last unpause:
        * **Population Change:** Net increase or decrease in live cells.
        * **New Species Created:** Number of new mutated colors observed.
        * **Species Lost:** Number of colors that were present but are no longer active.
        * **Unique Surviving Species:** The number of unique colors still present on the grid.
        * Click anywhere on the modal overlay to close it.

5.  **Accessing Rules and Theme:**
    * **Show Rules Button (❓):** Click this button to bring back the initial "Evolution: Game of Life" overlay, which explains the rules of the game.
    * **Toggle Theme Button (☀️/🌙):** Switch between a dark theme (default) and a light theme for the interface. Your theme preference will be saved.

## Core Rules of Evolution

* **Birth:** An empty cell with exactly three live neighbors becomes a live cell. The new cell's color is determined by blending or inheriting from its parents, with a small chance of mutation.
* **Genetics:** When a new cell is born, it typically blends the colors of its parent cells. If it has only one parent color, it inherits that color.
* **Survival:** A living cell with two or three live neighbors survives to the next generation.
* **Mutations:** New cells have a 1% chance to mutate into a completely new, random color, introducing new "species" into the simulation.
* **Aging:** A living cell can survive for a maximum of 100 generations before dying of old age.
* **Death:** A cell dies if it has fewer than two live neighbors (loneliness), more than three live neighbors (overcrowding), or reaches its maximum age.

Enjoy observing the fascinating emergent behavior in "Game of Life: Evolution"!
