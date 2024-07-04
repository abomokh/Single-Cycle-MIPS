## README

# Single Cycle MIPS Processor in Logisim

This repository contains the implementation of a Single Cycle MIPS processor using Logisim. The project includes support for additional instructions to enhance the processor's functionality.

## Features

- Single Cycle MIPS processor design
- Support for additional instructions: `addi`, `jump`, `jr`, `bne`, `sll`, `ori`, and a custom `jnezr`
- Modifications to control units and data paths
- Utilizes Logisim components such as multiplexers, shifters, and splitters
- Verification through instruction set encoding and simulation using MARS and SPIM simulators

## Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Single-Cycle-MIPS-Processor.git
    ```

2. Open the project in Logisim:
    - Open Logisim and load the `single_cycle_mips.circ` file.

3. Implemented Instructions:
    - `addi`: Add immediate (file 1)
    - `jump`: Jump (file 2)
    - `jr`: Jump register (file 3)
    - `bne`: Branch if not equal (file 4)
    - `sll`: Shift left logical (file 5)
    - `ori`: OR immediate (file 6)
    - `jnezr`: Jump if not equal zero register (file 7)

4. Testing:
    - Verify the correctness of the implementation through direct instruction set encoding and simulation.
    - Use the MARS or SPIM simulators for additional testing:
        - [MARS Simulator](http://courses.missouristate.edu/KenVollmar/mars/index.htm)
        - [SPIM Simulator](http://spimsimulator.sourceforge.net)

## File Structure

- `single_cycle_mips.circ`: Logisim circuit file for the Single Cycle MIPS processor
- `README.md`: Project description and instructions
- `example_data.mem` and `example_instructions.mem`: Example memory files for testing

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions that improve the functionality or efficiency of the processor.

## Acknowledgments

Special thanks to the resources and tools provided by Cornell University and the developers of MARS and SPIM simulators.
