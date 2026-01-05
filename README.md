# Resonance Frequency HRV Analysis

This script analyzes ECG data from a BITalino device to determine an
individual’s resonance breathing frequency using HRV metrics.

## Requirements
Python 3, numpy, pandas, scipy, matplotlib

## Data
Upload OpenSignals (.txt) files with ECG data in column A2.
Files should include `baseline` or `<number>bpm` in the filename. The code is set up to run 'Camille' data, and can compare 'Luzie' results. Please update the participant numbers and associated .txt files. 

## Usage
1. For recreating the results from our data: Download the ZIP files (CAMILLE & LUZIE), ennsure that the pathway in the code matches the location you have stored the downloads in. 
2. Else: Upload data files
3. Update file paths in the script
4. Run the script

## Output
- HRV plots
- Resonance frequency
- CSV file with HRV metrics
- Comparison table to display the differences between the participants performance in each condition and a complementing bar chart to visualise.
