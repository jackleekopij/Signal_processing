# Signal_processing


## Uncertainty quantification
Forms of uncertainty:

Epistemic uncertainty - translates to 'knowledge' in Greek, is the uncertainty derived from lack of knowledge of information which can be reduced with further data.
Aleatoric uncertainty - comes from the word "alea" which means "the roll of the dice" and is defined as internal, unexplainable randomness


## Fourier transform
Heat equation https://tutorial.math.lamar.edu/classes/de/theheatequation.aspx

## Kernel smoothing
  Bibliography: 
  
    https://homepages.inf.ed.ac.uk/rbf/HIPR2/gsmooth.htm
    
    https://pdfs.semanticscholar.org/ad19/0bc250bb16202a032a5a2ba50fd1085c3c79.pdf
    
    https://stackoverflow.com/questions/28754252/smoothing-a-noisy-image-then-sharpening
    
 
    
## Gaussian Processes:
Carl Rasmussen GPs
http://gaussianprocess.org/gpml/chapters/RW.pdf
"There are several ways to interpret Gaussian Process regression models:
1. Weight space
2. Function space - a probability density directly over the function output space.
  
Predictive distribution, P(y*|x*, y, x) = \int P(y*|f,x*) P(f|y, x) df)

A Gaussian Process (prior) is a prior distribution on some unknown *function*, \mu(x). 

Fantastic introduction resource video on GPs:
https://www.youtube.com/watch?v=UBDgSHPxVME

Gaussian Processes have propertry where by as you move away from data uncertainty decreases. Such increase in uncertainty propagates both along the x-axis and the y-axis.
  Bibliography: 
  
    http://cs229.stanford.edu/section/cs229-gaussian_processes.pdf

## Bayesian optimisation:
Bayesian optimisation was pivotal in the implementation of AlphaGo achieving its success ([paper on Bayesian optimisation in AlphaGo](https://arxiv.org/pdf/1812.06855.pdf)).

## Hidden Markov Models: 

## Kalman filters
   [Kalman filter demystified: from intuition to probabilistic graphical model to real case in financial markets](https://arxiv.org/pdf/1811.11618.pdf)
   [Kalman filter video](https://www.youtube.com/watch?v=CaCcOwJPytQ)

### ML and Physical World - Neil Lawrence
1.	Laplace's demon, full determinism in physical world is not possible.
2.	Machine learning, data + model = prediction. Too much of ML has had pure focus on prediction more work needs to be causal ML to endeavour to understand system = more transferability.
3.	Analogy  of Stochastic Vs Determinism, likened to hurricane Vs Navier-Stokes equation. Be mindful of your model’s granularity.
4.	Physical Vs Simulation Vs emulations. UK's BOM uses too much low level physics, not enough high level emulations /ML.
5.	OR and Machine Learning hasn't come together as of yet. There’s a lot of low hanging fruit to be had at the intersection of these fields.
6.	Separation of concern architecture – again has focused on prediction at the cost of explanability, needs to incorporate causal lens.

Video: https://youtu.be/FuJgGeKMIJM

Lecture series: https://mlatcl.github.io/mlphysical/
