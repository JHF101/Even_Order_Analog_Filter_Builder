# Even Order Filter Calculator and Builder

The even order filter calculator can calculate lowpass or highpass analog filter designed using opamps. 

The Equal Component Filter Calculator Class calculates the relevant components of this type of design method. It does not build the filters.

The Unity Gain Filter Calculator Class is the class that can automatically build an optimised(minimises the error between the theoretically calculated value from values that are available in the real world, i.e. E96 ) real-world implementation of the filter for LTSpice. 

## Usage 
The classes and functions have descriptions of their purpose, input and output parameters. The notebook also contains design information.

## Bugs
- Indexing errors occur when the optimisation function cannot find an adequate solution (Occurs when decimal place accuracy is too large or when the filter capacitance and resistor range of values are too small) 