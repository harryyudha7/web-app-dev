
# Pressure vs Temperature Visualization App using Dash

This is a beginner-friendly Dash application that allows users to visualize the relationship between pressure (psig) and temperature (°F) through an interactive plot. The app is built using Python's Dash framework and is a simple yet powerful tool to demonstrate the basics of creating interactive web applications.

## Overview

The application is designed to take user inputs for pressure and temperature ranges, along with the step size, to generate a corresponding plot that shows how temperature varies with pressure. The interface is divided into three main sections: 

1. **Header Block**: Displays the title or other header information.
2. **User Input Block**: Allows users to input the pressure and temperature range, along with the step size.
3. **Result Block**: Shows the resulting plot based on the input data.

The layout of the application is visually structured using a combination of HTML and CSS styles provided by the Dash framework.

## Application Layout

- **Header Block**: This section is simply a placeholder for the header of the app.
- **User Input Block**: 
  - Users can input the start and end values for pressure (psig) and temperature (°F).
  - The step size determines the increments for the pressure and temperature values.
  - A "Run" button triggers the calculation and updates the plot.
- **Result Block**: 
  - This section displays the generated plot, which dynamically updates based on the user inputs.
  - The plot shows the relationship between pressure (psig) on the x-axis and temperature (°F) on the y-axis.

## Getting Started

### Prerequisites

To run this app, you need to have Python installed along with the following libraries:
- Dash
- Numpy

You can install these dependencies using pip:

```bash
pip install dash numpy
```

### Running the Application

To run the application, execute the following command in your terminal:

```bash
python app.py
```

Once the server is running, you can view the app in your web browser at `http://127.0.0.1:8050/`.

### Usage

1. Set the desired range for pressure and temperature using the input fields.
2. Specify the step size for how much each subsequent value should increase.
3. Click the "Run" button to generate the plot.
4. The plot will display the relationship between pressure and temperature based on the inputs provided.

## Example

The app will generate a plot similar to the one below:

![Example Plot](image.png)

## Customization

The application layout and styling can be easily customized by modifying the `layout` dictionary and CSS styles within the `app.py` file. 

## Conclusion

This simple Dash app is an excellent starting point for beginners looking to get familiar with creating interactive data visualizations and web applications in Python.
