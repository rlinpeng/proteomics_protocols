# LiP-MS Protocol
### For bacterial pellets
### Developed in the Picotti lab by Ludovic Gillett, modified here by Noelle Held

### Materials
* Native lysis buffer - ice cold (100 mM HEPES pH 7.5, 150 mM KCl, 1 mM MgCl2)
* Acid washed <106um glass beads, resuspended
* Proteinase kinase 1ug/uL stocks (from freezer stocks; dilute in 25mM ambic)
* Positive control solution - usually prepared in 100 mM HEPES pH 7.5
* Negative control solutions
* 10% DOC solution made in 25mM ammonium bicarbonate
  * 10% w/v DOC = 0.1g sodium deoxycholate in 1mL 25mM ammonium bicarbonate.
* ambic 25mM
  * 25mM ammonium bicarbonate = 0.1977g in 100mL water.
  * 100mM ammonium bicarbonate = 0.7906g in 100mL water.
* 200mM DTT (30.85mg DTT in 1mL ammonium bicarbonate) - make day of use
  * Note: 15.4mg DTT in 1mL makes approximately 100mM DTT, not 200mM.
* 1M iodoacetamide (IAA/IODA; 184.96mg IAA in 1mL ambic) - make day of use and protect from light
* 0.1ug/uL trypsin/LysC mix - make day of use and keep on ice
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

### Preparation checklist
* Before starting lysis
  * Chill native lysis buffer, bead-beating tubes, and centrifuge to 4C.
  * Prepare 1:1 glass bead slurry in cold lysis buffer.
  * Confirm BCA standards, BCA reagents, and plate/tubes are ready.
* Before starting LiP
  * Confirm protein concentrations from BCA and decide whether each sample will use 25ug or 50ug protein.
  * Prepare or thaw kanamycin master stock and make 5mg/mL kanamycin working stock if running +Kan samples.
  * Prepare/dilute 0.1ug/uL PK in 25mM ambic and keep on ice.
  * Pre-set PCR blocks to 25C, 99C, and 4C.
  * Label +Kan/-Kan and +PK/-PK tubes clearly before timed steps begin.
* Before starting trypsin digest
  * Make 200mM DTT day of use.
  * Make 1M IAA/IODA day of use and protect from light.
  * Prepare enough 100mM ABC/ambic for DOC dilution.
  * Prepare 0.1ug/uL trypsin/LysC day of use and keep on ice.
  * Confirm thermal mixer settings for 27C and overnight 37C incubation.
* Before starting C18 cleanup
  * Calculate Buffer A, Buffer B, and methanol volumes based on sample number.
  * Prepare Buffer A and Buffer B fresh or confirm they are available.
  * Confirm the centrifuge units/settings for the C18 plate; rpm and rcf are not interchangeable.
  * Label waste and elution plates before loading samples.

### Suggested day split
* Day 1: native lysis from filters, BCA assay, LiP reaction, DOC quench, DTT reduction, IAA alkylation, DOC dilution, trypsin/LysC addition, and start overnight digestion at 37C.
* Day 2: formic acid quench, DOC precipitation/removal, filter plate cleanup, C18 cleanup, speedvac drying, and storage.

### Day 1 - Native Cell Lysis from Filters with Bead-beater
* Make Native Lysis Buffer (100 mM HEPES pH 7.5, 150 mM KCl, 1 mM MgCl2) and keep ice cold.
* Make a 1:1 bead slurry with acid-washed glass beads and cold lysis buffer.
* Place Trichodesmium filters into cold lysis buffer in bead-beating tubes.
* Add enough bead slurry to cover the filter.
  * Previous notes indicate ~600uL of 1:1 beads in lysis buffer was used.
  * If the slurry was truly 1:1, this corresponds to approximately 300uL beads + 300uL lysis buffer.
* Bead beat samples with ice on hand.
  * Original reference condition: 2 rounds of 30s at speed 20.
  * Keep tubes on ice between bead-beating rounds.
* Centrifuge lysates for 10min at 16,000 rcf, 4C.
* Carefully transfer the supernatant to a fresh tube.
  * Avoid disturbing beads, filter material, cell debris, and foam.
* Centrifuge the transferred supernatant again to further clarify the lysate.
  * Likely same or similar conditions: 10min, 16,000 rcf, 4C, unless otherwise noted.
* Transfer clarified supernatant to a clean tube.
* Perform BCA assay.
  * Use 10uL standard or sample per reaction.
  * Incubate BCA reactions for 30min according to assay instructions.
* Measure absorbance and calculate protein concentration from the BCA standard curve.
* Estimated time needed: 1.25-1.75hr total, with ~90min as a practical planning estimate.
  * Prepare filters, lysis buffer, beads, and tubes: 10-15min.
  * Bead beating plus cooling between rounds: 5-10min.
  * First centrifugation: 10min.
  * Transfer supernatant: 5min.
  * Second centrifugation: 10min.
  * Transfer clarified lysate: 5min.
  * Set up BCA standards and samples: 10-20min.
  * BCA incubation: 30min.
  * Plate/tube reading and calculations: 5-10min.                             

### Day 1 - LiP
#### Timing and temperatures must be exact; use a lab timer to maintain timing between strips. If working with multiple strips, offset 2 min between strips.
* Choose how much protein to carry forward based on extraction yield.
  * Standard yield option: carry forward 50ug protein.
  * Low yield option: carry forward 25ug protein.
* Dilute each sample with native lysis buffer to 50uL total volume in PCR tubes.
  * 50ug protein in 50uL = 1ug/uL.
  * 25ug protein in 50uL = 0.5ug/uL.
* Prepare kanamycin working stock for +Kan samples.
  * Start with 50mg/mL kanamycin master stock.
  * Dilute 1:10 in 25mM ambic to make 5mg/mL kanamycin working stock.
  * Add 0.5uL of 5mg/mL kanamycin working stock to +Kan samples.
  * Add 0.5uL of 25mM ambic to -Kan samples.
  * This gives approximately 50ug/mL kanamycin in the 50uL protein reaction before PK addition.
* Incubate +Kan and -Kan samples at 25C for 10min.
* Prepare PK on ice.
  * Use 0.1mg/mL PK stock, equivalent to 0.1ug/uL.
  * Prepare/dilute PK in 25mM ambic.
  * Add PK at a 1:100 PK:protein mass ratio.
* Add PK or ambic control.
  * For 25ug protein samples: add 2.5uL of 0.1ug/uL PK to +PK samples, or 2.5uL of 25mM ambic to -PK samples.
  * For 50ug protein samples: add 5uL of 0.1ug/uL PK to +PK samples, or 5uL of 25mM ambic to -PK samples.
  * General formula: PK volume (uL) = protein amount (ug) / 10 when using 0.1ug/uL PK stock.
* Start timer, mix shortly, centrifuge quickly, and incubate 5min at 25C.
* Transfer tubes to 99C, incubate 5min exactly
* Transfer tubes to 4C PCR block, incubate 5mins
* Add the same volume of 10% DOC as the current reaction volume to quench the reaction.
  * 25ug protein setup: approximately 53uL reaction volume after Kan/control and PK/control additions, so add ~53uL 10% DOC.
  * 50ug protein setup: approximately 55.5uL reaction volume after Kan/control and PK/control additions, so add ~55.5uL 10% DOC.
* Estimated time needed for the LiP section: 45-60min, or 60-75min if running multiple strips with 2min offsets.
  * Dilute protein samples to 50uL: 10-15min.
  * Prepare 5mg/mL kanamycin working stock: 5min.
  * Add +Kan/-Kan treatment: 5min.
  * Kanamycin/control incubation at 25C: 10min.
  * Prepare/check PK stock on ice: 5min.
  * Add PK or ambic control, quick mix/spin: 5min.
  * PK digestion at 25C: 5min.
  * Heat inactivation at 99C: 5min.
  * Cool at 4C: 5min.
  * Add 10% DOC quench: 5min.

### Day 1 - Trypsin Digest Setup and Overnight Digestion
* Reduce disulfide bonds with 200mM DTT to 5mM final concentration.
  * Calculate DTT volume based on the current sample volume after LiP quench.
  * Exact calculation: DTT volume = current sample volume x 5mM / (200mM - 5mM), or current sample volume / 39.
  * Quick approximation: DTT volume = current sample volume / 40.
  * Previous fixed-volume example: 112uL sample + 2.82uL 200mM DTT stock.
* Incubate 40min at 27C, 500rpm in the thermal mixer. DOC may precipitate.
* After DTT incubation, determine or calculate the current sample volume.
  * Example from previous run: current volume after DOC + DTT was 108.2uL.
* Alkylate samples with IAA at 1:25 of the final alkylation volume.
  * Flexible calculation: IAA volume = current sample volume / 24.
  * Example from previous run: 108.2uL / 24 = 4.508uL IAA.
  * Final post-IAA volume in this example: 108.2uL + 4.508uL = 112.708uL.
* Incubate 30min at room temperature in the dark, 500rpm.
* Dilute samples with 100mM ABC/ambic to a DOC concentration of 1%.
  * If the sample is approximately 5% DOC after LiP quench, dilute 5-fold to reach 1% DOC.
  * Flexible calculation: final diluted volume = post-IAA volume x 5.
  * Flexible calculation: 100mM ABC/ambic volume to add = post-IAA volume x 4.
  * Example from previous run: 112.708uL x 5 = 563.54uL final volume, so add 450.832uL 100mM ABC/ambic.
  * Rounded example addition: add ~450uL 100mM ABC/ambic.
  * DOC may still be precipitated.
* Add 10uL of a 0.1ug/uL trypsin/lysC mix stock prepared on ice. This is equivalent to about 1ug added per 50ug protein reaction which is reasonable. Incubate overnight at 37C, can check pH with pH strip should be about 8.
* Day 1 stopping point: incubate samples overnight at 37C.

### Day 2 - Digest Quench and DOC Removal
* Quench digestion by adding 50% FA to a final concentration of 2%.
  * Flexible calculation: 50% FA volume = pre-quench sample volume / 24.
  * Previous run example: added 24uL of 50% FA.
  * DOC will pop and precipitate; keep tubes open or vented briefly as appropriate to avoid pressure buildup.
  * Vortex and make sure formic acid and DOC have fully mixed.
  * Note from previous run: the exact wait time for "after some time" was not confirmed.
* If white DOC precipitate remains floating, centrifuge to clarify before filter plate cleanup.
  * Previous troubleshooting spins:
  * 16,000rpm for 10min: white precipitate still floating.
  * 18,000rpm for 10min: additional clarification attempt.
  * 20,000rpm for 15min: additional clarification attempt.
  * Note: rpm is rotor-dependent; convert to rcf for future runs if possible.
* Remove DOC by transferring samples to a filter plate and centrifuging.
  * Eluent contains peptides/proteins.
  * DOC precipitate should stay on the filter.

### Day 2 - C18 cleanup
* Calculate how much Buffer A and Buffer B to prepare based on the number of samples/wells.
  * Let N = number of samples/wells being processed.
  * Buffer B needed per sample = 2 x 200uL conditioning washes + 2 x 150uL elutions = 700uL.
  * Buffer A needed per sample = 3 x 200uL equilibration washes + 4 x 200uL post-sample washes = 1400uL.
  * Add 10-20% extra volume for pipetting/reservoir dead volume.
  * Buffer B total = N x 700uL x 1.1-1.2.
  * Buffer A total = N x 1400uL x 1.1-1.2.
  * Optional methanol calculation: LC-grade methanol needed per sample = 2 x 200uL = 400uL, plus 10-20% extra.
* Prepare desalting buffers.
  * Buffer B = 50% acetonitrile, 0.1% formic acid.
  * Buffer A = 1% acetonitrile, 0.1% formic acid.
  * For any final buffer volume V: 0.1% formic acid = V x 0.001.
  * For Buffer B: acetonitrile = V x 0.50, formic acid = V x 0.001, bring to V with water.
  * For Buffer A: acetonitrile = V x 0.01, formic acid = V x 0.001, bring to V with water.
* Wash C18 columns with 200uL LC-grade methanol 2x; centrifuge.
* Wash 2x with 200uL Buffer B.
* Wash 3x with 200uL Buffer A.
* Add sample to column and elute through slowly; can repeat this if working with little protein material.
  * Use the minimum centrifuge speed/time needed for liquid to pass through the C18 plate.
  * Previous note: 1300 rcf during washing may have eluted the sample too quickly; 600rpm was tried to slow elution.
  * Confirm whether the centrifuge is set to rpm or rcf before repeating, because these are rotor-dependent.
* Wash 4x with 200uL Buffer A and discard waste.
  * Previous C18 plate optimization with Buffer A: 1300 for 3min did not elute; 1500 for 5min did not elute; 1800 for 5min worked.
  * Units should be confirmed as rpm or rcf before repeating.
* Elute into a clean plate with 2x 150uL Buffer B.
  * Previous C18 plate optimization with Buffer B: 1800 for 5min worked.
  * Units should be confirmed as rpm or rcf before repeating.
* speedvac samples to dryness
* store samples at -20C, resuspend in water or buffer B prior to analysis, centrifuge and transfer top volumes to autosampler vials
* Estimated time needed for C18 cleanup: 1.5-2.5hr before speedvac drying, depending on sample number and centrifuge/elution times.
  * Calculate and prepare Buffer A/Buffer B: 10-20min.
  * Set up plates, reservoirs, and samples: 10-15min.
  * Methanol conditioning washes: 10-15min.
  * Buffer B conditioning washes: 10-15min.
  * Buffer A equilibration washes: 15-25min.
  * Load and pass samples through C18 plate: 10-30min, depending on sample viscosity and centrifuge settings.
  * Buffer A post-sample washes: 20-35min.
  * Buffer B elution into clean plate: 15-25min.
  * Speedvac to dryness: variable, often 1-3hr or longer depending on volume and instrument.
