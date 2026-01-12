# Neuroplasticity
This repository contains material related to the article "Mechanistic Explanation of Neuroplasticity Using Equivalent Circuits" in bioRxiv, ([DOI 10.1101/2023.05.21.541639](https://www.biorxiv.org/content/10.1101/2023.05.21.541639v6)). More specifically, it holds SPICE netlists and symbol files for the neuron model and the experiments. The files have been tested with [LTspice XVII, Version 17.0.37.0](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html), but will probably work with other SPICE simulators as well after minor adjustments.

## How to run the simulations:

1. Install [LTspice](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html) if you haven’t already.
2. Download (or clone) the files in this repository.
3. Open LTspice and load the experiment you want to run. The schematics are named `experiment-N.asc`, where `N` is 1, 2, 3, or 4.
4. Run the simulation via **Simulate → Run**.

The relevant traces are defined in the accompanying `.plt` files and will be displayed automatically. Feel free to modify the circuits and parameters for further exploration.
