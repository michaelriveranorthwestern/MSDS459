# Part 2: Instance Matching and Statistical Relational Learning

This section covers how to make sure different mentions in a knowledge graph refer to the same real-world thing. This is called instance matching (IM). For example, two papers may have slightly different citation formats but be the same. IM helps group them correctly. It’s hard for machines because language is fuzzy, and context matters. IM also takes a lot of computing power because it compares many pairs, so techniques like blocking are used to make it faster. The readings also explain statistical relational learning (SRL), which deals with uncertainty in KGs. It lets you write logic rules with probabilities to describe things like “spouses vote the same” or “friends support the same candidate.” SRL helps make smarter predictions using frameworks like Markov Logic Networks (MLNs) and Probabilistic Soft Logic (PSL). These tools are useful when the data is incomplete or noisy.

## Key Takeaways
1. IM helps clean up data by merging different names or formats that refer to the same thing.
2. SRL uses logic and probability to handle uncertainty in KGs.
3. Tools like MLNs and PSL support predictions and reasoning from messy or incomplete data.

## References
Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. *Knowledge Graphs: Fundamentals, Techniques, and Applications*. Cambridge, MA: MIT Press, 2021. Chapters 8–9, 175–238. ISBN-13: 978-0262045094.  
Getoor, Lise, and Ben Taskar. *Introduction to Statistical Relational Learning*. The MIT Press, 2007. https://www.cs.umd.edu/srl-book/.  
W3C. “OWL 2 Web Ontology Language Document Overview.” World Wide Web Consortium, 2012. https://www.w3.org/TR/owl2-overview/.

[Back to README](README.md)
