# Financial PDE Discovery using Machine Learning

This first ever attempt to research the ability to uncover financial PDEs using machine learning tools. 



Train a model to predict option premiums (price call) using a large range of diverse data points (this has been done before, Hutchinson et al, 1994). Here we want to include known PDEs, known quantities of interest from known PDEs (i.e BS, Heston), quantities of interest from known PDEs, as well as true measurement data as inputs, basically whatever we can get our hands on to minimise the prediction error. Options metrics - S&P 500 stock index options probably.

 

Make sure this model outperforms the Black Scholes model (it would as long as it has BS as input). Use this model to simulate more input-output relationships, probably using recurrent generative adversarial networks. Now you have a larger data set (as large as you want) to try to rediscover financial PDEs or find simpler solutions.

 

The assumption is that we can now simulate a more precise (trained on all data), but unknown PDE and can now approximate it by learning differential terms from option values, and naturally combine them in some sparse model.

 

We don't just want to functionally approximate Black-Scholes and friends (that has been done already). We want to find a way to get closer to the governing equations of the true system for that reason we need a bigger time series data sets (GAN) with more terms. The method we present should be able to select, from a large library, the correct linear, nonlinear, and spatial derivative terms, allowing us to identify the PDE from data.

 

So in four steps, train model from all available data, create larger data set, sufficient in size to learn the best differential terms. And train a new model against this simulated dataset but now isolate quantities of interest from known Financial PDEs, to make sure that regulators would respect the outcome and finally combine them in some sparse model.


1. Can the Black-Scholes be rediscovered solely from time series data. 
1. There are various wasy to go about discovering dynamical systems using data-driven discovery.
    1. Equation Free Modelling
    1. Artificial Neural Networks
    1. Nonlinear Regressions
    1. Emperical Dynamical Modelling
    1. Normal Form Identification
    1. Nonlinear Laplacian Spectral Analysis
    1. Modelling Emergent Behaviour and
    1. Automated Inference of Dynamics.

  
  
  
  Acknowledgements:
  Samuel H. Rudy1,*, Steven L. Brunton2, Joshua L. Proctor3 and J. Nathan Kutz1
  Jens Berg, Kaj Nystrom
