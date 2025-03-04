# MULTIVAC Documentation and References
This page serves as an index of system design, theory, and walk through documentation for Gallup’s Meta-model Unification Learned Through Inquiry Vectorization and Automated Comprehension (MULTIVAC). DARPA’s Information Innovation Office’s Automating Scientific Knowledge Extraction (ASKE) program seeks to develop approaches to make it easier for scientists to build, maintain and reason over rich models of complex systems — which could include physical, biological, social, engineered or hybrid systems. MULTIVAC supports these goals by developing a system that absorbs scientific knowledge — in the form of facts, relationships, models and equations — from a particular domain corpus into a Markov Logic Network (MLN) ontology and learns to query that ontology in order to accelerate scientific exploration within the target domain. 

## Phase I Development - System Overview
### Data Acquisition and Parsing
- <a href='https://github.com/GallupGovt/multivac/tree/master/src/data'>Introduction</a> and overview of initial data acquisition from online repositories and preprocessing steps. 
### Markov Logic Network Induction
- <a href='https://github.com/GallupGovt/multivac/tree/master/pymln'>Construction</a> of the knowledge graph representation in the form of a Markov Logic Network.
### System Walk-Through (Jupyter Notebook)
- <a href='https://github.com/GallupGovt/multivac/tree/master/precooked_replication.ipynb'>Piece-by-Piece Execution</a>
### Query Mapping
- <a href='https://github.com/GallupGovt/multivac/tree/master/prepared_output.ipynb'>Query Mapping Execution</a>
<br>

## Phase II Development
- MULTIVAC in the <a href='https://github.com/GallupGovt/multivac/blob/master/doc/aske_context.md'>ASKE Context</a>
### Phase I Lessons Learned
- <a href='https://github.com/GallupGovt/multivac/blob/master/doc/lessons_learned.md'>Review</a> of lessons learned from implementing Phase I systems.
### Machine Generation of Queries
- <a href='https://github.com/GallupGovt/multivac/tree/master/prepared_output.ipynb#gan'>Next Steps</a> with Generative Adversarial Networks

## ASKE Community
- Other ASKE <a href='https://github.com/DARPA-ASKE/info-and-links'>repositories</a>
- ASKE official <a href='https://www.darpa.mil/program/automating-scientific-knowledge-extraction'>homepage</a>

## Related Research and Resources
- GANs for Text Generation: <a href='https://paperswithcode.com/search?q=gan+text'>paperswithcode.com</a>
- Markov Logic Networks <a href='https://paperswithcode.com/search?q=markov+logic+network'>paperswithcode.com</a>


For more information please contact Principal Investigator, Benjamin Ryan (ben_ryan@gallup.com).

---
## Acknowledgements
This work is supported by the Defense Advanced Research Projects Agency (DARPA) under Agreement No. HR00111990008.

