# NetLogoAIA
A NetLogo model for the evolution of bacteria via drug resistance and combination therapy.


# Instructions
The model is ran by pressing the Setup button and then the Go button.


# Variable Descriptions
## Drug Variables
Drugs are enabled and disabled using the "drug1_enabled" and "drug2_enabled" switches.

Drugs are administered repeatedly on the ticks set by the "drug1_interval" and "drug2_interval" sliders.

The range of ticks that the drugs will be administered between are set using the "drug1_start_tick" and "drug1_end_tick" for drug1 and "drug1_start_tick" and "drug2_end_tick" for drug2.

The "stop_after_drug_course" switch will stop the model after the drugs are no longer administered if enabled.


## Disease Variables
The disease will have a chance to multiply repeatedly on the ticks set by "spread_rate" based on the "spread_chance."

The "drug1_base_resistance_min" and "drug1_base_resistance_max" control the range that the initial resistance to drug1 can be for the bacteria created during setup. "drug2_base_resistance_min" and "drug2_base_resistance_max" are used for drug2.

The "drug1_max_resistance_gain" and "drug2_max_resistance_gain" control the max amount of resistance the drugs can gain.

## Mutation Variables
The "mutation_chance" variable sets the chance that a bacteria can mutate a higher drug resistance. The amount of resistance it can gain from mutation is set using "range_of_mutation."

## Transformation Variables
Transformation can be enabled using the "transformation_enabled" switch. This gives the bacteria a chance to pass on drug resistance values to other bacteria with a lower resistance. The chance that this can happen is set using the "transformation_chance" variable.

