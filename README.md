# Multilevel/multifidelity working group

List of key papers, in an approximate suggested reading order (within each category).

### Multilevel Monte Carlo
- [Multilevel Monte Carlo methods](https://people.maths.ox.ac.uk/gilesm/files/acta15.pdf) by Giles, 2015.

- [Multilevel Monte Carlo methods and applications to elliptic PDEs with random coefficients](http://people.maths.ox.ac.uk/~gilesm/files/cgst.pdf) by Cliffe, Giles, Scheichl and Teckentrup, 2011.


### Multifidelity
- [Optimal Model Management for Multifidelity Monte Carlo Estimation](http://epubs.siam.org/doi/pdf/10.1137/15M1046472) by Peherstorfer, Willcox, and Gunzburger, 2016.

We held a reading group on this paper. To start the discussion on compariing MLMC and MFMC with ML-emulation, we implemented MFMC with the surrogate being a GP emulator. You can see this in the notebook [here](https://github.com/rich-d-wilkinson/Multilevel/blob/master/Multi-fidelityGPonline.ipynb).


### Multilevel emulation

- [Predicting the output from a complex computer code when fast approximations are available](https://www.jstor.org/stable/2673557?seq=1#page_scan_tab_contents)
Kennedy, & O'Hagan, 2000.

- [Reified Bayesian modelling and inference for physical systems](http://www.sciencedirect.com/science/article/pii/S0378375808003303), Goldstein and Rougier, 2009.
We describe an approach, termed reified analysis, for linking the behaviour of mathematical models with inferences about the physical systems which the models represent. We describe the logical basis for the approach, based on coherent assessment of the  


- [Fast linked analyses for scenario‐based hierarchies](http://onlinelibrary.wiley.com/doi/10.1111/j.1467-9876.2012.01042.x/abstract)
Williamson, Goldstein, & Blaker, 2012.

- [Small sample Bayesian designs for complex high-dimensional models based on information gained using fast approximations](http://www.tandfonline.com/doi/abs/10.1198/TECH.2009.08015)
Cumming, & Goldstein, 2009.


- [On uncertainty quantification in hydrogeology and hydrogeophysics](https://www.sciencedirect.com/science/article/pii/S0309170817304608), Linde, Ginsbourger, Irving, Nobile, Doucet, 2017.


- [https://www.sciencedirect.com/science/article/pii/S0309170812003016](https://www.sciencedirect.com/science/article/pii/S0309170812003016), Ginsbourger, Rosspopoff, Pirot, Durrande, Renard, 2013.



### Multilevel Quasi Monte Carlo

- [Multilevel quasi-Monte Carlo path simulation](https://people.maths.ox.ac.uk/gilesm/files/radon.pdf) by Giles and Waterhouse, 2019;  including the greedy algorithm for choosing the optimal number of samples on each level that Rob mentioned in his informal lecture, which can also be applied for standard MLMC.

- [Application of quasi-Monte Carlo methods to elliptic PDEs with random diffusion coefficients: a survey of analysis and implementation]() by Kuo and Nuyens, 2016.

### Misc related work

- [Estimating orthant probabilities of high dimensional Gaussian vectors with an application to set estimation](http://www.tandfonline.com/doi/abs/10.1080/10618600.2017.1360781) Azzimonti and Ginsbourger, 2017.



### Other useful links
- [Rob's talk from UNQW01]{https://www.newton.ac.uk/files/seminar/20180112090010001-1161181.pdf) which includes further key references.

- [Rob's slides from his lecture notes on MLMC used in the informal talk in Week 2](http://www.maths.bath.ac.uk/~masrs/tcc_uqlect2.pdf). The rest of the lecture notes and an exercise sheet can be found [here](http://www.maths.bath.ac.uk/~masrs/compuq.html)

- [Mike Giles' community webpage](https://people.maths.ox.ac.uk/gilesm/mlmc_community.html) which contains almost all papers written on MLMC to date.
