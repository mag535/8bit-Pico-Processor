# 8bit-Pico-Processor
ECE 472 - Project 2 assignment (VLSI II)

Research Paper #1
https://www.researchgate.net/publication/259864953_Pico_Processor_Using_Verilog_HDL

Shared Project Library  
/home/ECE472_572/8bitPicoProcessor

For now whenever you make a new file in the shared library you need to go to the command line and run these commands for the cell view.  

`chmod -R 770 <cell name>`  
`chgrp -R ECE472_572 ./<cell name>`

## Standards

1. All variables in Cadence Virtuoso must be capitalized
2. The clock variable is spelled `CLK`
3. Only use the OSU library for standard cells
4. Use 2's Complement for ALU (Professor's note)
5. Use 1fF Capacitor as load. Use 1fF per gate the output is connected to for testing
6. The `CLK` should have a 5ns period (200MHz)


## How to for Git

First, Follow steps [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) all the way to the end to setup
SSH keys for Github.

Next, to add your changes to the remote repo, use these commmads:
  `git add -all`
  `git commit -m "YOUR MESSAGE HERE"`
  `git push origin HEAD:main`
The `--all` tag is because Xunil has Git version 1, which requires this. Git version 2 doesn't.
The `HEAD:main` is also because Xunil has an old version of Git. Just using `main` like you would for version 2 will cause an error.

