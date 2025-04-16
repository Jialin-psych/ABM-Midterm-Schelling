# Updated Schelling Segregation Model

This repository contains the Updated Schelling Segregation Model. The model simulates the behavior of agents in a two-group system, where agents they can decide whether to move and/or switch groups based on the composition of their neighbors.

## Overview

The model simulates spatial segregation where agents can be of two types (denoted by `0` and `1`). Each agent interacts with its neighbors, and based on the number of similar neighbors, they may move to another location. Additionally, if an agent has been surrounded by too many opposite-type agents for a certain number of time steps, it may switch groups with a certain probability.

The model allows users to experiment with various parameters like:
- **Grid size** (width, height)
- **Population density**
- **Desired similarity between neighboring agents**
- **Transition threshold and probability** for agents to switch groups.


## Installation
To install the dependencies use pip and the requirements.txt in this directory. e.g.
$ pip install -r requirements.txt

To run the model interactively:

$ solara run app.py


## Files
+ agents.py: Contains the agent class, currently incomplete
+ model.py: Contains the model class
+ app.py: Defines classes for visualizing the model in the browser via Solara, and instantiates a visualization server.
