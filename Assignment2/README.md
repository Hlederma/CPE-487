# 8-Bit Parity Generator

## VHDL Files
* Architecture: [parity.vhd](./parity.vhd)
* Test Bench: [tb_parity.vhd](./tb_parity.vhd)
* Value Change Dump: [pairty.vcd](./parity.vcd)

## GTKWave of Test Bench
![This is an image](https://github.com/Hlederma/CPE-487/blob/9833abc277394048857d9cbe7ec495b5850b7e8f/Assignment2/parity.png)

## Commands Used to Run VHDL files
```sh
$ ghdl -a parity.vhdl
$ ghdl -a tb_parity.vhdl
$ ghdl -e tb_parity
$ ghdl -r tb_parity --vcd=parity.vcd
$ gtkwave parity.vcd
```

## Citations
F. Cayci, “VHDL-digital-design/parity.vhd at master · FCAYCI/VHDL-digital-design,” GitHub, 31-Oct-2019. [Online]. Available: https://github.com/fcayci/vhdl-digital-design/blob/master/rtl/parity.vhd. [Accessed: 08-Feb-2022].  

F. Cayci, “VHDL-digital-design/TB_PARITY.VHD at master · FCAYCI/VHDL-digital-design,” GitHub, 31-Oct-2019. [Online]. Available: https://github.com/fcayci/vhdl-digital-design/blob/master/tb/tb_parity.vhd. [Accessed: 08-Feb-2022]. 
