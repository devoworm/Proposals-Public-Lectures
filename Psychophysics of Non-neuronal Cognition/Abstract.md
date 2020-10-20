Non-neuronal cognition can be used to explain what appear to be neural behaviors in cellular-level systems. Examples include cellular decision-making (Perkins and Swain, 2009), information processing in regenerative processes (Baluska and Levin, 2016), and active perception among filopodia (Aspalter et.al, 2020). We characterize movement among colonies of the diatom genus _Bacillaria_ as a collective pattern generator (CoPG). The CoPG is similar to a central pattern generator (CPG) found in insect nervous systems. Collective pattern generators are produced by the stretching motions produced by the actin filaments of two neighboring cells. These synchronized movements propagate down the colony in an undulating, accordion-like manner. While we can utilize a neural model to characterize the behavior of this type of multicellular colony, psychophysical models are used to characterize pseudo-neuronal behaviors. 

We will use a database of images and movies of _Bacillaria_ movement (Alicea et.al, 2019) to capture measurements of colony movement and to train a generative model of movement dynamics. Using these data and a model, we can then establish an input/output curve that determines how much input results in a corresponding degree of output. From these input/output curves, we can derive just-noticeable differences and signal detection measurements. To model the movements that lead to statistical regularities, we propose a connectionist model in which nodes (neuronal units) can act as neuronal oscillators. Collectively, these nodes form the components of a CoPG. Meanwhile, connectivity is determined by the relative degree of synchronization between neighboring cells. 

## References
Alicea, B., Gordon, R., Harbich, T., Singh, U., Singh, A., and Varma, V. (2019). Towards a Digital Diatom: image processing and deep learning analysis of _Bacillaria paradoxa_ dynamic morphology. _bioRxiv_, doi:10.1101/2019.12.21.885897.

Aspalter, I.M. et.al (2020). Active Perception during Angiogenesis: filopodia speed up Notch selection of tip cells _in silico_ and _in vivo_. _bioRxiv_, doi:10.1101/2020.08.22.261263.

Baluska, F. and Levin, M. (2016). On Having No Head: cognition throughout Biological Systems. _Frontiers in Psychology_, 7, 902.

Perkins, T.J. and Swain, P.S. (2009). Strategies for cellular decision-making. _Molecular Systems Biology_, 5, 326. 

