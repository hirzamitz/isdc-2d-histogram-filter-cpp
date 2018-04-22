# isdc-2d-histogram-filter-cpp
ISDC Project - Implementing a 2D Histogram Filter using C++

In this project, I've translated the 2D histogram filter which was imnplemented in Python to C++.

This project includes the following files:

1. localizer.cpp - This implements a 2-dimensional histogram filter for a robot living on a colored cyclical grid by correctly implementing the "initialize_beliefs", "sense", and "move" functions 
2. simulate.cpp - This implements a Simulation class which simulates a robot living in a 2D world. Relies on localization code from localizer.py 
3. helpers.cpp - This contains helper functions for normalizing the grid, checking if the robot is localized, etc. 4. debugging_helpers.cpp - This contains helper functions for debugging when working with grids of floats and chars.
5. tests.cpp - This contains the code for testing the 2D Histogram Filter
