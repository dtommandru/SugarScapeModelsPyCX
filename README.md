# SugarScape Models Using PyCX
This repository contains implementation of Rob Axtell's and Joshua Epstein's original SugarScape model from [Growing Artificial Societies - Social Science from the Bottom Up](https://mitpress.mit.edu/9780262550253/growing-artificial-societies/) and few variations using PyCX

## Table of contents

- Requirements and Installations
- Models and Folder Structure
- Credits

## Requirements and Installations

To run the code make sure have Python installed, and follow the installation steps as mentioned in the [PyCX](https://github.com/hsayama/PyCX)


## Models and Folder Structure
```bash
.
├── pycxsimulator.py                         # This is file that does all the magic, cloned from PyCx - https://github.com/hsayama/PyCX 
├── abm-sugarscape.py                        # Baseline model as mentioned in the Chapter 1 of the book "Growing Artificial Societies Social Science from the Bottom Up"
├── abm-sugarscape-with-vinegar.py           # A variation of baseline model with agents pollute the environment with Vinegar, environment has healing capacity or depolluting capabilities, and Agents prioritixze the location with less Vinegar 40% times
├── abm-sugarscape-seasons.py                # Sugar availabity flips every 50 iterations
├── abm-sugarscape-less-greedy-agents.py     # Some agents aren't greedy for sugar, rather move to random location
├── abm-sugarscape-grided-initial.py         # Try running this, You'll see migration emerge!
└── README.md
```

## Credits

Thanks for the inputs and guidance from [Dr. Hiroki Sayama](https://github.com/hsayama) and [Annaji Rao Challa](https://github.com/Annajiraochalla) for helping me navigate through the project.

The mirror image code is taken from [Geeks for Geeks](https://www.geeksforgeeks.org/find-mirror-image-point-2-d-plane/)
