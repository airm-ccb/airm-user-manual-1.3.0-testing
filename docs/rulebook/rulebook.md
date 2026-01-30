# AIRM Rulebook

Edition 1.1.0 FEBRUARY 2026

The AIRM Rulebook provides principles, rules and recommendation in order to facilitate the development and maintenance of the AIRM. 
The principles, rules and recommendations are intended to be used for modelling, consolidation, validation and verification, and quality check purposes.

## 1. Introduction

### Purpose of the Document
The AIRM Rulebook provides principles, rules and recommendations for developing and maintaining the AIRM. This document is a normative rule book that 
focuses on providing definitions of vocabularies, principles, rules and recommendations.

The AIRM Rulebook is the basis for modelling the AIRM, assessing the quality of the AIRM (the AIRM UML models themselves). It is also used for internal
AIRM harmonisation, consolidation, review and change management activities.

### Intended readership
The AIRM Rulebook shall be used by contributors and submitters of model elements and change requests in order to increase the quality of their material.

It shall be used by participants in harmonisation and consolidation activities in their review, assessment and consolidation processes for checking quality, 
structure, semantics and other aspects. If a requested change or submission does not conform to a principle or rule then the breach may be reported back with 
the unique identity of the violated principle or rule.

### Terminology

| Term | Definition |
| :-   | :--------- |
| AIRM models | Shorthand to include the AIRM Conceptual Model, AIRM Logical Model and AIRM Contextual Model.|
| Conceptual Model | A conceptual model is a model of the information about the concepts in the universe of discourse, relevant to the architecture effort. | 
| Logical Model | The logical model is a specification of business/operational information requirements as a formal data structure, where relationships and classes (entities) are used to specify the logic which underpins the information. |
| Mapping | A set of traces that establishes a semantic correspondence between a concept in an information definition and AIRM concepts. |
| Information Definition under Assessment | A formal representation of information concepts or data concepts which is subject to AIRM Compliance demonstration. |
| Physical Data Model| The physical data model specifies how the logical data model will be instantiated in a particular product or service. It takes into account implementation restrictions and performance issues whilst still enforcing the constraints, relationships and typing of the logical model. |
| Trace | A directed link from a concept in an information definition to an AIRM concept. |

### Acronyms

| Term | Definition |
| :-   | :--------- |
| ADS-B | Automatic Dependant Surveillance - Broadcast |
| ADS-C | Automatic Dependant Surveillance - Contract |
| AIRM | ATM Information Reference Model |
| ASCII | American Standard Code for Information Interchange |
| ATM | Air Traffic Management |
| BSD | Berkeley Software Distribution |
| CONOPS | Concept of Operations |
| EATMA | European ATM Architecture |
| EBNF | Extended Backus–Naur Form |
| EXOT | Estimated Taxi-Out Time |
| FANS | Future Air Navigation System |
| GUID | Global Unique Identifier |
| ICAO | International Civil Aviation Organization |
| IEC | International Electrotechnical Commission |
| IETF | Internet Engineering Task Force |
| ISO | International Standards Organization |
| ISRM | Information Services Reference Model |
| MODAF| (UK) Ministry of Defence Architecture Framework |
| NAF | NATO Architecture Framework |
| NATO | North Atlantic Treaty Organisation |
| NOV | NAF Operations View |
| NSS | Namespace Specific String |
| NSV | NAF System View |
| OMG | Object Management Group |
| PDF | Portable Document Format |
| SES | Single European Sky | 
| SESAR | Single European Sky Air Traffic Management Research |
| SJU, SESARJU | SESAR Joint Undertaking | 
| STANAG | Standardization Agreement (NATO) |
| SWP | Sub Work Package | 
| WMO | World Meteorological Organization |
| XM | Exchange Model |


### Adoption
This section describes external documents and other artefacts that, through reference in this text, provide provisions that are considered as normative
of this document. For dated references, subsequent amendments to, or revisions of, any of these publications do not apply. For each publication a description 
how it has been adopted/used in this set of documents is also provided.

Note: If a reference is expressed with a date then only that version, of the reference, is valid since it is not possible to guarantee that newer versions, of referenced document, does not adversely impact this document.

#### Normative
The following publications, documents and artefacts are considered as normative:
- NATO Architecture Framework (NAF), v3, see [1]
- OMG Unified Modelling Language (UML), v2.1, see [2]
- OMG Semantics of Business Vocabulary and Business Rules (SBVR), v1.0 see [3]

#### Informative
The following publications, documents and artefacts are considered as informative:
- UPDM v1.0, see [5]

### Reading instructions
All parts of the document should be read.



## Using the AIRM Rulebook

### Interpretation
The following terms are used in this document:
- Rules. These are mandatory and shall be applied.
- Recommendations. These are not mandatory. However, compliance is strongly advised.
- Principles. These give general statements about the AIRM.

The following editorial practice has been followed in the writing of the AIRM Rulebook:
- For Rules the operative verb “shall” is used.
- For Recommendations the operative verb “should” is used.
- For Principles a more general wording is used.

The term “AIRM models” is often used as shorthand to include the:
- AIRM Conceptual Model;
- AIRM Logical Model; and
- AIRM Contextual Model.

### Numbering
The rules, recommendations and principles are presented in logical groupings. This means that as new items are added they are inserted 
in the relevant group. Therefore, the numbering of the items is not consecutive. Indeed, as items are removed, there may appear to be gaps in the numbering.

### Typographical conventions
The following layout is adopted to ease the use of the document.

### Rule template

| AIRM_Rule number | 
| :- |
| <mark style="background-color:lightblue">Rule statement</mark> |

### Recommendation template

| AIRM_Recommendation number |
| :- |
| <mark style="background-color:yellow">Recommendation statement</mark> |

### Principle template

| AIRM_Principle number |
| :- |
| <mark style="background-color:lightgrey">Principle statement</mark> |


### Last Version
When the phrase “latest version” is used it always means at the time of publication of the AIRM Rulebook for this version of the AIRM.

