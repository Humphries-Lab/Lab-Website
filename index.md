---
---
Mark Humphries' lab at the [University of Nottingham School of Psychology](https://www.nottingham.ac.uk/psychology/welcome-to-psychology.aspx).

### We are a neural data lab.

We interrogate how the joint activity of many neurons encodes the past, present, and future in order to guide behaviour.  We develop analysis techniques for neural data, and use them to understand what the joint activity is encoding in recordings of hundreds or thousands of neurons, across different tasks, brain circuits, species, and phyla. And we develop theoretical and computational models for how this joint activity arises from neural circuits.
​<br>
Supported by the Medical Research Council, the BBSRC, and Innovate UK.

{% include section.html %}

## Highlights

{% capture text %}

### Strategy Tracker
Investigating how, when, and what subjects learn during decision-making tasks requires tracking their choice strategies on a trial-by-trial basis. In our new paper, we present a simple but effective probabilistic approach to tracking choice strategies at trial resolution. We show it identifies both successful learning and the exploratory strategies used in decision tasks performed by humans, non-human primates, rats, and synthetic agents. 
<br>
Strategy Tracker is available in [Python](https://github.com/Humphries-Lab/Bayesian_Strategy_Analysis_Python) and [MATLAB](https://github.com/Humphries-Lab/Bayesian_Strategy_Analysis_MATLAB).

{%
  include button.html
  link="https://doi.org/10.7554/eLife.86491"
  text="Read 'Tracking subjects' strategies in behavioural choice experiments at trial resolution' at eLife"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Paper_Figures/Maggi_eLife2024_figure5.jpg"
  link="https://doi.org/10.7554/eLife.86491"
  text=text
%}

{% capture text %}

### Computing the probability of connection between two neurons
A new Bayesian approach to computing the probability of connection between classes of neuron from paired recordings. Our algorithm outputs the probability of connection, the strength of evidence for it, and how it depends on distance between neurons. We use this approach to synthesise the most complete map of the striatal microcircuit currently available. 

{%
  include button.html
  link="https://doi.org/10.1523/JNEUROSCI.1487-21.2021"
  text="Read 'Bayesian Mapping of the Striatal Microcircuit Reveals Robust Asymmetries in the Probabilities and Distances of Connections' in the Journal of Neuroscience."
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="https://github.com/Humphries-Lab/Bayesian-map-of-striatum-circuitry"
  text="Get code"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/1__Neuron_with_a_patch_pipette.jpg"
  link="https://doi.org/10.1523/JNEUROSCI.1487-21.2021"
  text=text
%}

{% capture text %}
### Strong and weak principles of neural dimension reduction
When we apply dimension reduction to neural activity how should we interpret its output? Mark's paper argues for strong and weak principles of neural dimension reduction: The weak principle is that dimension reduction is a convenient tool for making sense of complex neural data; the strong principle is that dimension reduction shows us how neural circuits actually operate and compute. 
<br>
The strong and weak principles make different predictions about how we might expect the dimensionality of neural activity to scale with the number of neurons; these predictions were recently tested by [Manley et al (2024) Neuron](https://doi.org/10.1016/j.neuron.2024.02.011).


{%
  include button.html
  link="https://doi.org/10.51628/001c.24619"
  text="Read 'Strong and weak principles of neural dimension reduction' in Neurons, Behavior, Data analysis, and Theory."
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Paper_Figures/DimensionScalingSketch.png"
  link="https://doi.org/10.51628/001c.24619"
  text=text
%}

{% capture text %}
### Finding the dimensions of networks
Discovering low-dimensional structure in networks requires a suitable null model that defines the absence of meaningful structure. Here we introduce a spectral approach for detecting a network's low-dimensional structure, and the nodes that participate in it, using any null model. A powerful feature of our approach is that it automatically estimates the number of dimensions in the data network that depart from the null model. 
<br>
This paper was the result of whole-lab hackathons by Humphries, Caballero, Evans, Maggi & Singh. 

{%
  include button.html
  link="https://doi.org/10.1371/journal.pone.0254057"
  text="Read 'Spectral estimation for detecting low-dimensional structure in networks using arbitrary null models' in PLoS One"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="https://github.com/mdhumphries/NetworkNoiseRejection"
  text="Get code"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Paper_Figures/Fig8_of_Spectral_PLoSOne_paper.png"
  link="https://doi.org/10.1371/journal.pone.0254057"
  text=text
%}
