# HRV_Project
Analysing the signals from the BITalino - calculator for each participants Baroreflex and thus their resonant frequency

# Resonance Frequency HRV Analysis

This script analyzes ECG data from a BITalino device to determine an
individual’s resonance breathing frequency using HRV metrics.

## Requirements
Python 3, numpy, pandas, scipy, matplotlib

## Data
Upload OpenSignals (.txt) files with ECG data in column A2.
Files must include `baseline` or `<number>bpm` in the filename.

## Usage
1. Upload data files
2. Update file paths in the script
3. Run the script

## Output
- HRV plots
- Resonance frequency
- CSV file with HRV metrics
