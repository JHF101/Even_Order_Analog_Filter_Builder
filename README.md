# Even Order Filter Calculator and Builder

The even order filter calculator can calculate lowpass or highpass analog filters designed using opamps. 

The Equal Component Filter Calculator "FilterCalculator" class calculates this type of design method's relevant capacitor and resistor components. It does not build the filters.

The Unity Gain Filter Calculator "UnityGainFilterCalculator" class is the class that can automatically build an optimised (minimises the error between the theoretically calculated value from values that are available in the real world, i.e. E96 ) real-world implementation of the filter for LTSpice. 

## Usage 
In order to build the Unity Gain Filter, run the "Filter_Builder" class. After that, run the "UnityGainFilterCalculator" class. The user will now be able to design the filter according to their specification. The "Filter_Builder" class should be run in conjunction with the "UnityGainFilterCalculator" because the setup is not designed for the "FilterCalculator" under the Sallen-Key Equal Component Design section. 

The classes and functions have descriptions of their purposes, input and output parameters.

## Bugs
- Indexing errors occur when the optimisation function cannot find an adequate solution (occurs when decimal place accuracy is too large or when the filter capacitance and resistor range of values are too small) 
