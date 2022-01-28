
# Table of Contents

<!-- - [What is the QHA program ?](#WhatisQHA)
- [What is the quasi-harmonic approximation ?](#Whatisquasi) -->
1. [What is the `QHA_3D` program ?](#example)
2. [How to cite](#example9)
3. [Contributing](#example9)

<a name="example"></a>
# What is the `QHA_3D` program ?

This is intended to be an alternative approach with respect to the [`QHA_2D` program](https://github.com/DavidCdeB/QHA_2D). 
The idea in the `QHA_3D` program is the following:
 If we represent the Gibbs free energy as a function of temperature and pressure for different thermodynamic polymorphs, we can obtain surface plots like the following:
 
 ![Data flow](https://github.com/DavidCdeB/QHA_3D/blob/master/Images_for_README_md/gibbs_free_energy_of_two_phase.jpg)
 
 where the crossing between two phases (alpha and beta in the figure) define a line, which is the phase boundary of these two phases in a 2D Temperature-Pressure diagram. 
In other words, by implementing the quasi-harmonic approximation we are predicting the **phase diagram** of a substance and the **thermodynamic stability** of different polymorphs, which leads to the exploration of **phase transitions** at a fnite temperature and pressure.

This program is currently under construction, and is being 
developed as part of my PhD project at [Prof. Nicholas Harrison's Computational Materials Science Group](http://www.imperial.ac.uk/computational-materials-science/people/), Imperial College London. The program is being used to investigate the phase diagram and phase transitions mechanisms on the calcium carbonate system.

 
<a name="example2"></a>
# How to cite

Please cite the following reference when using this code:

D. Carrasco-Busturia, "The temperature - pressure phase diagram of the calcite I - calcite II
phase transition: A first-principles investigation", Journal of Physics and Chemistry of Solids, vol. 154,
p. 110 045, 2021. DOI: https://doi.org/10.1016/j.jpcs.2021.110045.

Here the bibtex:

```
@article{CARRASCOBUSTURIA2021110045,                                                                        
title = {The temperature - pressure phase diagram of the calcite {I} - calcite {II} phase transition: A first-principles investigation},
journal = {Journal of Physics and Chemistry of Solids},
volume = {154},
pages = {110045},
year = {2021},
issn = {0022-3697},
doi = {https://doi.org/10.1016/j.jpcs.2021.110045},
url = {https://www.sciencedirect.com/science/article/pii/S0022369721001116},
author = {David Carrasco-Busturia}
}
```

<a name="example3"></a>
# Contributing

`QHA_3D` is free software released under the Gnu Public Licence version 3. 
All contributions to improve this code are more than welcome.

* Have a look at GitHub's ["How to contribute"](https://guides.github.com/activities/contributing-to-open-source/#contributing).

* If you are familiar with `git`: fork this repository and submit a pull request.

* If you are not familiar with `git`: 

    * If something should be improved, open an issue here on GitHub
    * If you think a new feature would be interesting, open an issue
    * If you need a particular feature for your project contact me directly.
  
