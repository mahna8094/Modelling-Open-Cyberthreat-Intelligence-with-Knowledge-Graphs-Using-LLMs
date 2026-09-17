# Modelling-Open-Cyberthreat-Intelligence-with-Knowledge-Graphs-Using-LLMs

This project explores the use of Large Language Models (LLMS), Named Entity Recognition (NER), and Knowledge Graphs to transform unstructured Cyber Threat Intelligence (CTI) into structured applicable information.

The project was completed as part of the Bachelor of Computer Science at Edith Cowan University

## Project Objective

The objective of this projected is to develop a pipeline that is capable of extracting cybersecurity-related information from unstructured CTI documents and presenting the extracted information in a knowledge graph format.

The overall pipeline is made up of:
1. Cyber Threat Intelligence documents
2. Vulnerability and CVI identification
3. LLM-assisted CVE alignment
4. CTI processing
5. Named Entity Recognition
6. Entity and Relationship Extraction
7. Knowledge Graph Construction
8. Neo4j storage and querying

## Technologies
- Python
- Large Language Models (LLMs)
- CyNER 2.0
- DeBERTa
- Neo4j
- Cyber Threat Intelligence (CTI)
- Common Vulnerabilities and Exposures (CVE)
- Natural Language Processing

## Cybersecurity Entities 
The NER pipeline identifies Cyber Security entities including
- MALWARE
- VULNERABILITY
- SYSTEM
- THREAT_GROUP
- ATTACKER
- TARGET
- TOOL

## Project Pipeline
CTI Documents
/
CVE / Vulnerability Identification 
/
LLM-Assisted Processing
/
Named Entity Recognition
/
Entity Extraction
/
Relationship / Triple Generation
/
Neo4j Knowledge Graph


## My Contribution
I worked primarily on the Named Entity Recognition (NER) component of the project

My work Included:
- Investigating cybersecurity-focused NER approaches
- Working with CyNER 2.0 and the DeBERTa architecture
- Processing CTI text for cybersecurity entity extraction
- Evaluating entity recognition performance
- Converting extracted entities into structured representations
- Supporting the integration of extracted entities into the knowledge graph pipeline
