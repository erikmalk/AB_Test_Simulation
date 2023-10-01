# AB Test Simulation in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/erikmalk/AB_Test_Simulation/HEAD)

This repository contains code to simulate a large number of A/B test iterations in Python. The visual output of the simulation presents the number of visitors on the X-axis and shows the percentage of improvements on the Y-axis. The primary objective of this code is to help those new to A/B testing and statistics understand the importance of significance testing. It demonstrates why we cannot solely trust the numbers in a test without considering the influence of random variation on the measured metrics.

## Features

- Generates random conversion rates for different versions being tested.
- Simulates visitor interactions based on these conversion rates.
- Visualizes observed conversion improvements over time.
- Allows for "AA tests" where all versions are identical, to observe the role of random variation.
- Allows interactive visualization with sliders to adjust parameters in real-time.

## Usage

1. Open the Jupyter Notebook file in JupyterLab or Jupyter Notebook.
2. Adjust the parameters using the provided sliders and checkboxes.
3. Click on the "Run Simulations" button to run the simulation with the selected parameters.
4. Observe the plotted results interactively.

## Dependencies

- Requires `matplotlib`, `numpy`, and `ipywidgets`. Ensure these libraries are installed in your Python environment.

## License

[MIT](LICENSE)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For any questions or feedback, please contact [Erik Malkemus](mailto:erikmalk@gmail.com).

## Note

For the MATLAB version of this simulation, please visit the [AB_Test_Simulation_MATLAB repository](https://github.com/erikmalk/AB_Test_Simulation_MATLAB.git).
