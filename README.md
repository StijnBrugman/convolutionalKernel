# Convolution Kernal on 2D matrix



## Details
* Kernal size: 3x3
* Matrix size: 80x300

## Implementation steps
- [x] Load distance_vector data from file
- [ ] Run average execution time
- [ ] Implement improvement functionality with FPGA and HLS
- [ ] Quantify performance

## Running the software
```c
$ gcc reference_source_code.c -o program && ./program POS_NUMB MAX_DIS
```

## Flags
Several flags can be added to the command to provide additional functionality.
```c
$ gcc reference_source_code.c -o program -FLAGS && ./program POS_NUMB MAX_DIS
```
flags:
* -O3 : -Ofast | Speeds up the program signifanctly 
* -g | Debug mode

## Useful sources
- https://github.com/Xilinx/Vitis-HLS-Introductory-Examples/blob/master/

## Contact
For more information about the project, you can contact Stijn Brugman ([s.r.d.brugman@student.utwente.nl](mailto:s.r.d.brugman@student.utwente.nl)).
