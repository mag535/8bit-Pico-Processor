# Notes

## Tools

Prototyping
- Figma
- Pencil & Paper / Tablet

Circuit Design
- Cadence Virtuoso

Collaboration
- GitHub
- Discord


## Timeline

Due Dates:
- January 30:	5min Presentation of description of design and implementation
- February 20:	HSPICE simulations verifying functionality (schematic)
- March 5:	Final report which should include Specification, design, testing strategies & results, areas for optimization, layout & schematics

## Tasks

- Prep:
	- [ ] Find or create schematics or HDL code for each component in the processor 
		- [v] Go to Kandasamy for help if needed
			- [v] Ask about Unknown parts
			- [v] Ask if the intermediate registers like TEMP and JUMP ADDR can be ignored in design diagram
		- Parts:
			- [ ] PC Control
			- [ ] RA, RB, RD, RJ, R_DEST are 3-bit registers
			- [ ] DISP and CONST, RX and RY, D_DEST are 8-bit registers
			- [ ] SC, RZ is 1-bit register
			- [ ] RM
			- [ ] CLK
   			- [ ] ALU
      			- [ ] PC Counter
			- [ ] Unknowns
				- [ ] TEMP
				- [ ] P_OUT (register? d flip flop?)
				- [ ] PORT ADDR & PORT DATA
				- [ ] DATA MEMORY (256 Bytes)

- Specification:
	- Use existing design
	- [ ] Summarize logic of Pico processor
	- [ ] Come up with ways to test and verify design
	- [ ] Estimate area
	- [ ] Estimate power 
	- [ ] Estimate performance


 ## Research

 Products using Pico processors:
- [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)
- [Pico-8 Fantasy Console](https://www.lexaloffle.com/pico-8.php)
- [RP2040](https://en.wikipedia.org/wiki/RP2040)

Other:
- [Pico Processor in VHDL](https://www.researchgate.net/publication/259864953_Pico_Processor_Using_Verilog_HDL)
	- Pico processor is scaled down version of RISC processor
	- pipelined, 5 stages
- [8-bit Processing](https://en.wikipedia.org/wiki/8-bit_computing)
