# SugarScapeModels Using PyCX
This is repositiry contains implementations of Rob Axtell's and Joshua Epstein's SugarScape model
## Table of contents

- Requirements and Installations
- Models

## Requirements and Installations

To run the code make sure have Python installed, and follow the installation steps as mentioned in the [PyCx](https://github.com/hsayama/PyCX)


## Models
```bash
.
├── pycxsimulator.py                         # This is file that does all the magic, cloned from [PyCx](https://github.com/hsayama/PyCX)
├── abm-sugarscape.py                        # Baseline model as mentioned in the Chapter 1 of the book "Growing Artificial Societies"
├── abm-sugarscape-with-vinegar.py           # A variation of baseline model with agents pollute the environment with Vinegar, environment has healing capacity or depolluting capabilities, and Agents prioritixze the location with less Vinegar 40% times
├── abm-sugarscape-seasons.py                # Sugar availabity flips every 50 iterations
├── abm-sugarscape-less-greedy-agents.py     # Some agents aren't greedy for sugar, rather move to random location
├── abm-sugarscape-grided-initial.py         # Try running this, You'll migration emerge!
└── README.md
```