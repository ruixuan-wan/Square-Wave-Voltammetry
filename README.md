# LabVIEW Square Wave Voltammetry (SWV) Program

## Overview
This LabVIEW program enables the connection of a CV-27 Bioanalytical Systems Voltammograph to a National Instruments (NI) data acquisition (DAQ) card for performing Square Wave Voltammetry (SWV) measurements. The software allows users to configure essential SWV parameters, view real-time raw data (current and voltage), and visualize the processed data as an SWV graph. Additionally, users can save the acquired data for further analysis.

This code is developed for use in CHEM 426/526 Instrumental Analysis at the University of Washington.

## Features
- **Potentiostat Connection**: Seamlessly interfaces with a National Instruments DAQ card.
- **SWV Measurement**: Configure and execute Square Wave Voltammetry with adjustable parameters.
- **Real-Time Data Display**: View both raw current/voltage data and processed SWV graphs.
- **Data Saving**: Export measurement results for further analysis.

## Installation
1. Ensure that LabVIEW and NI-DAQ drivers are installed on your system.
2. Connect the potentiostat to the NI DAQ card: Iout and App.E are connected to selected AI ports on the NI-DAQ card, Ext. in needs to be connected to selected AO port on the NI-DAQ card. 
3. Open the LabVIEW project file.
4. Configure the necessary SWV parameters in the program interface.

## Usage
1. Launch the LabVIEW application and load the SWV program.
2. Connect your potentiostat to the NI DAQ card.
3. Set up the SWV parameters (e.g., pulse period, pulse amplitude, pulse width, step potential, voltage range, finish voltage, scan rate).
4. Start the SWV measurement.
5. Observe the real-time raw data and processed SWV graph.
6. Save the acquired data for further analysis.

## Data Output
- **Raw Data**: Displays the recorded current and voltage values.
- **Processed Data**: Generates an SWV plot based on the acquired data.
- **Save Options**: Allows exporting data in a user-defined format (e.g. csv, txt).
