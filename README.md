# AB Test Simulation in MATLAB and Python

This repository contains code to simulate a large number of A/B test iterations in both MATLAB and Python. The visual output of the simulation presents the number of visitors on the X-axis and shows the percentage of improvements on the Y-axis. The primary objective of this code is to help those new to A/B testing and statistics understand the importance of significance testing. It demonstrates why we cannot solely trust the numbers in a test without considering the influence of random variation on the measured metrics.

## Features

- Generates random conversion rates for different versions being tested.
- Simulates visitor interactions based on these conversion rates.
- Visualizes observed conversion improvements over time.
- Allows for "AA tests" where all versions are identical, to observe the role of random variation.
- The Python version allows interactive visualization with sliders to adjust parameters in real-time.

## Usage

### MATLAB Version

1. Set the desired parameters at the beginning of the script, such as:
   - `base_conv`: Base conversion rate.
   - `factor`: Factor by which conversion rate can vary.
   - `aa_test`: Set to 1 for AA test, 0 otherwise.
   - `versions`: Number of different versions being tested.
   - `new_vis_per_iter`: Number of new visitors in each iteration.
   - `set_iter`: Number of iterations.
   - `num_sims`: Number of simulations.
2. Run the script in MATLAB.
3. Observe the plotted results, which show the true conversion improvements and the observed conversion improvements over time.

### Python Version (Recommended for Latest Improvements)

1. Open the Jupyter Notebook file in JupyterLab or Jupyter Notebook.
2. Adjust the parameters using the provided sliders and checkboxes.
3. Click on the "Run Simulations" button to run the simulation with the selected parameters.
4. Observe the plotted results interactively.

## Dependencies

- MATLAB Version: This code uses the `brewermap` function for generating color maps. Ensure you have this function available in your MATLAB path or replace it with an alternative color map function.
- Python Version: Requires `matplotlib`, `numpy`, and `ipywidgets`. Ensure these libraries are installed in your Python environment.

## License

[MIT](LICENSE)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For any questions or feedback, please contact [Erik Malkemus](mailto:erikmalk@gmail.com).

## Note

While both MATLAB and Python versions accomplish similar tasks, there might be slight differences in features and user interface. The Python version is recommended for the latest improvements and interactive visualization capabilities.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/erikmalk/AB_Test_Simulation/HEAD?labpath=AB_Test_Simulations_Gen.ipynb)