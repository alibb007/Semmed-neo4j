# SeMMed - Neo4j Project

## Overview

This project focused on leveraging a graph-based database, Neo4j, to establish meaningful relationships within the [National Library of Medicine&#39;s Semantic Medline Database](https://lhncbc.nlm.nih.gov/ii/tools/SemRep_SemMedDB_SKR.html). which contains vast biomedical data.

As described on its official site, “The Semantic MEDLINE Database (SemMedDB) is a repository of semantic predications (subject-predicate-object triples) extracted by SemRep, a semantic interpreter of biomedical text. SemMedDB currently contains information about approximately 96.3 million predications from all PubMed citations (about 29.1 million citations) and forms the backbone of the Semantic MEDLINE application.”

The project aimed to demonstrate how a graph representation could transform the existing database into a more intuitive and functional knowledge resource by consolidating dispersed information into a unified structure.

The research and development team was comprised of 7 people and ended in December 2023:

    - Ali Barfi Bafghi
    - Aristotelis Dougales
    - Dhruthi Sridhar Murthy
    - Thu Thu Hlaing
    - Joshua Breininger
    - Candice Normalee Chambers
    - Malakai Spann

## Objective

The objective of this project was to investigate innovative methods for utilizing knowledge graphs, implemented through Neo4j, to organize and visually represent biomedical concepts and their intricate relationships as captured within the [Semantic MEDLINE Database (SemMedDB)](https://lhncbc.nlm.nih.gov/ii/tools/SemRep_SemMedDB_SKR.html).

SemMedDB serves as a repository of semantic predications, structured as subject-predicate-object triples, derived from biomedical literature using the SemRep semantic interpreter. With over 96.3 million predications extracted from approximately 29.1 million PubMed citations, SemMedDB offers a wealth of information that can empower research in medical and biological sciences. However, the database’s vast and decoupled structure can make meaningful insights challenging to uncover.

By leveraging Neo4j, a graph-based database platform, the project aimed to transform this vast biomedical data into an interconnected knowledge graph. This approach sought to provide a more intuitive and user-friendly way of navigating the relationships between biomedical entities such as diseases, drugs, genes, and other concepts. The graph representation allowed researchers to explore these entities and their interdependencies dynamically, enabling semantic visualization and paving the way for advanced data analysis powered by artificial intelligence.

The project included several critical components:

**1. Data Cleaning and Preprocessing:** Ensuring the data extracted from SemMedDB was structured and ready for integration into a graph-based system.

**2. AWS Integration:** Utilizing cloud-based storage and retrieval solutions to handle the extensive dataset efficiently.

**3. Graph Database Querying with Neo4j:** Designing and implementing queries to extract meaningful insights and relationships from the graph representation of the data.

**4. Performance Analysis:** Evaluating the efficiency and scalability of the system in handling large-scale biomedical data.

This effort demonstrated the potential of knowledge graphs to simplify complex datasets, provide clearer insights, and enhance the accessibility of biomedical knowledge for researchers and practitioners. Through this project, Neo4j proved to be a valuable tool for advancing the representation and usability of data within the biomedical field.
