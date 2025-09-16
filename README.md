# ABAQUS Python scripting

This repository provides two simple scripts, which showcases how a Python script can be used to run FE models in ABAQUS. The scipts are valid for ABAQUS 2022.

Repository layout:
- **single:** folder which contains the script, which can be run from inside the GUI
  - change the script parameters inside the Python file
  - run the script via: *File -> Run Script...*
- **set:** folder, which contains the files, which are used to run a parameter study
  - *parameters.py*: file, which contains the parameter sets, and the working directory
  - *demoModel.py*: file, which contains the model, the definitions
  - set the desired parameters and working directory in *parameters.py*
  - run the script via CMD: *abaqus cae noGUI=demoModel.py*