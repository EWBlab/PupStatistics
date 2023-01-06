# PupStatistics

The provided script is part of the data analysis for the manuscript "Electrostatic interactions guide substrate recognition of the prokaryotic ubiquitin-like protein ligase PafA".

It extracts data from three combined pupylome data sets from Festa et al. (2010), Poulsen et al. (2010) and Watrous et al. (2010) and compares these data points with a published protein abundance data set from Schubert et al. (2013). Classification of pupylation substrates was done manually based on their ability to be pupylated in vitro and/or known in vivo effects. Please see the method section of the manuscript for further information.

Running the script generates the figures 1b and 1c in the manuscript. 
The script is standalone and can be executed in a python environment with the numpy, scipy and matplotlib packages. The supplied .csv files are sufficient for running the code. 

Function of the script was tested in Jupyter Notebook v. 6.4.8 with Python 3.9.12. 



Data sets used from the following publications:

**Festa, R.A. et al.** Prokaryotic ubiquitin-like protein (Pup) proteome of Mycobacterium tuberculosis. *PLoS One 5*, e8589 (2010), https://doi.org/10.1371/journal.pone.0008589.

**Poulsen, C. et al.** Proteome-wide identification of mycobacterial pupylation targets. *Mol Syst Biol 6*, 386 (2010), https://doi.org/10.1038/msb.2010.39.

**Watrous, J. et al.** Expansion of the mycobacterial "PUPylome". *Mol Biosyst 6*, 376-85 (2010), https://doi.org/10.1039/B916104J.

**Schubert, O.T. et al.** The Mtb proteome library: a resource of assays to quantify the complete proteome of Mycobacterium tuberculosis. *Cell Host Microbe 13*, 602-612 (2013), https://doi.org/10.1016/j.chom.2013.04.008.
