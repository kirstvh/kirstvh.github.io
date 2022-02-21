## BioCCP.jl

The first main project in my PhD was centered around the experimental design of screening experiments in biotechnology. 
In these experiments, a large number of variants of, for example, proteins, cells or organisms are generated to find an optimal phenotype. 
Here, we make the abstraction of considering each biosystem as a set of modules that is assembled into a design. 

<p align="center">
  <img src="images/abstraction.png" width="600"/>
</p>

For example, you can engineer a protein by varying and recombining existing protein domains. 
In chemical drugs, the type and position of atoms are varied to obtain a highly active configuration.
In plant breeding, one can create various growth phenotypes by performing gene knockouts combinatorially (multiplex CRISPR/Cas).

The large collection of variants we make in the wet lab by randomly varying and recombining modules is called a "library". 
An important question is how many variants should be present in a library or the "library size" to sufficiently cover the design space. 
In this context, we define "coverage" as the fraction of all available modules (or k-combination of modules) of interest that are present in a library.

We developed the Julia package [BioCCP.jl](https://github.com/kirstvh/BioCCP.jl) to help biotechnologists to determine an adeqate library size for their screening experiments!
A [Pluto notebook](https://kirstvh.github.io/BioCCP_Case_Study_html) with illustrations is available. Consult the accompanying paper [here](https://academic.oup.com/bioinformatics/article-abstract/38/4/1144/6425668?redirectedFrom=fulltext).

---------------------------
 
  [🔙 *Back to home page*](https://kirstvh.github.io)
