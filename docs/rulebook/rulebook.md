# AIRM Rulebook

Edition 1.1.0 FEBRUARY 2026

The AIRM Rulebook provides principles, rules and recommendation in order to facilitate the development and maintenance of the AIRM. 
The principles, rules and recommendations are intended to be used for modelling, consolidation, validation and verification, and quality check purposes.

## Introduction

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

#### Rule template

| AIRM_Rule number | 
| :- |
| <mark style="background-color:lightblue">Rule statement</mark> |

#### Recommendation template

| AIRM_Recommendation number |
| :- |
| <mark style="background-color:yellow">Recommendation statement</mark> |

#### Principle template

| AIRM_Principle number |
| :- |
| <mark style="background-color:lightgrey">Principle statement</mark> |


### Last Version
When the phrase “latest version” is used it always means at the time of publication of the AIRM Rulebook for this version of the AIRM.



## AIRM Modelling Environment

| AIRM_Rule 1| 
| :- | 
| <mark style="background-color:lightblue">The AIRM models shall be represented using the UML v2.1.<br><br>Note: This means the AIRM models are based on the meta-model that is defined by the OMG Superstructure document [4].</mark> |

| AIRM_Rule 12 | 
| :- | 
| <mark style="background-color:lightblue">The AIRM models shall be exclusively expressed using UML::Class Diagram and UML::Package Diagram principles, notations and conventions.</mark> 

| AIRM_Recommendation 7 |
| :- |
| <mark style="background-color:yellow">The AIRM models should be developed and maintained using Sparx Enterprise Architect.</mark> |

## Content of the AIRM Components

### AIRM Contextual Model

AIRM_Rule 104
The AIRM Contextual Model shall contain a representation of the external standards and specifications that are necessary for AIRM modelling work.

AIRM_Rule 64
When the UML construct available in the AIRM Contextual Model has no definition, the definition from the corresponding standard or specification shall apply.

Note: This rule is necessary as not all of the UML models imported into the AIRM Contextual Model contain the definitions from the corresponding standard or specification.

AIRM_Rule 128
The AIRM Standards Catalog shall list the standards which are acceptable sources for modelling the AIRM.

### AIRM Conceptual Model

AIRM_Rule 103
The AIRM Conceptual Model shall contain definitions of model elements that are part of an ATM operational language, satisfying operational requirements and concerns. The model elements are defined without the consideration of solution, system and implementation aspects.

It is recognised that one of the purposes of the AIRM Conceptual Model is to ensure that the operational language is fully understood and can be communicated to operational experts and modellers.

### AIRM Logical Model

AIRM_Rule 106
The AIRM Logical Model shall contain definitions of model elements that are exchanged by systems and services. The model elements are defined without the consideration of solution, system and implementation aspects.

AIRM_Rule 129
The definitions from the AIRM Conceptual Model shall be used as the baseline for the AIRM Logical Model definitions. If there is a conflict, the definitions in the AIRM Conceptual Model have precedence.

AIRM_Rule 107
The AIRM Logical Model’s Abstract package shall contain model elements that are general in nature and provide a higher level of abstraction needed to align and maintain consistency of concrete model elements.

AIRM_Rule 53
The AIRM Logical Model shall not contain message types.
Note: MessageTypes are used to bring implementation specific structure to the AIRM model elements. As such, they are outside of the scope of the AIRM Logical Model.

AIRM_Principle 4
The AIRM Common Subject contains definitions of information constructs that are assessed as reusable in relation to other operational entities.

AIRM_Recommendation 4
Entities that are defined in two or more subject should be relocated to the Common Subject.

AIRM_Recommendation 5
Entities that are considered as domain neutral (usable in the context of other industries such as automotive) should be relocated to the Common Subject.

Example: Address is a general information entity with wide cross-industry applicability.

## AIRM Meta-Model

AIRM_Rule 109
The AIRM UML Models shall conform to the AIRM meta-model contained in Appendix A.

AIRM_Rule 41
The AIRM models shall make use of the following UML model elements: class diagram, package diagram, package, class, attribute, role, dependency, association (including specialisation, aggregation and composition), association class and note. Other UML model elements, such as templates, shall not be used.

AIRM_Rule 81
The model elements in the AIRM Conceptual Model and AIRM Logical Model shall use one of the following stereotypes:

< < Subject > > . Represents a field of specific knowledge. These appear as packages in the AIRM.
< < Information_Message > > . ATM specific message type. This appears as a UML class in the AIRM.
< < Information_Entity > > . A definition (type) of an operational ATM item of interest that is subject to constraints. This appears as a UML class in the AIRM.
< < Data_Entity > > . A definition (type) of a data (ATM) item of interest that is implementation independent and is subject to constraints. This appears as a UML class in the AIRM.
< < Data_Object > > . A standardized or formalized collection of a Logical ModelEntity's or association’s Properties.
< < CodeList > > . CodeList is used to describe a flexible and open enumeration UML::Enumeration. This appears as a UML class in the AIRM.
< < DataType > > . DataType is the abstract class that represents the general notion of being a data type (i.e., a type whose instances are identified only by their value). This appears as a UML class in the AIRM.
< < Measure > > . A Measure is the result from performing the act or process of ascertaining the value of a characteristic of some entity. [ISO 19103]
< < UnitOfMeasure > > . A unit of measure is a quantity adopted as a standard of measurement for other quantities of the same kind. [ISO 19103] In the AIRM, this is modelled as a CodeList with a restricted meaning.
Note: The AIRM meta-model contains more model elements and stereotypes which are used, e.g., in the context of AIRM compliance.

Note: The rulebook consistently refers to AIRM meta-model elements. Reference to the UML specification are explicitly identified by the “UML::” package prefix.

## AIRM Model Elements

### General Rules

AIRM_Rule 2
The AIRM models shall not contain model elements with a purpose to support a specific implementation, algorithm, technology or solution.

Note: Adding such constructs to a model in general imposes constraints that may make a model unnecessarily dependent on implementation decisions. The AIRM models should be focused on describing information needs independent of implementation and technological decisions.

### AIRM Subjects

AIRM_Rule 10
Subjects shall provide a documented rationale explaining the boundaries of the subject.

Note: The rationale is intended to be used to assess, during consolidation, if an entity is a natural part of a subject.

AIRM_Rule 110
The content of an AIRM Subject shall be documented / illustrated by at least one UML class diagram that portrays those entities and their associations which are most essential to an understanding of the scope of the Subject.

AIRM_Rule 130
All entities and objects shall appear on at least one UML class diagram.

### Naming Rules

AIRM_Rule 13
Names of model elements shall only use characters that are in ASCII ranges 48-57 (numbers), 65-90 (capital letters) and 97-122 (small letters).

In addition, the following are characters are allowed in codelist values to separate words: 95 (underscore).

AIRM_Rule 111
The ASCII 45 (hyphen), 46 (point), 47 (forward slash) characters shall be allowed if the name of a model element appears below:

8.33kHz
ADS-B
ADS-C
FANS 1/A
Note: The list of exceptions is managed by the AIRM Change Control Board Support Office and takes into account the following:

The name contains a specific character
The name refers to a concept widely shared amongst aeronautical community
Keeping the name the way it is known enables an easier understanding of the model

AIRM_Rule 14
Name parts and words shall not begin with numbers (0-9) unless an adopted standard mandates such spelling.

AIRM_Rule 15
Verbs (if any) shall be in the present tense.

AIRM_Rule 16
Abbreviations and acronyms shall not be used in names of model elements except where they appear in the Abbreviations section of the AIRM Contextual Model.

AIRM_Rule 7
Names of model elements shall be in the English language following the terms as identified by ICAO or other standard present in the AIRM Standards Catalog. If no term can be identified, the latest version of the Oxford English Dictionary shall be used.

AIRM_Rule 18
Where conflicting spellings exist for the names of model elements, the spelling listed as the primary British spelling in the Oxford English Dictionary shall be used.

AIRM_Rule 8
All model element names shall be unique within enclosing namespace(s).

Example: All entities shall be uniquely named within an AIRM model.

Example: All properties shall be uniquely named within the enclosing entity.

Example: All values must be unique within the enclosing codelist.

AIRM_Rule 19
The name of a subject or other UML::Package shall be expressed using the UpperCamelCase principle.

AIRM_Rule 5
The name of an entity, object, codelist or datatype shall be expressed using the UpperCamelCase principle.

Note: This rule does not apply to imported standards in AIRM Contextual Model. These might deviate from this rule.

AIRM_Rule 6
The name of a property shall be expressed using the lowerCamelCase principle.

AIRM_Rule 68
The name of a role shall be a noun describing the role of the associated entity.

AIRM_Rule 43
The name of a data type shall end with “Type”.

Example: ValDistanceType

AIRM_Rule 42
The name of a codelist shall begin with “Code” and end with “Type”

Example: CodeAirspaceType

AIRM_Rule 30
The name of a value contained in a codelist shall be UPPER_CASE. Spaces shall not appear in the value and words shall be separated by the underscore character ‘_”.

Example: NO_RESTRICTION

Exception: This rule does not apply if the name of the value is a recognised term such as an abbreviation. In this case the name of the value should be represented as the recognised combination of UPPER and lower case characters.

AIRM_Rule 24
If given, the name of an association shall be expressed using lower case.

Example: contains

Example: expressed as.

AIRM_Rule 112
If given, the name of an association shall be represented as either a verb or a verb phrase.

Example: omit “is” when followed by verb-phrase; e.g., instead of “is enabled by” have only “enabled by”, i.e., skip the verb.

AIRM_Recommendation 20
In the AIRM Conceptual Model, the name of an association should, where possible, be based on verbs found in the definitions of the associated entities which relate the entities.

AIRM_Rule 131
In the AIRM Conceptual Model, associations which are merely possible/probable or imprecise shall be given a multiplicity rather than reflecting this status as part of the association name.

Example: An association which can be expressed using such words as “can have”, “may have” or “may be” shall have a multiplicity and the association shall not have the word in its name.

### Authorship

AIRM_Rule 66
The author of a model element shall be given in the "Author" property. The author shall be the person or project which created the model element.

### Entities

AIRM_Rule 21
Entities shall be stereotyped as << Data_Entity >> in the AIRM Logical Model and as << Information_Entity >> in the AIRM Conceptual Model.

AIRM_Rule 83
A model element with the stereotype << Data_Entity >> shall be a specialisation of the abstract Entity.

Note: Entity is obviously exempt from this rule.

Note: The specialisation can be via a more generalised entity e.g. TemporalEnabledEntity.

AIRM_Rule 80
Entities shall not inherit from model elements with the stereotype <<Data Type>>, <<CodeList>>, <<Measure>>, <<UnitOfMeasure>>, <<Subject>>, <<Information_Message>> or <<Data_Object>>.

AIRM_Rule 20
Model elements shall not be represented as ‘root’ or ‘leaf’.

Note: It is impossible, in the context of ATM, to know that the AIRM is complete.

Logical Model Objects
AIRM_Rule 113
A model element with the stereotype <<Data_Object>> shall be a specialisation of the abstract Object.

Note: Object is obviously exempt from this rule.

Note: The specialisation can be via a more generalised object.

### Properties

AIRM_Rule 44
All properties of an entity, object or datatype shall be given "public" access privileges/scope.

AIRM_Rule 46
In the AIRM Logical Model, attributes shall only be typed by datatypes.

Note: This means that they should not be typed by other entities or objects from the AIRM Logical Model.

Note: This rule does not apply in the AIRM Conceptual Model, so attributes can be typed by other entities. This can help the readability of the model.

AIRM_Rule 105
In the AIRM Logical Model, attributes shall be typed by:

Data types found within the ISO series of standards present in the AIRM Contextual Model; or
Data types found within the AIRM Logical Model’s DataTypes package; or
Codelists found within a Subject.
Examples:

ISO19103 contains primitives for Real, CharacterString, DateTime
ISO19107 contains geometry constructs
ISO19108 contains temporal constructs
ISO 639-2 contains language codes
Note: AIRM specific data types which specialise or otherwise reuse the ISO series can be found in the AIRM Logical Model’s DataTypes package.

Note: AIRM specific codelists can be found in dedicated packages within the relevant Subject.

AIRM_Rule 22
In the AIRM Logical Model, attributes shall, by default, be represented with multiplicity of [0..1] (zero to one). If an operational constraint has been identified then multiplicities shall be chosen to reflect such constraints.

Note: If no explicit attribute multiplicity is given, [0..1] multiplicity is implied.

Note: Further constraints on multiplicity may be added in "AIRM Derived" models.

AIRM_Rule 26
In the AIRM Logical Model, role names shall, by default, be represented with multiplicity [0..*] (zero to many). If an operational constraint has been identified then multiplicities shall be chosen to reflect such constraints.

Note: If no explicit role name multiplicity is given, [0..*] multiplicity is implied.

Note: Further constraints may be added in "AIRM Derived" models such as in Physical Data Models.

### Associations

AIRM_Rule 47
Datatypes shall not be used as an end-point in an UML::Association.

AIRM_Rule 45
Associations between entities shall be modelled using an UML::Association where navigability is unspecified.

AIRM_Rule 82
A model element with the stereotype <<Data_Object>> shall be made part of a <<Data_Entity>> or another <<Data_Object>> by means of a UML::Aggregation association.

AIRM_Rule 132
In the AIRM Conceptual Model every association (except specialisation/generalisation) shall have at least:

One association name with a labelled direction, or
One role name. The role names shall be added to the end of the association which has semantic significance (i.e. as the property of an entity). In the case of UML::Aggregation and UML::Composition the role name shall be added only at the “part” end of the association.

AIRM_Rule 23
In the AIRM Logical Model every association (except specialisation/generalisation) shall have at least one role name. The role names shall be added to the end of the association which has semantic significance (i.e. as the property of an entity). In the case of UML::Aggregation and UML::Composition the role name shall be added only at the “part” end of the association.

AIRM_Rule 114
Associations shall not be named in the AIRM Logical Model.

Note: Role names should be used in preference to relationship names. However, it is accepted that naming relationships can improve the readability of the AIRM Conceptual Model which is why this rule is limited in scope.

AIRM_Rule 124
In the AIRM Conceptual Model, any association name information supplied shall be considered informative, i.e. it will not have to be respected by derived models or by the AIRM Logical Model.

AIRM_Recommendation 22
UML::Specialisation should not be given an association name or a role name.

Rationale: UML::Specialisation has a pre-defined (semantic) meaning in UML as a special type of UML::Association.

AIRM_Recommendation 24
UML::Aggregation and UML::Composition should not be given an association name.

Rationale: UML::Aggregation has a pre-defined (semantic) meaning in UML as a special type of UML::Association.

AIRM_Recommendation 14
The use of association classes should be limited. However, they may be used to model attributes specific to one specific relationship, in situations where the association management business process is unspecified or out of scope of the model.

### Aggregation and composition

AIRM_Recommendation 11
The use of UML::Aggregation and UML::Composition between entities should be avoided where possible. They should be used only where there is a real-world constraint or they are otherwise allowed by a rule.

### Generalisation- specialisation

AIRM_Principle 6
An entity can be a specialisation of more than one general entity.

Rationale: Generalisation and specialisations commonly occur in models where concerns such as data structures, algorithms, technology, implementations etc. are not considered.

Note: The UML terms of generalisation and specialisation is preferred over ‘inheritance’ in order to be aligned with UML and NAF terminology. The term inheritance is often associated with technical /programming thinking and aspects.

AIRM_Rule 28
If a single-generalisation modelling construct can be found, with the same modelling effect as a multiple-generalisation modelling construct, then that construct shall be selected.

Rationale: Extensive use of multiple generalisation and specializations may create complex models that may be more difficult to extend over time.

AIRM_Recommendation 12
Deep generalisation and specialisation hierarchies should be avoided.

### Data Types

#### Codelists

AIRM_Rule 32
The issuing Authority of a codelist shall be identified and represented by an AIRM::TaggedValue ‘Authority’, attached to the codelist.

Note: More than one Authority may be attached to a codelist in case of joint governance.

Example: ICAO

## Definition Conventions

AIRM_Principle 30
A good definition:

Is a dictionary-style statement that describes the concept designated by a term.
Helps to establish the textual match between languages by stating the essential and delimiting characteristics of a concept (semantic feature).
Note: The quality of the definition is crucial, because without knowing what is meant exactly, we cannot communicate effectively, and without fully understanding the concept, we cannot establish relationships between concepts in our subject field.

AIRM_Rule 3
All model elements within the AIRM shall have a definition.

AIRM_Rule 34
If Sparx Enterprise Architect is used to maintain the AIRM (see Recommendation 7), a definition of an AIRM model element shall be stored in the Notes feature.

AIRM_Rule 35
The definition shall use the following principles for good definitions:

Predictability - the definition inserts the concept into a concept system.
Simplicity - the definition is concise, clear, and whenever possible no longer than one sentence; it includes only essential information.
Affirmativeness - the definition states what the concept is, rather than what it is not.
Non-circularity - the definition does not use words whose definitions refer back to the concept in question, nor does it begin with the term itself.
Absence of tautology - the definition is not a paraphrase of the term, but rather a description of the semantic features of the concept.
Part of speech - the definition begins with a word of the same part of speech as the term being defined.
Example: aerodrome: a defined area on land or water (including any buildings, installations and equipment) intended to be used either wholly or in part for the arrival, departure and surface movement of aircraft/helicopters.

Note: Stating a synonym is not a definition!

AIRM_Rule 37
The source of a model element definition shall be represented in a AIRM::TaggedValue, ‘Definition:Source’ that indicates its origin.

AIRM_Rule 63
The 'Definition:Source' for a model element shall be listed in the AIRM Standards Catalog.

AIRM_Recommendation 26
Extra details concerning the source of a model element definition should be captured in the AIRM::TaggedValue 'Defintion:SourceDetail'.

Example: This can be used to pinpoint the exact ICAO document used or a section within a larger document.

AIRM_Rule 60
The 'Definition:Adapted' AIRM::TaggedValue shall be completed in order to indicate the level of semantic correspondence with the source definition. The list of values is:

ExactCopy: Definition of source and target are exact copy of each other.
SyntacticallyEqual: Syntax corrections (grammar, spelling)
Rewritten: The definition has been rewritten for improved quality. The meaning is the same, i.e. the definition still describes exactly the same entity as the target definition.
Specialised: Source definition is a special case of the target definition.
Generalised: Source definition is a generalised case of the target definition.
AIRM_Rule 38
A definition shall not contain references to a name of the submitter, origin or external model or source.

AIRM_Rule 39
A definition shall not contain references to how it is used.

Example: “This is primarily used by x, y, and z” is not an allowed definition.

AIRM_Rule 40
Definitions shall contain a “straight definition”. That is, they should not start with “This class defines…” or “This property represents…”.

AIRM_Rule 61
The status of a model element definition shall be represented in an AIRM::TaggedValue 'Definition:Status'. It shall be one of the following:

Proposed: The definition has been created or reworked.
Under Review: The definition is under review by experts.
Approved: The definition has been approved.
Under Rework: The definition has been reviewed and/or approved but is subject to change.
AIRM_Rule 62
Any synonyms for a model element's name shall be represented as a comma separated list in an AIRM::TaggedValue 'Definition:Synonyms'.

AIRM_Rule 17
Any abbreviation or acronym for a model element's name shall be represented in an AIRM::TaggedValue 'Definition:Abbreviation'.

## Diagram Conventions

AIRM_Principle 31
In the AIRM Conceptual Model, UML is used to create two types of diagram:

Hierarchy diagrams which are used to express taxonomies using UML::Specialisations
Analysis diagrams which are used to give a narrative about the AIRM model elements contained on the diagram expressed as a (network) of, for example, UML::Associations, UML::Roles and Diagram::Notes.
AIRM_Rule 133
In the AIRM Conceptual Model, a diagram shall be either a “hierarchy” diagram or an “analysis” diagram.

AIRM_Rule 134
In the AIRM Conceptual Model, a diagram shall have a stereotype of <<Analysis>> or <<Hierarchy>> assigned.

AIRM_Rule 135
In the AIRM Conceptual Model, every <<Analysis>> diagram shall be documented by explaining the following:

Content: What is this diagram about? (mandatory)
(Maturity) Status - <free text> (mandatory)
AIRM_Recommendation 25
In the AIRM Conceptual Model, every <<Analysis>> diagram should be documented by explaining the following:

Assumptions (optional)
Additional comments (optional)
Link to Requirements (optional)
AIRM_Recommendation 23
In the AIRM Information Model all diagrams should be possible to read on an A4 format (either in landscape or portrait.)

## Intellectual Property Rights

AIRM_Rule 9
All parts of the AIRM shall have following the BSD-type licence attached:

Copyright (c) 2019, Members of the AIRM CCB

==========================================

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the disclaimer in the documentation and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

DISCLAIMER

THIS SPECIFICATION IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE

==========================================

Editorial note: this license is an instance of the BSD license template as provided by the Open Source Initiative: http://opensource.org/licenses/BSD-3-Clause

Details on the AIRM CCB and a list of its members is available on request from swim@eurocontrol.int.

## General Principles, Rules and Recommendations

Evolution
AIRM_Principle 22
Evolution refers to how model elements evolve over time (e.g. version, status, lifecycle, etc).

AIRM_Rule 65
The status of a model element shall be given in the "Status" property. The value shall be one of the following:

Proposed: The model element has been created but is not mature enough for use by others or for publication.
Implemented: The model element has been finalised and has been verified. It is mature enough for use by other parties involved in building the AIRM but is not ready for publication.
Published: The model element is implemented and has been included in an official AIRM release.
Validated: The model element has been published and validated.
Under Rework: The model element has been published/validated but is being reworked. (Note: it is still part of the AIRM in its latest released version.)
Deprecated: The model element is no longer fit for use and will deleted in the version stated in the AIRM::TaggedValue "Deprecated:TargetRelease".
Obsolete: The model element has been marked deprecated in the current release version and will be deleted in the next release.
AIRM_Rule 115
The allowed combination of model element status (AIRM_Rule 65) and definition status (AIRM_Rule 61) are:

If the status of a model element is "Proposed", its Definition:Status shall be "Proposed", "Under Review", "Approved", or "Under Rework".
If the status of a model element is "Implemented", its Definition:Status shall be "Under Review" or "Approved".
If the status of a model element is "Published", its Definition:Status shall be "Under Review " or "Approved".
If the status of a model element is "Validated", its Definition:Status shall be "Approved".
If the status of a model element is "Under Rework", its Definition:Status shall be "Proposed", 'Under Review", "Approved" or "Under Rework".

Deprecation

AIRM_Principle 8
Deprecation of a model element indicates that it is about to be deleted in a subsequent release.

AIRM_Recommendation 15
A model element that is marked as deprecated should not further be used and a warning or error should be emitted if it is actually used.

AIRM_Rule 50
A model element that is marked as deprecated shall contain the following AIRM::TaggedValues:

Deprecated:DecisionDate: (mandatory) date of deprecation decision
Deprecated:Rationale: (mandatory) short rational for the deprecation
Deprecated:TargetRelease: (optional) planned release when the deprecated element will be deleted
Deprecated:Replacement: (optional) reference to other elements that should or shall be used instead
AIRM_Rule 51
A model element shall be deleted from the model only after it has been marked as “Deprecated” in a previous release.

AIRM_Rule 52
A model element that is to be deprecated shall be listed in the AIRM Release Notes.

AIRM Internal Semantic Trace from Logical Model to Conceptual Model
AIRM_Rule 137
In the AIRM Logical Model, every entity shall have at least one semantic trace to at least one model element in the AIRM Conceptual Model.

Supplements

AIRM_Principle 36
An AIRM supplement is a package within the AIRM that elaborates the AIRM content for a specific community

AIRM_Rule 144
The supplements shall fit within the scope of the AIRM, meaning that it should be relevant to ATM.

AIRM_Rule 145
The supplement shall follow the same rules as other AIRM content.

Note: this means following naming conventions, stereotypes, completion of metadata about a model element, etc.

AIRM_Rule 146
The supplement shall follow the structure of the main AIRM.

Note: this means it may have a contextual, a conceptual and a logical model. Indeed, it must have at least one of these.

AIRM_Rule 147
The supplement shall not introduce new model types such as physical models.

AIRM_Rule 148
The supplement should not have dependencies on the content of other supplements.

Note: this is to ensure that the change management of one supplement does not affect another supplement. However, reuse of definitions across supplements is to be encouraged.

AIRM_Rule 149
The supplement shall not remove or otherwise restrict the content of the main AIRM.

Note: supplements are about elaborating the content of the main AIRM. The ability to restrict the AIRM is handled by the AIRM derivation rules and should be handled as a separate step in the development cycle.

AIRM_Rule 150
Supplements shall contain, where necessary:

additional subjects;
additional entities;
additional objects;
additional data types;
additional relationships;
additional properties;
additional local definitions.
AIRM_Rule 151
The model elements in the supplement shall have URNs.

AIRM_Principle 37
The relationship between two model elements is owned by the source. This applies to associations between model elements and to the properties of a model element that are typed by another model element. For example, if Class1 “has” Class2, the “has” association is owned by Class1; if Class 1 contains a property “name” that is typed as a CharacterString, the “name” property is owned by Class 1.

AIRM_Principle 38
The main AIRM content cannot “own” an association or property where the target exists in a supplement.

AIRM_Rule 152
When supplementing a model element from the main AIRM, the supplement shall use the same name as the model element that it is supplementing.

AIRM_Rule 153
When supplementing a model element from the main AIRM, the supplement shall use the same definition as the model element that it is supplementing.

AIRM_Rule 154
When adding properties to a model element from the main AIRM, the supplement shall use a specialization of the model element that it is supplementing.

AIRM_Rule 155
When adding relationships to a model element from the main AIRM, the supplement shall use a specialization of the model element that it is supplementing.

AIRM_Rule 156
The specialization association shall be stereotyped <<supplement>>.

Note: This makes the exact nature of the specialization clear.

AIRM_Rule 157
Additional local definitions shall be added to the note field, below the existing definition, separated by a <<supplement>> stereotype

Derivation
AIRM_Principle 23
Derivation refers to the way in which model elements can be restricted and subsetted by users of the AIRM. Adaptation is also related to compliance.

AIRM_Principle 10
An AIRM Derived Model is a model that uses the AIRM to define its semantics but serves a specific restricted purpose.

Examples:

A NSV-11b product shall be a derived model.
Existing models shall prove they are "derivable from" the AIRM as a key element in claiming compliance with the AIRM.
AIRM_Principle 11
AIRM Derivation Rules are the set of rules to apply in order to establish traceability of the semantics of a given model to the AIRM.

AIRM_Principle 12
Derivation of the AIRM works by restriction. Therefore:

Any additional model elements of an AIRM Derived Model, assumed to be within the scope of the AIRM, should be traced to a Change Request identifier in the semantic correspondence statement of the Information Definition.
Any additional model elements, assumed to be outside the scope of the AIRM, should be traced to the “Out-Of-Scope” construct in the semantic correspondence statement of the Information Definition.
AIRM_Rule 54
A derived model shall declare any deviation from the AIRM Rulebook.

Note: For example, the AIRM naming conventions may not be applicable to an already existing model. In that case, deviations from the AIRM Rulebook shall be documented and explained.

AIRM_Rule 55
The upper bound of the multiplicity specified in a derived model shall be lower or equal to the upper bound of the multiplicity and greater or equal to the lower bound of the multiplicity specified in the AIRM.

AIRM_Rule 56
The lower bound of the multiplicity specified in a derived model shall be greater or equal to the lower bound of the multiplicity and lower or equal to the upper bound of the multiplicity specified in the AIRM.

AIRM_Principle 13
A derived model may declare leaf nodes final.

AIRM_Principle 14
A derived model may describe physical implementations of generalisation.

AIRM_Principle 16
A derived model may describe physical implementations of generalisation.

AIRM_Principle 15
A derived model may add navigability to its relationships.

Note: This does not mean that the associations cannot be navigated in the other direction but the directionality is a hint that implementations should make the navigation in the primary direction convenient and efficient.

AIRM_Principle 17
Constraints and business rules present in the AIRM can be further restricted in a derived model. They cannot be extended.

Example: A business rule restricts the length of a CharacterString to 4 characters. It can be restricted to length [2] but cannot be extended to length [7].

AIRM_Principle 18
Further constraints (including patterns, maximum values) may be added to a derived model.

Example: The length of datatypes may be restricted. For example, in the AIRM CharacterStrings are not given a maximum length. They can be restricted e.g. to length [10].

AIRM_Principle 20
A derived model may convert an attribute to a role name or vice versa. This means:

A property modelled as an UML attribute in the AIRM may be converted into a property modelled as a role, with a complex “constructed” type.
A property modelled as a role name in the AIRM may be converted into an attribute (e.g. if multiplicity is restricted to 1..1).
AIRM_Rule 59
A derived model shall not use an AIRM term with a conflicting definition.

Note: If a derived model does not use the original AIRM definition, a reference to the AIRM definition needs to be provided.

AIRM_Principle 19
In a derived model, AIRM codelists:

May remain as codelists; or
May be converted to enumerations (which can be seen as a restricted codelist); or
May be converted to a series of classes.
AIRM Uniform Resource Name (URN)
AIRM_Principle 35
To facilitate the referencing of the AIRM, each AIRM model element has a globally unique name. This unique name is defined according to the Uniform Resource Name (URN) standard [6].

AIRM_Rule 76
The URN of an AIRM model element shall use the structure: <URN> ::= "urn:" <NID> ":" <NSS>

Example: A full URN to a property of an entity: urn:aero:airm:1.0.0:ConceptualModel:Subjects:AirTrafficOperations:AirportOperationsManagement:TaxiOut@EXOT

Note: An AIRM namespace identifier (NID) and namespace specific string (NSS) are defined in Rules 70-72 and 74, respectively.

AIRM_Rule 70
AIRM model elements shall use the namespace identifier (NID): NID = aero

AIRM_Rule 71
The namespace specific string (NSS) shall use the structure: NSS = <MODEL_NSS>:<ELEMENT_NSS>

AIRM_Rule 72
The Model Namespace Specific Strings (MODEL_NSS) shall use the structure: MODEL_NSS = <ISSUER>?':'<PRODUCT>':'<VERSION>

The following terms are used in <MODEL_NSS>

<ISSUER> defines the agency responsible for the AIRM version in question (where applicable). This item shall be a URI itself.
<PRODUCT> identifies the AIRM (or an AIRM Derived Model by the same issuer).
<VERSION> is the version number of the product in question. The syntax and semantics are issuer specific (e.g. may or may not include issuer specific branch information).
Note: The components of the MODEL_NSS are considered as case insensitive, e.g. AIRM and “airm” refer to the same product.

AIRM_Rule 74
The Element Namespace Specific Strings (ELEMENT_NSS) shall use the structure: ELEMENT_NSS = (<NAME_OF_PACKAGE>':')+(<NAME_OF_CLASS>(@<NAME_OF_PROPERTY)?)?

The following terms are used in <ELEMENT_NSS>

<NAME_OF_PACKAGE> is the recursive definition of the model element’s position within the AIRM UML Package structure
<NAME_OF_CLASS> is the name of the UML Class in question (where applicable)
<NAME_OF_PROPERTY> is the name of the UML property within the class (where applicable)
Note: The components of the ELEMENT_NSS are considered case sensitive.

AIRM_Rule 79
The ISSUER component of the MODEL_NSS shall be left empty.

AIRM_Rule 77
The PRODUCT component of the MODEL_NSS shall be: PRODUCT = AIRM.

AIRM_Rule 73
The URN of AIRM Contextual Model elements that already have a URN issued by their originator shall be respected. This means that these elements shall uniformly be referenced by the original URN and the AIRM shall not issue an additional URN for these elements.

AIRM_Recommendation 16
Models derived from the AIRM should reference MODEL_NSS to disambiguate their semantic binding to the AIRM.

AIRM_Rule 75
Published AIRM model element semantics shall be backward compatible.

That is, a given ELEMENT_NSS referring to an AIRM model element in development status “published”, “validated”, “under rework” or “deprecated” shall always refer to the same logical concept. Its semantics shall not depend on the context of a MODEL_NSS.



