This model package provides NEURON codes for a multi-compartment model described 
in Zhou Y, Carney LH, Colburn HS (2005). The model simulates recent physiological 
results from the gerbil medial superior olive (MSO) that reveal that blocking 
glycinergic inhibition can shift the tuning for the interaural time difference (ITD)
of the cell (Brand et al., 2002). 

The model has a bipolar structure and incorporates two anatomic observations 
in the MSO: (1) the axon arises from the dendrite that receives ipsilateral 
inputs (Smith, 1995); and (2) inhibitory synapses are located primarily 
on the soma in adult animals. Specific Hodgkin-Huxley type of ionic channels 
are inserted into the axon to generate action potentials: fast sodium (Ina), 
low threshold potassium (ILTK), high threshold potassium (IHTK), 
hyperpolarization-active inward current (Ih), and the leakage channel (Il). 

The kinetics of all channels are based on the model of Type II cells in the 
anteroventral cochlear nuclei (Rothman and Manis, 2003c). The soma has only 
fast sodium channels. Ionic channels and the driving function for synaptic 
inputs are described in .mod files. The hoc files describe simulation procedures 
for modeling neural responses to ITDs (MSO_Zhouetal_2005.hoc) and a test kit 
for exploring input characteristics (test_inputs.hoc). Use NEURON command nrnivmodl 
to compile *.mod files, and then execute a *.hoc file. Please refer to NEURON 
documentations for further instructions on compiling mod files and 
launching hoc files on different operation systems.  

The file MSO_Zhouetal_2005.hoc produces the rate-ITD responses 
in Figures. 5, 6, 8, 11 in Zhou Y, Carney LH, Colburn HS (2005). 

Go to http://www.bu.edu/dbin/binaural/MSOdemo for more instructions on using the model. 

Any questions for implementing the model should be directed to Yi Zhou (yizhou@bu.edu). 
