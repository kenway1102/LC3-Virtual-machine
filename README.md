# LC3-Virtual-machine

This program is a virtual machine based on LC3 or Little Computer 3.

## Running the VM
To run the VM compile lc3.c

    gcc lc3.c -o lc3-vm

run the following command

    ./lc3-vm path/to/objFile
Provide the path to your pre assembled LC3 application object file.
use this tool to assemble your .asm file

[LC3-tool](https://wchargin.com/lc3web/)

## Sample Applications

Here are some sample applications for LC3
- [Rogue](https://www.jmeiners.com/lc3-vm/supplies/rogue.obj)
- [2048](https://www.jmeiners.com/lc3-vm/supplies/2048.obj)

## Acknowledgments

  - Project inspired by [justin meiners](https://github.com/justinmeiners) VM LC3
  - [LC3 - ISA](https://www.jmeiners.com/lc3-vm/supplies/lc3-isa.pdf)
