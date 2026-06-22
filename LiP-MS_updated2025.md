# LiP-MS Protocol
### For bacterial pellets
### Developed in the Picotti lab by Ludovic Gillett, modified here by Noelle Held

### Materials
* Native lysis buffer - ice cold (100 mM HEPES pH 7.5, 150 mM KCl, 1 mM MgCl2)
* Acid washed <106um glass beads, resuspended
* Proteinase kinase 1ug/uL stocks (from freezer stocks)
* Positive control solution - usually prepared in 100 mM HEPES pH 7.5
* Negative control solutions
* 10% DOC solution
* ambic 25mM
* 200mM DTT (15.4mg in 1mL ambic)
* 1M IODA 
* 0.1ug/uL trypsin/lysC mix
* 50% formic acid LC grade
* 0.2um filter plates
* C18 plates
* LC grade methanol
* Desalting Buffer B (50% acetonitrile-0.1% formic acid)
* Desalting Buffer A (1% acetonitrile-0.1% formic acid)

### Equipment
* 3 block PCR machine
* small PCR quick spinner
* vortexer
* pipettes and multichannel in various sizes, and enough tips nearby
* lab timer
* large centrifuge that can hold plates
* thermal mixers that can hold pcr strips
* speedvac that can hold plates


### Native Cell Lysis
* Resuspend bacterial pellets in a small amount of cold lysis buffer (such as 200uL) and transfer to a tube appropriate for bead beatin
* Add beads in approx 1:1 volume ratio
* Grind cells in bead beater. For E.coli, 2 rounds 30x speed 20 is good. Lysates should get foamy. Keep cold/on ice between pulses.
* Centrifuge at high speed 5min 4C to get rid of cell debris and beads; decant cleanly avoiding foam. 
* Perform protein quantitation according to normal BCA assay.                              

### LiP
#### Timing and temperatures must be exact; use a lab timer to maintain timing between strips. If working with multiple strips, offset 2 min between strips.
* Carry forward 50ug of protein from the cell lysis step; dilute samples to 1g/uL in native lysis buffer and transfer 50ug to PCR tubes
* Prepare PK on ice: dilute 1ug/uL stock 1:10 to 0.1ug/uL in water
* Prepare positive control solutions and negative control solutions, if performing a treatment
* If using positive or negative controls, add these and incubate at 25C for 10mins
* Add 5uL of the 0.1ug/uL PK stock in ratio of 1:100 enzyme: protein. Start timer, mix shortly, centrifuge quickly and incubate 5min 25C
* If using trypsin controls, add 5uL of water to those instead of the PK solution.
* Transfer tubes to 99C, incubate 5min exactly
* Transfer tubes to 4C PCR block, incubate 5mins
* Add same volume (usualy 55uL) of 10% DOC to quench the reaction. 

### Trypsin digest
*  Reduce disulfide bonds with 200mM DTT (final 5mm) 1:40 = 112uL + 2.82uL 200mM stock.                     
* Incubate 40min 27C 500rpm in the thermal mixer. DOC may precipitate. 
* Alkylate samples in final IODA 40mM   – 1:25 = add 4.7 uL IAA                
* Incubate 30min room temperature dark 500rpm    
* Dilute samples with 100mM ABC to a DOC concentration of 1% (add 430uL). DOC may still be precipitated.
* Add 10uL of a 0.1ug/uL trypsin/lysC mix stock prepared on ice. This is equivalent to about 1ug added per 50ug protein reaction which is reasonable. Incubate overnight at 37C, can check pH with pH strip should be about 8.
* Quench digestion by adding 50% FA to final concentration of 2% (add 25uL of the 50% FA). DOC will pop and precipitate; keep tubes open to avoid popping. After some time, vortex and make sure formic acid and DOC have fully mixed. 
* Remove DOC by transfering samples to a filter plate and centrifuging; eluent contains proteins and DOC will stay on the filter. 

### C18 cleanup
* wash C18 columns with 200uL LC grade methanol 2x - centrifuge
* wash 2x with 200uL buffer B
* wash 3x 200uL buffer A
* add sample to column and elute through slowly; can repeat this if working with little protein material
* wash 4x buffer A 200uL and discard waste
* Elute into a clean plate with 2x 150uL buffer B 
* speedvac samples to dryness
* store samples at -20C, resuspend in water or buffer B prior to analysis, centrifuge and transfer top volumes to autosampler vials
