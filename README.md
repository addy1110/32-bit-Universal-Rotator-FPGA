# 32-bit-Universal-Rotator
------------------------------------------------
Implemented a data dependent 32-bit left rotate and 32-bit right rotate on FPGA board. Taking msb-bit of the rotational amount to decide the type of rotation (right/left)

When,
sel <= “0XXXXX”  → perform left rotation
sel <= “1XXXXX”  → perform right rotation

###Technology Used
*	Language : VHDL
*	Simulator: [Xilinx ISE Navigator](http://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/design-tools.html)
*	FPGA: [Nexys4 DDR](http://store.digilentinc.com/nexys-4-ddr-artix-7-fpga-trainer-board-recommended-for-ece-curriculum/) 
*	Programmer : [Digilent Adept](http://store.digilentinc.com/digilent-adept-2-download-only/)

###[Demo Video](https://www.youtube.com/watch?v=LuC0sUbRnCA)

###Functional simulation screen-shots for various test cases

*	When input equals  0000 0000 0000 0000 0000 0000 0000 1111
	Output when select key is “000010”
![alt text](https://github.com/addy1110/32-bit-Universal-Rotator/blob/master/Screenshot/a1_left_b1.JPG)

	Output when select key is “100010”
![alt text](https://github.com/addy1110/32-bit-Universal-Rotator/blob/master/Screenshot/a1_right_b1.JPG)


*	When input equals  0000 0000 0000 0000 0000 0000 1111 1111
	Output when select key is “000100”
![alt text](https://github.com/addy1110/32-bit-Universal-Rotator/blob/master/Screenshot/a2_left_b1.JPG)

	Output when select key is “100010”
![alt text](https://github.com/addy1110/32-bit-Universal-Rotator/blob/master/Screenshot/a2_right_b1.JPG)

