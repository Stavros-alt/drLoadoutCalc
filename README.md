# Deltarune Ultimate Loadout Optimizer

This project provides a web-based tool that calculates the optimal equipment loadout for characters in the game Deltarune.

## Features

*   Automated "Best-in-Slot" Calculation
*   Party Selection
*   Item Quantity Management
*   Comprehensive Equipment Database
*   Self-Contained Application

## How to Use

1.  Open the `index.html` file in a web browser.
2.  Select the characters currently in your party.
3.  Check the boxes for all the weapons and armor you have collected.
4.  For any items you have more than one of, adjust the quantity in the number input that appears.
5.  Click the "Calculate Optimal Loadouts" button.
6.  View the results, which show the best equipment for each selected character.

## Live Demo

Try the calculator without downloading: [Live Demo](https://stavros-alt.github.io/drLoadoutCalc/)

### Bug Fixes
* Fixed uncaught ReferenceError: `characterPriorities is not defined` by correcting variable references to `characterPriorityWeights` in loadApplicationState()