# Covid Graph CVD and Age Association

Exploration of Covid Graph with CVD and Age association

**Title**: A study of Covid-19 KG for Different Age group and CVD cases

<img src="https://covidgraph.org/img/content-img/data_model_with_logos_and_numbers.png" width="700" height="350"></img>)

                                       Image Courtesy: covidgraph.org 


**Description**: Covid-19 is caused by a coronavirus called SARS-CoV-2 and often presents with symptoms of high fever, cough and shortness of breath. In severe cases, Covid-19 may lead to acute respiratory distress syndrome (ARDS) and multiple organ dysfunction and eventually to death. It is clear that the severity and mortality of Covid-19  is much higher than any other known coronaviruses. New data from Covid-19 cases have indicated that the severity and mortality of this disease are significantly higher in elderly patients and patients with a history of CVD. Applying a Text Mining approach, the students will explore the role of risk factors such as ageing and several cardiovascular diseases (e.g., coronary artery disease) on the severity of Covid-19, and unravel possible underlying mechanisms.

### Participants
- ***John Fu***
- Maya Gupta
- Ethan Ji

**Leaders/instructors**: 
Dr. Dibakar Sigdel & Dr. David Liem (Mr. Vincent Kyi for technical support)


**Project walk-through**:
Identification of documents in the intersection with CVD cases, Covid 19 and Age Group (defined by MeSH).
Analysis of outcomes from cypher queries in graph databases for different age groups linking CVD cases and Covid 19.
Prepare a score based clustering approach for Age Group to CVD complications and explore underlying molecular mechanisms. 
Organize codes and prepare project documentation sites at PingLab Intern GitHub account.
Final Presentation at lab meeting.

**Education goals**: Students will learn how to apply innovative tools in text mining and knowledge graphs (e.gNeo4J and Spark) for data exploration and for the development of search algorithms with specific tasks in biomedical scenarios. 

**Scientific goals**:  Students will learn how to hypothesize meaningful biomedical questions from available tools and databases in CVD and Covid-19. (e.g., Which age groups and pre-existing CVD significantly increase the risk of mortality in Covid-19, and what are the underlying mechanisms?) The search results can be further explored to investigate the underlying age based mechanism.


### Preparing Foundation
- Create an account at NLM/UMLS account
- Get Familiar with the following:
    - [MeSH tree](https://meshb.nlm.nih.gov/treeView): Madical Subject Headings
    - [ICD codes](https://icd.who.int/browse11/l-m/en): International Classification of Disease
    - [Uniprot](https://www.uniprot.org): Database of proteins organized with Protein ID, synonyms, Abbr, associated Genes and biomolecules
    - [Reactome](https://reactome.org) : Database of Pathways and associated documents in Graph structure
    - [Drugbank](https://www.drugbank.ca) : Database of Drugs and associated documents
- Install Python([Anaconda](https://www.anaconda.com/products/individual))
- Install [Neo4J](https://neo4j.com/) and take available tutorials
- Get Familiar with [NLTK](https://www.nltk.org/) NLP package in Python
- Get introductory idea of Machine Learning from [Scikit](https://scikit-learn.org/stable) Learn and [Tensorflow](https://www.tensorflow.org/) (Specially, LSTM)

### Project Detail
- **Step -1**: Prepare required Covid entities (e.g, MeSH Tree (Age), ICD Tree (Age), Proteins, Genes, RNASeq, Drugs)
- **Step -2**: Explore Covidgraph with different Age cases with CVD entities
- **Step -3**: Prepare a sypher queries to search over the documents
- **Step -4**: Create a Graph association Matrix and artifacts
- **Step -5**: Design Machine Learning models (e.g., Clustering, PCA, tSNE)
- **Step -6**: Analyse the result
- **Step -7**: Present the result
- **Step -8**: Organize the documentation with Mkdocs


### Reference
- Data Source: (www.covidgraph.org) 

