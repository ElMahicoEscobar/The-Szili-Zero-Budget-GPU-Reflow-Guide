This guide provides a detailed, step-by-step procedure for attempting a last-resort reflow repair on a non-functional graphics card using minimal tools and household items. This method was developed out of necessity to salvage a dead GPU when professional repair or replacement was not an option.
It prioritizes harm reduction and uses a novel "pre-bake" method with a clothes iron to safely handle homemade flux from denatured alcohol.
Table of Contents
1.	⚠️ CRITICAL SAFETY WARNING
2.	Required Materials
3.	The Procedure
o	Step 1: Preparation & Disassembly
o	Step 2: Calibrating the Heat Source
o	Step 3: Creating the Flux (The Cold Mix Method)
o	Step 4: Flux Application & Pre-Bake (The Clothes Iron Method)
o	Step 5: The Final Reflow
o	Step 6: The Cool Down & Reassembly
4.	Expected Outcome
5.	Contributing
6.	License
7.	Acknowledgments
________________________________________
⚠️ CRITICAL SAFETY WARNING
This is an inherently dangerous procedure that involves high temperatures and flammable materials. You assume all risks. Failure to follow safety precautions can result in fire, property damage, or serious injury.
•	Ventilation: This procedure MUST be performed outdoors or in a space with active, direct ventilation (e.g., a fan in a wide-open window pointing outwards). Rosin and alcohol fumes are hazardous.
•	Fire Safety: Keep a Class B or ABC fire extinguisher within arm's reach at all times. Work on a non-flammable surface (concrete, ceramic tile) and clear the area of all flammable materials.
•	Personal Protective Equipment (PPE): Safety glasses are mandatory. Nitrile gloves are strongly recommended to protect your skin.
________________________________________
Required Materials
Tools
•	A non-functional graphics card (this is a last-resort method).
•	A basic hot air station (e.g., BAKU 852D+ or similar, with analog controls).
•	An old clothes iron with a flat metal base and a low-temperature setting.
•	Household items to create a stable, upside-down stand for the iron (e.g., bricks, sturdy books).
•	A metal bottle cap.
•	A toothpick, needle, or other fine-tipped, non-plastic tool.
Consumables
•	Solid Rosin: Can be sourced from an electronics supply can or by crushing rosin-core solder wire.
•	Solvent: 99% Isopropyl Alcohol (IPA) is highly recommended. If unavailable, this guide is based on using 70% denatured sanitary alcohol, which requires the specific "pre-bake" step to remove water.
•	High-quality thermal paste for reassembly.
________________________________________
The Procedure
Step 1: Preparation & Disassembly
1.	Completely disassemble the graphics card, removing the heatsink, fan shroud, and backplate.
2.	Carefully disconnect all fan headers and other connectors.
3.	Thoroughly clean the old thermal paste from the GPU die and heatsink using your solvent and a lint-free cloth.
4.	Protect heat-sensitive components surrounding the GPU (VRAM, capacitors, plastic connectors) with Kapton tape or small, carefully placed pieces of aluminum foil.
Step 2: Calibrating the Heat Source
If your hot air station lacks a precise temperature display, this step is crucial.
1.	Place a small piece of solder wire onto a scrap PCB or in your metal bottle cap.
2.	Set your hot air station's airflow to LOW and the temperature dial to its minimum setting.
3.	Slowly increase the temperature dial in small increments, waiting a few seconds at each step.
4.	Observe the solder. The moment it melts from a dull solid into a shiny liquid ball, stop.
5.	Mark this position on your station's dial. This is your baseline solder melting point (approx. $220^\\circ\\text{C}$ for lead-free). The target reflow temperature will be ~20-25% higher on the dial than this mark.
Step 3: Creating the Flux (The Cold Mix Method)
This method avoids the dangerous heating of flammable alcohol.
1.	At room temperature, crush a small amount of solid rosin into a fine powder and place it in the metal bottle cap.
2.	Add a few drops of your solvent (alcohol).
3.	Stir with a toothpick until the rosin dissolves into a thin, syrup-like liquid. You have now safely created usable liquid flux.
Step 4: Flux Application & Pre-Bake (The Clothes Iron Method)
This is the key step to safely use low-purity alcohol by removing the water content before the reflow.
1.	Apply Flux: Use your toothpick or needle to apply a thin bead of the homemade liquid flux into the seam around all four edges of the GPU die.
2.	Set Up Iron: Securely position the clothes iron upside-down so it is stable and level. Set the temperature dial to its LOWEST setting (e.g., for silk/delicates).
3.	Perform Pre-Bake: Carefully place the GPU circuit board directly onto the warm surface of the iron.
4.	Let the board heat gently for 5-10 minutes. This low, controlled heat will safely evaporate the alcohol and water, leaving a non-conductive film of solid rosin precisely where it's needed.
5.	Unplug the iron and allow the board to cool completely to room temperature before moving to the next step.
Step 5: The Final Reflow
1.	Place the cooled, pre-baked circuit board on a stable, elevated, heat-proof surface.
2.	Set your hot air station to the target reflow temperature determined in Step 2.
3.	Begin by pre-heating the entire board from a distance of ~20cm for 2-3 minutes to prevent thermal shock.
4.	Focus the heat on the GPU die. Hold the nozzle ~2-3cm away and use constant, slow, circular motions for 3-5 minutes. DO NOT hold the heat still in one spot.
5.	The flux should bubble and smoke. A slight "shimmer" of the GPU die may indicate a successful reflow. Do not touch or nudge the chip to check.
Step 6: The Cool Down & Reassembly
This step is as critical as the heating.
1.	Turn off the hot air station.
2.	DO NOT MOVE, TOUCH, OR FORCE-COOL THE BOARD.
3.	Allow the board to cool down naturally to room temperature for at least 30-45 minutes. Any thermal shock at this stage will crack the new solder joints.
4.	Once completely cool, clean any excess flux residue from around the chip using your solvent.
5.	Apply fresh thermal paste, re-install thermal pads, and reassemble the entire graphics card.
6.	Install in a test system and check for functionality.
________________________________________
Expected Outcome
Success is not guaranteed. This is a last-ditch effort to revive hardware that is otherwise electronic waste. If the repair works, consider slightly underclocking the card to reduce thermal stress and prolong its new lease on life. If it fails, the underlying chip or solder pads were likely beyond a simple reflow repair.
________________________________________
Contributing
Feel free to fork this repository, add translations, or share your results (both successful and unsuccessful) via the Issues tab. Real-world data helps everyone.
________________________________________
License
This guide is released under the MIT License. You are free to share, adapt, and use it for any purpose.
________________________________________
Acknowledgments
This method was developed by Szili in Salonta, Romania, on August 5, 2025, through a collaborative, safety-focused process.

# The-Szili-Zero-Budget-GPU-Reflow-Guide
[DIY Method] [High-Risk Procedure] [Zero-Budget
