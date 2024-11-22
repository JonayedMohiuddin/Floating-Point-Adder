# Floating-Point Arithmetic (FPA) - Custom IEEE 754 Implementation  

This repository contains a custom **Floating-Point Arithmetic (FPA)** unit designed according to the IEEE 754 standard with customized parameters. The implementation was created and simulated using **Logisim**, a digital circuit design and simulation tool.  

## Bit Configuration  
The floating-point format in this implementation uses the following structure:  
- **Sign Bit**: 1 bit  
- **Exponent**: 9 bits  
- **Fraction (Mantissa)**: 22 bits  

## Features  
- Supports the following operations:  
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  
- Implements IEEE 754 guidelines, including:  
  - Normalization and rounding  
  - Handling of subnormal numbers  
  - Exceptional cases like Infinity (`Inf`) and Not-a-Number (`NaN`)  

## Software  
- **Logisim**: The entire FPA unit is designed and tested in Logisim, a powerful tool for building and simulating digital circuits.  

## Applications  
This project provides a hands-on approach to understanding and implementing custom floating-point representations. It can be used for:  
- Learning about IEEE 754 standards and floating-point arithmetic.  
- Experimenting with hardware designs tailored for specific applications.  

## Contributing  
Contributions are welcome! Feel free to submit issues, pull requests, or suggestions to enhance the functionality of this project.  

## License  
This project is open-source and licensed under [Your License Here].  

---

### Screenshot  
_Add a screenshot of the Logisim circuit here for better visualization!_  

### Getting Started  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/repo-name.git
