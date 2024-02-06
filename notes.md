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
		- [x] Go to Kandasamy for help if needed
			- [x] Ask about Unknown parts
			- [x] Ask if the intermediate registers like TEMP and JUMP ADDR can be ignored in design diagram
		- Parts:
			- [ ] PC Control
			- [ ] RA, RB, RD, RJ, R_DEST are 3-bit registers
			- [ ] DISP and CONST, RX and RY, D_DEST are 8-bit registers
			- [ ] SC, RZ is 1-bit register
			- [ ] RM
			- [ ] CLK
   			- [ ] ALU
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


## Logs

### February 6, 2024

What we did
- Added standards to [README.md](/README.md) for making schematics and layouts so that our designs don't conflict
- Presented first design draft
- Decided on doing a pipelined 8-bit Pico Processor

What we need to do:
- [ ] Adjust our cells to first height of OSU library's standard cells.
- [ ] Create a floorplan to determine how everything is connected and be able to divide up the work.

