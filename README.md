# NativeMS_Analysis
Simple Library for Native MS Analysis based on UniDec and RawFileReader by Thermo

Unidec: https://github.com/michaelmarty/UniDec

RawFileReader: https://github.com/thermofisherlsms/RawFileReader

Settings for deconvolution via Unidec are specified in a config.txt. The config is then also saved in the specified output folder for future reference. A working example on how to use the module can be found in `ms_analysis.ipynb`

## Setting up the environment:
1. Clone this repository
2. Open Terminal and go to the main folder of the repository:
    
    `cd <filepath>`

3. Create and activate a new conda environment:
    
    `conda env create -f environment.yml`