# sugar-circuit

This repository contains code for running whole-brain simulations included in "Overlap and divergence of neural circuits mediating distinct behavioral responses to sugar" by Jacobs et al. The first version of the preprint is available at https://www.biorxiv.org/content/10.1101/2023.10.01.560401v1. A revised version with the simulation data is forthcoming.

All code for brain simulations was adapted from Philip Shiu (see https://github.com/philshiu/Drosophila_brain_model).

List of notebooks:
- Sugar_sim_activation_v1: performs activation of sugar GRNs and individual downstream neurons in sugar pathway
- Sugar_sim_activation_v2: performs activation of combinations of downstream sugar neurons
- Sugar_sim_activation_v3: performs activation of sugar pathway neurons along with P9
- Sugar_sim_silencing: performs activation of sugar GRNs with bilateral silencing of downstream sugar neurons, both individually and in combinations
- Sugar_bitter_activ_silencing: performs activation of sugar + bitter GRNs and also tests silencing of downstream bitter neurons
- Sugar_bitter_downstream_activation: performs activation of sugar GRNs along with downstream bitter neurons
