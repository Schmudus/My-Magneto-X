Here are my complete Magneto X config files. They differ from the original Peopoly oners.
I also use a nozzle brush (real brush, not that rubber thing)
Have fun :-)

Print start macro (Standard/PLA, PETG, ...)is doing as follows:<br>
Homing<br>
Preheat to bed=50/nozzle=150 (Bed only if actual temp lower than 50°C)<br>
Clean nozzle (brush) while nozzle temp is set to 140°C<br>
Wait until nozzle is cooled down to 140°C (Shrink the Filament a little to avoid oozing)<br>
Fast clean nozzle<br>
Home only Z with clean nozzle<br>
Do a Quad gantry level<br>
Heat up bed and nozzle to print temperatures<br>
Do a purge line<br>
Clean nozzle<br>
Load Mesh and Skew<br>
Print!<br>
<br>
<br>
Print start macro (ASA/ABS/ABS-GF)is doing as follows:<br>
Homing<br>
Preheat to final bed temperatur<br>
Wait for chamber temperature reach 42°C<br>
Preheat nozzle to 150°C<br>
Clean nozzle while nozzle temp is set to 140°C<br>
Wait until nozzle is cooled down to 140°C (Shrink the Filament a little to avoid oozing)<br>
Clean nozzle<br>
Home only Z with clean nozzle<br>
Do a Quad gantry level<br>
Do a purge line<br>
Clean nozzle<br>
Load Mesh and Skew<br>
Print!<br>
<br>
<br>
------ UPDATE 2024-10-22 ------<br>
Installed TMC Auto Tune for Z and Extruder<br>
Installed TMC2240 for Z<br>
<br>
------ UPDATE 2024-10-22 ------<br>
Changed lead screws to different brand (PTFE coated)<br>
Installed new Z-Stepper motors with 0.9° and set TMC to 1.2A<br>
<br>
---- UPDATE 2024-10-30 ----<br>
Changed extruder motor to a much stronger one (1.83A rated current, TMC set to 1.1 / 0.6A and max_power: 1.0 in extruder section in printer.cfg) to get rid of the extruder skiping. <br>
<br>
Added my own designed and printed parts<br>
