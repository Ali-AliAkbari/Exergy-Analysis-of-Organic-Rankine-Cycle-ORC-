# Exergy Analysis of Organic Rankine Cycle (ORC) 

## Overview
This project analyzes the exergy efficiency and thermodynamic performance of different working fluids in an Organic Rankine Cycle (ORC) and Regenerative Organic Rankine Cycle (RORC). The analysis is performed using **Python** and the **CoolProp** library for thermodynamic property calculations.

This code is designed to validate the results presented in the research paper:
> *Exergy analysis of organic Rankine cycle for waste heat recovery using low GWP refrigerants* - A. E. Elahi et al., International Journal of Thermofluids, 2022.

## Features
- Exergy and thermal efficiency calculations for various ORC configurations.
- Comparison of different low GWP refrigerants such as **R1234ZE(Z), R1233zd(E), R113, R1234yf**.
- Visualization of thermal and exergy efficiencies under different turbine inlet pressures.
- Graphical representation of exergy destruction rates in ORC components.
- **Validation**: The results from this code have been compared with the paper's results for **R1234yf fluid**, confirming the accuracy of the thermal and second law (exergy) efficiency calculations.

## Requirements
Make sure you have the following dependencies installed before running the code:

```bash
pip install numpy matplotlib CoolProp
```

## Results & Visualization
The project includes various **matplotlib** plots comparing different fluids and their efficiency metrics. Key comparisons include:
- **Thermal Efficiency vs. Turbine Inlet Pressure**
- **Exergy Destruction in Different ORC Components**
- **Net Power Output for Different Fluids**
- **Validation of Results with Research Paper for R1234yf Fluid**

## References
This project is based on the paper:
> *Exergy analysis of organic Rankine cycle for waste heat recovery using low GWP refrigerants* - A. E. Elahi et al., International Journal of Thermofluids, 2022.

## License
This project is released under the **MIT License**. Feel free to use and modify it for academic and research purposes.

## Author
**Ali AliAkbari** - [ali.aliakbari@ut.ac.ir]

