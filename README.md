# oscar_matousek_ne204 Lab1

'Get Spectra.ipynb' is a Jupyter Notebook file that reads in the raw data, applies the trapezoidal filter and pole-zero correction, analyzes the per-waveform time constants, and saves a numpy array containing each waveform's channel number to a file after all anlaysis is completed.

'Create Calibration Values.ipynb' is a Jupyter Notebook File that reads in the aforementioned numpy arrays and uses them to identify peak channel numbers, using these channel numbers to create a first-order energy calibration function. It also contains the code used to plot and analyze spectra.
