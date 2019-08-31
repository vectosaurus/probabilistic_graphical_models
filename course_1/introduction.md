<h4>What is a model?</h4>
A model is a declarative representation of our understanding of the model. Since its a declarative representation, it means it stands on its own. Which implies that we can look at it and make sense of it regardless of the algorithm we choose to manifest this understanding.

<h4>Why is it important?</h4>
It is important because the same model can be used in context of different algorithms to answer different questions or perhaps to answer the same question but more efficiently or to make a different set of tradeoffs

<h4>Why are some models designed to be probabilistic?</h4>
<ul>
  <li>We have only partial knowledge of the world so it's hard to entirely sure</li>
  <li>There are observations that could be noisy and the general rule may be different from what we observe</li>
  <li>Not all phenomenon and complications of real world can be covered by a model</li>
  <li>There is inherent stochasticity in the world</li> 
</ul>

<h4> Why do wee need probability theory</h4>
<ul>
  <li>It provides us with a declarative representation with clear semantics</li> 
  <li>Provides us a tool box to develop powerful reasoning patterns for example conditioning on new forms of evidence</li> 
  <li>Allows to use established learning methods</li> 
</ul>

<h4>Complex Systems with probabilistic graphical models</h4>
Probabilistic graphical models are a synthesis of ideas from probability theory and ideas from computer science. The idea here is to use graphs from computer science and allow us to represent complicated systems that involve a large number of variables. 

In order to capture probability distributions over spaces involving such a large number of factors, we need to have probability distributions over what are called random variables. 

We need to think about the world as represention by a set of random variables, X1 up to Xn, each of which captures some facet of the world. So, one symptom that may be present or absent, or a test result that might have a continuous set of possible values or a pixel that might have one of several labels. So each of these is a random variable and our goal is to capture our uncertainty about the possible states of the world in terms of their probability distribution or what's called a joint distribution over the possible assignments to the set of random variables.

Graphical representation gives us an intuitive and compact data structure for capturing these high dimensional probability distributions. 

<h4>Probabilistic graphical models</h4>
Two main classes of PGMs
- Bayesian Networks (directed graphs)
- Markov Chains (undirected graphs)

<h4>Applications</h4>
To name a few applications
<ul>
  <li>Image Segmentations</li>
  <li>Medical Diagnosis</li>
  <li>Natural Language Processing</li>
  <li>Social Network Analysis</li>
</ul>
