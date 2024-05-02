
# Estimating resistance using ohm's law and Linear regression


This project utilizes ohm's law, which states that the voltage across a resistor is directly proportional to the current flowing through it, to estimate the resistance of an electrical component.

The method of least squares is utilized in this project to fit a linear model to the data obtained from voltage and current measurements. This technique allows us to find the line that best represents the relationship between voltage and current, ultimately enabling us to estimate the resistance of the electrical component under study.

## Method

1.Data Collection:
Voltage and current measurements are obtained using a multimeter. These measurements represent the input-output relationship of the electrical component under study.

2.Linear Regression:
The relationship between voltage (V) and current (I) is represented by Ohm's law equation: V = RI, where R is the resistance. This equation is linear, with current being the independent variable (x) and voltage being the dependent variable (y).

3.Parameter Estimation:
The least squares method is applied to estimate the slope parameter, which corresponds to the resistance in Ohm's law.

4.Result Analysis:
The estimated resistance parameter is printed, providing an approximation of the resistance of the electrical component under study.

5.Plotting the Results:
The best-fit line, representing the linear relationship between current and voltage, is plotted to visualize the estimated resistance.

Outcome:
The project demonstrated how Ohm's law and linear regression can be combined to estimate the resistance of an electrical component. Despite potential noise in the measurements, the estimated resistance closely approximates the true resistance, providing valuable insights into the behavior of the component.
## Tools used

Python programming language

NumPy for numerical computations

Matplotlib for data visualization