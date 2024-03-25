# Verification Notebook
Verification for this project is essential to correctly identify tornadoes, hail, and damaging wind in WRF-BCC. Variables from WRF-BCC (updraft vertical velocity, updraft helicity, and downdraft vertical velocity) are used to find simulated instances of these perils. The Fraction Skill Score verifies which variable best identifies an individual hazard. The notebook found in the directory containing this readme file is an attempt to introduce the verification workflow to others in the project who don't yet have the programming skills to accomplish this task. The widgets allow them to augment the threshold/other important settings of the notebook without having to worry about breaking the code.  

### Instructions
The notebook provided in this directory is relatively easy to use, however, there are some important steps to running it properly. It is important to know that there is no need to change any of the code itself, but rather the parameters in the widgets found in the notebook. Some steps on how to correctly work the notebook are provided below:

1. Run all cells before a widget. Widgets are **NOT** variables that say widget, but rather sliders/buttons that can be changed. They look similar to ordering pizza at dominos.com or changing the volume on your computer.
2. Once upon a widget, please make sure to run the cell with the widget **then** make your choice.
3. Proceed to run all the cells to the next widget.

**NOTE:** If you make a new selection, you will have to rerun all cells below that widget; otherwise, the data will not update to the new selection. 

### Purpose
The goal for this portion of the project is two-fold:

1. Which settings for the Fraction Skill Score help define a good and bad variable threshold?
2. What variables and threshold values best indicate a simulated peril?
