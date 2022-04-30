# virgule-hex
what is here: these are hex files you can upload into the RISC-V simulator--VIRGULE with emulsiV.
the sim is here: http://tice.sea.eseo.fr/riscv/
A blog post about this is here: https://audiodiwhy.blogspot.com/2022/04/risc-v-way-of-future-and-virgule.html
The code you find in the repository:

aa-load-some-registers   ; first thing I wrote!  Get some values into source registers.

AB-ascii hex   ; load 2 values into the ASCII display.

audiodiwhy-ascii.hex  ; load a string into the ASCII display.  There must be a better way to do this right, but my code works....

blank.hex   ;loads zilch into memory....so, blank out the memory, so you can start writing fresh code.

blink-run.hex   ;the classic Blink LED yaddah yaddah; don't leave home without it!

blink-step.hex  ;more blink, but designed to step through the code, not just run it.

cl-ascii.hex      ;more ASCII fun  

jal and jalr.hex  ; simplest code I could come up with to show how these 2 critical instructions work.  Mess with IMM values and registry values to illustrate.

program.hex   ; don't remember what this does.  

save2mem100   ; simple example of saving data to virgule "memory slot" decimel 100 

write-LEDs.hex   ; puts the GPIO LEDs into write and lights up LEDs
