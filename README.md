# Chemistry Equation Balancer
 A small python tool that can solve *n* dimensional balancing equations.
***
## Dependencies
*only when using source code*
 - [Numpy](https://numpy.org/)
 - [Sympy](https://www.sympy.org/en/index.html)

 To quickly install the dependencies simply execute
 ```
 pip install -r requirements.txt
 ```
 in the repository cwd.

## Usage
Here are 3 example equations with correct formatting:
```
H + O2 => H2O
CH4 + O2 => CO2 + H2O
(NH4)2CO3 + NaOH => Na2CO3 + NH3 + H2O
```

If you are running CHEB from the source code, you can simply execute ```CHEB.py``` to use it.

If you are running the CHEB release, executing ```CHEB.exe``` will run CHEB.

CHEB also supports passing in arguments for evaluating many balancing equations at once, or for simpler output.

For example:

Executing ```CHEB "H + O2 => H2O"``` will output ```[4, 1, 2]```.

Parameters:
 - ```--full``` Output equation with coefficients rather than just coefficients.
 - ```-f [input_filename]``` Read balancing equations from file.
 - ```-o [output_filename]``` Output balancing equations to file (only if read from file).

## Distributions
You can clone this repository and execute ```CHEB.py``` or download ```CHEB.exe``` from the [releases](https://github.com/AdinAck/Chemistry-Equation-Balancer/releases) section of this repository.

## Learn
Learn about how CHEB works on the [wiki](https://github.com/AdinAck/Chemistry-Equation-Balancer/wiki).
