# Signals-and-Systems
## Introduction
This Python script performs signal processing tasks such as filtering and correlation analysis on input and output signals. It provides functionality to apply low-pass, high-pass, and band-pass filters to an input signal and then compares the filtered signals with an output signal to determine the best matching filter.

## Instructions

### 1. Input Signals
Ensure that the input and output signals are stored in separate text files. Update the file paths in the code to point to these files:
- Input File: `input_file_path = "/content/INPUT-SIGNAL-X(t).txt"`
- Output File: `output_file_path = "/content/OUTPUT-SIGNAL-Y(t).txt"`

### 2. Environment Setup
Install the required dependencies:
- Python 3.x
- NumPy (`pip install numpy`)
- SciPy (`pip install scipy`)
- Matplotlib (`pip install matplotlib`)

### 3. Run the Code
Execute the Python script `B22ME053.py`.

## Output
- The script generates plots (optional) to visualize the signals and filter effects.
- It prints the correlation values for each filter and identifies the best matching filter.

## Additional Notes
- The code assumes specific file paths for the input and output signals. Modify these paths in the script if necessary.
- The predefined filter kernels in Method 2 can be adjusted based on your specific signal characteristics.
- Make sure to have NumPy and SciPy libraries installed to run the script successfully.
- The code provides two methods for signal processing:
  - **Method 1**: Uses built-in functions from the `scipy.signal` module.
  - **Method 2**: Directly convolves the input signal with filter kernels.
  
  Method 1 may be preferred for its simplicity and use of well-established functions, while Method 2 offers more flexibility in defining custom filter kernels.

