# Load Value Prediction

## Development Environment:

The notebook can be run on :


 1. Google Collab:
	
	Please Make sure that the trace files (train_pinatrace.out and test_pinatrace.out) are uploaded in the temorary runtime in Google Collab 

 2. Via Jupyter Notebook 
	Additional installations of packages like numpy, pandas, functools, collections may be required.
	Please Make sure that the trace files (train_pinatrace.out and test_pinatrace.out) are in the  same directory as the notebook.
	
You can change the variables 'train_file' and 'test_file' with your own file names which should be in the csv format <PC,Memory address,LoadValue> or the original format eg: 0x7f64b4765e1f: R 0x7f64b4791e68, 0x000000000000000e


## Overview 
The purpose of load value prediction is to be able to predict the value of a memory load instruction.

A major reason why value prediction works is that programs tend to exhibit value similarity behaviors
where values tend to be similar either spatially (neighboring memory addresses) or temporally (repeated
access to the same memory location does not change, for example, a constant value in memory).

The methods implemented in this project are:

1. Last Value Predictor
2. Global Load Value Predictor
3. Local Load Value Predictor
4. Predictable Loads Last Value Predictor

Please read the Report.pdf file for more detail






