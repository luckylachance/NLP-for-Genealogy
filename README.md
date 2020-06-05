Lucky LaChance
Entity Relationship Extraction for Genealogical Research 

Executive Summary 

Finished File:  Geneaology from Historical Text is the final Capstone Project work

All other notebooks were exploratory in nature.



Humans routinely read and digest volumes of text based documents to extrapolate potential relationships between entities in time in space.  Human discernment is highly accurate, but exceedingly slow when compared to the processing power of computers.  With the advent of two technologies Natural Language Processing (NLP) and network graphing applications, humans can utilize NLP to screen and score these relationships from large volumes of free text and graph it.  

Motivation

I am both a genealogist and a budding data scientist.  Given that our last project at NSS was Natural Language Processing I felt challenged to explore the potential application in a deeper and more meaningful manner to help me catchup on the volumes of data I have that I must manually process (Read and classify).  
Data Question

How can I leverage NLP to effectively “map” and “score” relationships from large volumes of text ?

Preliminary research findings

 Identifying entities and their respective relationships isn’t difficult for humans. However, reading text files and extrapolating a manual graph for large volumes of text is not scalable and it’s very slow. Nobody is going to go through thousands of documents (think resumes, family histories, official documents), and extract the unlimited relationships that exist in these documents.
 
Relationship extraction may seem easy enough using a naïve approach like finding phrases like “married to”, “XXX’s spouse” but human language has countless ways to indicate the relationship in its written and spoken form.  NLP processing will require three stages of development before a graph can even be applied to the data:

Results:  I was successful in training a small corpus to recognize simlar sentnecs using regressiona analysis.  The next stap is to have the machin categorize the sentences it recommended.  Finally I want to use those relationships as tuples where Proper Noun verb Proper noun would be marked and imported to a graphong database like Neo4J