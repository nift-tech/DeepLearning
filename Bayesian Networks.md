# What are Bayesian Networks?

Bayesian networks are graphical models that use Bayesian inference to represent variables and their conditional dependencies. The goal of Bayesian networks is to model likely causation (conditional dependence), by representing these conditional dependencies as connections between nodes in a directed acyclic graph (DAG). The graph’s nodes are just the model’s variables, whether observable quantities, latent variables, unknown parameters or subjective hypotheses.

Once graphed, researchers can then fairly simply calculate the probability tables for each node and find the joint probability effect of even independent, random variables on the model’s final outcome.



# How are Bayesian Networks Used?

For a simple example, a Bayesian network is setup to diagnose the likelihood of a possible disease, given symptoms and background information about the subject. Each of those variables would be presented as a node. The connections are the conditional dependencies, with the nodes that aren’t connected being variables that are conditionally independent of one another. Each node has its own probability function. The function’s input is the Bayes factor or other Bayesian statistic from the previously connected node, and the output is the probability or probability distribution of the variable the node represents.


###### (https://deepai.org/machine-learning-glossary-and-terms/bayesian-network)
