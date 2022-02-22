# paris_ratchet
Calculating the strength of the Paris Agreement's ratcheting mechanism

The scripts and data contained here calculate the strength of the Paris Agreement's ratcheting mechanism, based on
how emissions trajectories have changed between COP21 at Paris and COP26 at Glasgow.

There are four main scripts in the analysis:
# 1. ratchet_calculation
This calculates the strength of the Paris ratcheting mechanism and creates stylised future GHG trajectories on this basis

# 2. silicone_disaggregation
This disaggregates these stylised GHG trajectories into underlying constituent gases, using Silicone

# 3. magicc_prep
This takes the disaggregated GHG trajectory from Silicone and merges it with an SSP1-26 emissions template, so that 
temperatures can be assessed via MAGICC. MAGICC is run from the server: https://live.magicc.org/

# 4. temperature_plot
This takes the outcomes of the MAGICC runs (all accessible at https://live.magicc.org/scenarios)
#and plots emissions and temperature outcomes
