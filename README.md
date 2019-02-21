# hcls-drug-drug-interaction
W3C HCLS Minimum Information Model for Potential Drug-Drug Interaction Information

A repository to store artifacts created for the W3C Semantic Web in Health Care and Life Sciences Community Group Note
titled "A Minimum Representation of Potential Drug-Drug Interaction Knowledge and Evidence - Technical and User-centered Foundation." 

[The current draft of the note](https://dbmi-icode-01.dbmi.pitt.edu/dikb-evidence/hcls-drug-drug-interaction/index.html) is viewable online. 

See also the related [Minimum PDDI Information Ontology](https://github.com/MPIO-Developers/MPIO/) project and the [HL7 CDS and Pharmacy WG sponsored implementation guide for potential drug-drug interaction clinical decision support](https://github.com/HL7/PDDI-CDS).

## Folder layout:

- User-centered-definitions - documents that provide the final user-centered definitions for the minimum information model along with examples and references. See also the related [Minimum PDDI Information Ontology](https://github.com/MPIO-Developers/MPIO/) project.

- Decision-trees - documents that hold the exemplar potential drug-drug interactions PDDI used to build and validate the minimum information model. There is a single document for each PDDI. Each document provides a description of the PDDI, a decision trees for the clinical context, and references 

- Med-Rec-Use-Case - documents describing the medication reconciliation use case used to validate the minimum informaton model

- Stakeholder-descriptions - documents that define the intended users of the minimum information model and provide specific user stories for each intended user

- Presentations - presentations related to the minimum information model

- src - Source code used to demonstrate the minimum information model

## Overview:

Objectives: Develop a minimal information model for drug interaction
evidence and knowledge as part of an Health Information Technology
standard like HL7. These include the following activities:

- Clarify definitions for the minimum information items recommended by the relevant stakeholders. See also the related [Minimum PDDI Information Ontology](https://github.com/MPIO-Developers/MPIO/) project.

- Propose additional attributes that further specify information relevant for each of the seven information items (e.g., "what is the basic information that should be provided when discussing clinical consequences, frequency of harm and exposures, etc.)

- Create deliverables using an interesting and non-trivial set of potential drug-drug interactions:

   -- Data Model: A data model (schema) for potential drug interaction knowledge and evidence

   -- Vocabulary: A precise vocabulary describing/defining the data model

   -- Serializations: one or more serialization formats of the abstract
   data model, such as XML, JSON/JSON-LD, Structured Product Labeling (HL7 CDA),
   

- Demonstration of how the minimum information model can support medication reconciliation 

- Create a foundation for further collaborative work by disseminating results through an interest group note, a website, and an online discussion forum

## Possible workflow and application models for the PDDI minimal information model:

![alt text](https://github.com/W3C-HCLS/w3c-ddi/raw/master/Presentations/images/info-model-value-proposition.png "Possible workflow and application models for the PDDI minimal information model.")

## Contributors
- [rkboyce](https://github.com/rkboyce)
- [ericprud](https://github.com/ericprud)
