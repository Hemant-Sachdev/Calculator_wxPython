# Calculator_wxPython
A simple calculator application built using wxPython for the GUI. This calculator supports basic arithmetic operations such as addition, subtraction, multiplication, division, and includes a clear button.

## Features
 * Basic Operations: Addition (+), Subtraction (-), Multiplication (*), Division (/).
 * Decimal Support: Includes a decimal point (.) for floating-point operations.
 * Clear Button: Resets the calculator display (C button).
 * Evaluation: Press = to evaluate the current expression.

## Requirements
Before running the application, you need to install the following dependencies:
 * Python (3.x)
 * wxPython (version >= 4.x)

## Install wxPython
To install wxPython, use the following command: **pip install wxPython**

## Usage
Clone the repository or download the code.
Navigate to the project folder.
Run the script: **python calculator.py**

## How the Calculator Works
When you click on a number or operation, it gets appended to the display.
Clicking = will evaluate the expression displayed and show the result.
Clicking C will clear the display.

## Code Overview
The calculator GUI is built using wxPython. Below are key components of the code:
 * wx.Frame: The main window of the calculator.
 * wx.TextCtrl: A display area to show inputs and results.
 * wx.GridSizer: Used to organize the buttons into a grid layout.
 * wx.Button: Buttons for numbers, operations, and clear functionality.
 * Event Handling: Button clicks trigger on_button_click to handle input and perform calculations.

## Example Screenshot
![image](https://github.com/user-attachments/assets/ee74e543-16a3-430d-be77-74b2df863ccb)





