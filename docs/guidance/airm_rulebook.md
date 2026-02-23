# AIRM Rulebook

Edition 1.1.0 FEBRUARY 2026

The `AIRM Rulebook` provides `principles`, `rules` and `recommendations` in order to facilitate the development and maintenance of the `AIRM`. 
The `principles`, `rules` and `recommendations` are intended to be used for modelling, consolidation, validation and verification, and quality check purposes.

## Introduction

### Purpose of the Document
The `AIRM Rulebook` provides `principles`, `rules` and `recommendations` for developing and maintaining the `AIRM`. This document is a **normative** rule book that 
focuses on providing definitions of vocabularies, principles, rules and recommendations.

The `AIRM Rulebook` is the basis for modelling the `AIRM`, assessing the quality of the `AIRM` (the AIRM UML models themselves). It is also used for internal
AIRM harmonisation, consolidation, review and change management activities.

### Intended readership
The `AIRM Rulebook` shall be used by contributors and submitters of model elements and change requests in order to increase the quality of their material.

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
- `Rules`. These are mandatory and shall be applied.
- `Recommendations`. These are not mandatory. However, compliance is strongly advised.
- `Principles`. These give general statements about the AIRM.

The following editorial practice has been followed in the writing of the AIRM Rulebook:
- For `Rules` the operative verb “shall” is used.
- For `Recommendations` the operative verb “should” is used.
- For `Principles` a more general wording is used.

The term `AIRM models` is often used as shorthand to include the:
- `AIRM Conceptual Model`;
- `AIRM Logical Model`; and
- `AIRM Contextual Model`.

### Numbering
The rules, recommendations and principles are presented in logical groupings. This means that as new items are added they are inserted 
in the relevant group. Therefore, the numbering of the items is not consecutive. Indeed, as items are removed, there may appear to be gaps in the numbering.

### Typographical conventions
The following layout is adopted to ease the use of the document.

#### Rule template

| <mark style="background-color:lightblue">AIRM_Rule</mark> *`number`* | 
| :- |
| Rule statement |

#### Recommendation template

| <mark style="background-color:yellow">AIRM_Recommendation</mark> *`number`* |
| :- |
| Recommendation statement |

#### Principle template

| <mark style="background-color:lightgrey">AIRM_Principle</mark> *`number`* |
| :- |
| Principle statement |


### Last Version
When the phrase `latest version` is used it always means at the time of publication of the `AIRM Rulebook` for this version of the `AIRM`.



## AIRM Modelling Environment

| <mark style="background-color:lightblue">AIRM_Rule</mark> `1` |
| :- |
| The `AIRM models` shall be represented using the UML v2.1.<br><br>*Note: This means the `AIRM models` are based on the meta-model that is defined by the OMG Superstructure document [4].* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `12` | 
| :- |
| The `AIRM models` shall be exclusively expressed using `UML::Class Diagram` and `UML::Package` Diagram principles, notations and conventions. | 

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `7` |
| :- |
| The `AIRM models` should be developed and maintained using Sparx Enterprise Architect. |

## Content of the AIRM Components

### AIRM Contextual Model

| <mark style="background-color:lightblue">AIRM_Rule</mark> `104` |
| :- |
| The `AIRM Contextual Model` shall contain a representation of the external standards and specifications that are necessary for AIRM modelling work. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `64` |
| :- |
| When the UML construct available in the `AIRM Contextual Model` has no definition, the definition from the corresponding standard or specification shall apply.<br><br>*Note: This rule is necessary as not all of the UML models imported into the `AIRM Contextual Model` contain the definitions from the corresponding standard or specification.* | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `128` |
| :- |
| The `AIRM Standards Catalog` shall list the standards which are acceptable sources for modelling the `AIRM`. | 

### AIRM Conceptual Model

| <mark style="background-color:lightblue">AIRM_Rule</mark> `103` | 
| :- |
| The `AIRM Conceptual Model` shall contain definitions of model elements that are part of an ATM operational language, satisfying operational requirements and concerns. The model elements are defined without the consideration of solution, system and implementation aspects.<br><br>It is recognised that one of the purposes of the `AIRM Conceptual Model` is to ensure that the operational language is fully understood and can be communicated to operational experts and modellers. | 

### AIRM Logical Model

| <mark style="background-color:lightblue">AIRM_Rule</mark> `106` |
| :- |
| The `AIRM Logical Model` shall contain definitions of model elements that are exchanged by systems and services. The model elements are defined without the consideration of solution, system and implementation aspects. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `129` | 
| :- |
| The definitions from the `AIRM Conceptual Model` shall be used as the baseline for the `AIRM Logical Model` definitions. If there is a conflict, the definitions in the `AIRM Conceptual Model` have precedence. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `107` | 
| :- |
| The `AIRM Logical Model`’s Abstract package shall contain model elements that are general in nature and provide a higher level of abstraction needed to align and maintain consistency of concrete model elements. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `53` |
| :- |
| The `AIRM Logical Model` shall not contain message types.<br><br>*Note: MessageTypes are used to bring implementation specific structure to the AIRM model elements. As such, they are outside of the scope of the `AIRM Logical Model`.* | 

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `4` | 
| :- |
| The AIRM Common Subject contains definitions of information constructs that are assessed as reusable in relation to other operational entities. | 

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `4` |
| :- |
| Entities that are defined in two or more subject should be relocated to the Common Subject. | 

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `5` |
| :- |
| Entities that are considered as domain neutral (usable in the context of other industries such as automotive) should be relocated to the Common Subject.<br><br>Example: Address is a general information entity with wide cross-industry applicability. |


## AIRM Meta-Model

| <mark style="background-color:lightblue">AIRM_Rule</mark> `109` |
| :- |
| The AIRM UML Models shall conform to the AIRM meta-model contained in Appendix A. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `41` |
| :- |
| The `AIRM models` shall make use of the following UML model elements: class diagram, package diagram, package, class, attribute, role, dependency, association (including specialisation, aggregation and composition), association class and note. Other UML model elements, such as templates, shall not be used. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `81` |
| :- |
| The model elements in the `AIRM Conceptual Model` and `AIRM Logical Model` shall use one of the following stereotypes:<br>- **`<<Subject>>`**. Represents a field of specific knowledge. These appear as packages in the AIRM.<br>- **`<<Information_Message>>`**. ATM specific message type. This appears as a UML class in the AIRM.<br>- **`<<Information_Entity>>`**. A definition (type) of an operational ATM item of interest that is subject to constraints. This appears as a UML class in the AIRM.<br>- **`<<Data_Entity>>`**. A definition (type) of a data (ATM) item of interest that is implementation independent and is subject to constraints. This appears as a UML class in the AIRM.<br>- **`<<Data_Object>>`**. A standardized or formalized collection of a Logical ModelEntity's or association’s Properties.<br>- **`<<CodeList>>`**. CodeList is used to describe a flexible and open enumeration UML::Enumeration. This appears as a UML class in the AIRM.<br>- **`<<DataType>>`**. DataType is the abstract class that represents the general notion of being a data type (i.e., a type whose instances are identified only by their value). This appears as a UML class in the AIRM.<br>- **`<<Measure>>`**. A Measure is the result from performing the act or process of ascertaining the value of a characteristic of some entity. [ISO 19103]<br>- **`<<UnitOfMeasure>>`**. A unit of measure is a quantity adopted as a standard of measurement for other quantities of the same kind. [ISO 19103] In the AIRM, this is modelled as a CodeList with a restricted meaning.<br><br>*Note: The AIRM meta-model contains more model elements and stereotypes which are used, e.g., in the context of AIRM compliance.*<br><br>*Note: The rulebook consistently refers to AIRM meta-model elements. Reference to the UML specification are explicitly identified by the “UML::” package prefix.* |

## AIRM Model Elements

### General Rules

| <mark style="background-color:lightblue">AIRM_Rule</mark> `2` | 
| :- |
| The `AIRM models` shall not contain model elements with a purpose to support a specific implementation, algorithm, technology or solution.<br><br>*Note: Adding such constructs to a model in general imposes constraints that may make a model unnecessarily dependent on implementation decisions. The AIRM models should be focused on describing information needs independent of implementation and technological decisions.* |

### AIRM Subjects

| <mark style="background-color:lightblue">AIRM_Rule</mark> `10` |
| :- |
| Subjects shall provide a documented rationale explaining the boundaries of the subject.<br><br>*Note: The rationale is intended to be used to assess, during consolidation, if an entity is a natural part of a subject.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `110` | 
| :- |
| The content of an AIRM Subject shall be documented / illustrated by at least one UML class diagram that portrays those entities and their associations which are most essential to an understanding of the scope of the Subject. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `130` |
| :- |
| All entities and objects shall appear on at least one UML class diagram. |

### Naming Rules

| <mark style="background-color:lightblue">AIRM_Rule</mark> `13` |
| :- |
| Names of model elements shall only use characters that are in ASCII ranges 48-57 (numbers), 65-90 (capital letters) and 97-122 (small letters).<br>In addition, the following are characters are allowed in codelist values to separate words: 95 (underscore). |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `111` |
| :- |
| The ASCII 45 (hyphen), 46 (point), 47 (forward slash) characters shall be allowed if the name of a model element appears below:<br>8.33kHz<br>ADS-B<br>ADS-C<br>FANS 1/A<br><br>*Note: The list of exceptions is managed by the AIRM Change Control Board Support Office and takes into account the following:* <br> *- The name contains a specific character* <br> *- The name refers to a concept widely shared amongst aeronautical community* <br>  *- Keeping the name the way it is known enables an easier understanding of the model* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `14` |
| :- |
| Name parts and words shall not begin with numbers (0-9) unless an adopted standard mandates such spelling. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `15` | 
| :- |
| Verbs (if any) shall be in the present tense. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `16` |
| :- |
| Abbreviations and acronyms shall not be used in names of model elements except where they appear in the Abbreviations section of the `AIRM Contextual Model`. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `7` |
| :- |
| Names of model elements shall be in the English language following the terms as identified by ICAO or other standard present in the AIRM Standards Catalog. If no term can be identified, the latest version of the Oxford English Dictionary shall be used. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `18` |
| :- |
| Where conflicting spellings exist for the names of model elements, the spelling listed as the primary British spelling in the Oxford English Dictionary shall be used. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `8` |
| :- |
| All model element names shall be unique within enclosing namespace(s).<br><br>Example: All entities shall be uniquely named within an AIRM model.<br><br>Example: All properties shall be uniquely named within the enclosing entity.<br><br>Example: All values must be unique within the enclosing codelist. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `19` |
| :- |
| The name of a subject or other `UML::Package` shall be expressed using the UpperCamelCase principle. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `5` |
| :- |
| The name of an entity, object, codelist or datatype shall be expressed using the UpperCamelCase principle.<br><br>*Note: This rule does not apply to imported standards in AIRM Contextual Model. These might deviate from this rule.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `6` |
| :- |
| The name of a property shall be expressed using the lowerCamelCase principle. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `68` |
| :- |
| The name of a role shall be a noun describing the role of the associated entity. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `43` |
| :- |
| The name of a data type shall end with `Type`. <br><br>Example: ValDistanceType |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `42` | 
| :- |
| The name of a codelist shall begin with `Code` and end with `Type`<br><br>Example: CodeAirspaceType |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `30` |
| :- |
| The name of a value contained in a codelist shall be UPPER_CASE. Spaces shall not appear in the value and words shall be separated by the underscore character `_`.<br><br>Example: NO_RESTRICTION<br><br>Exception: This rule does not apply if the name of the value is a recognised term such as an abbreviation. In this case the name of the value should be represented as the recognised combination of UPPER and lower case characters. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `24` |
| :- |
| If given, the name of an association shall be expressed using lower case.<br><br>Example: contains<br><br>Example: expressed as. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `112` |
| :- |
| If given, the name of an association shall be represented as either a verb or a verb phrase.<br><br>Example: omit “is” when followed by verb-phrase; e.g., instead of “is enabled by” have only “enabled by”, i.e., skip the verb. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `20` |
| :- |
| In the AIRM Conceptual Model, the name of an association should, where possible, be based on verbs found in the definitions of the associated entities which relate the entities. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `131` |
| :- |
| In the AIRM Conceptual Model, associations which are merely possible/probable or imprecise shall be given a multiplicity rather than reflecting this status as part of the association name.<br><br>Example: An association which can be expressed using such words as “can have”, “may have” or “may be” shall have a multiplicity and the association shall not have the word in its name. |

### Authorship

| <mark style="background-color:lightblue">AIRM_Rule</mark> `66` |
| :- |
| The author of a model element shall be given in the "Author" property. The author shall be the person or project which created the model element. |

### Entities

| <mark style="background-color:lightblue">AIRM_Rule</mark> `21` |
| :- |
| Entities shall be stereotyped as `<<Data_Entity>>` in the `AIRM Logical Model` and as `<<Information_Entity>>` in the AIRM Conceptual Model. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `83` |
| :- |
| A model element with the stereotype `<<Data_Entity>>` shall be a specialisation of the abstract Entity.<br><br>*Note: Entity is obviously exempt from this rule.* <br><br>*Note: The specialisation can be via a more generalised entity e.g. TemporalEnabledEntity.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `80` |
| :- |
| Entities shall not inherit from model elements with the stereotype `<<Data Type>>`, `<<CodeList>>`, `<<Measure>>`, `<<UnitOfMeasure>>`, `<<Subject>>`, `<<Information_Message>>` or `<<Data_Object>>`. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `20` |
| :- |
| Model elements shall not be represented as ‘root’ or ‘leaf’.<br><br>*Note: It is impossible, in the context of ATM, to know that the AIRM is complete.* |

### Logical Model Objects

| <mark style="background-color:lightblue">AIRM_Rule</mark> `113` |
| :- |
| A model element with the stereotype `<<Data_Object>>` shall be a specialisation of the abstract Object.<br><br>*Note: Object is obviously exempt from this rule.* <br><br>*Note: The specialisation can be via a more generalised object.* |

### Properties

| <mark style="background-color:lightblue">AIRM_Rule</mark> `44` |
| :- |
| All properties of an entity, object or datatype shall be given "public" access privileges/scope. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `46` |
| :- |
| In the AIRM Logical Model, attributes shall only be typed by datatypes.<br><br>*Note: This means that they should not be typed by other entities or objects from the AIRM Logical Model.<br><br>Note: This rule does not apply in the AIRM Conceptual Model, so attributes can be typed by other entities. This can help the readability of the model.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `105` |
| :- |
| In the AIRM Logical Model, attributes shall be typed by:<br>- Data types found within the ISO series of standards present in the AIRM Contextual Model; or<br>- Data types found within the AIRM Logical Model’s DataTypes package; or<br>- Codelists found within a Subject.<br><br>Examples:<br>ISO19103 contains primitives for Real, CharacterString, DateTime<br>ISO19107 contains geometry constructs<br>ISO19108 contains temporal constructs<br>ISO 639-2 contains language codes<br><br>*Note: AIRM specific data types which specialise or otherwise reuse the ISO series can be found in the AIRM Logical Model’s DataTypes package.* <br><br>*Note: AIRM specific codelists can be found in dedicated packages within the relevant Subject.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `22` |
| :- |
| In the AIRM Logical Model, attributes shall, by default, be represented with multiplicity of [0..1] (zero to one). If an operational constraint has been identified then multiplicities shall be chosen to reflect such constraints.<br><br>*Note: If no explicit attribute multiplicity is given, [0..1] multiplicity is implied. <br><br>Note: Further constraints on multiplicity may be added in "AIRM Derived" models.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `26` |
| :- |
| In the AIRM Logical Model, role names shall, by default, be represented with multiplicity `[0..*]` (zero to many). If an operational constraint has been identified then multiplicities shall be chosen to reflect such constraints.<br><br>*Note: If no explicit role name multiplicity is given, `[0..*]` multiplicity is implied.*<br><br>*Note: Further constraints may be added in "AIRM Derived" models such as in Physical Data Models.* |

### Associations

| <mark style="background-color:lightblue">AIRM_Rule</mark> `47` |
| :- |
| Datatypes shall not be used as an end-point in an `UML::Association`. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `45` |
| :- |
| Associations between entities shall be modelled using an `UML::Association` where navigability is unspecified. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `82` |
| :- |
| A model element with the stereotype `<<Data_Object>>` shall be made part of a `<<Data_Entity>>` or another `<<Data_Object>>` by means of a `UML::Aggregation` association. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `132` |
| :- |
| In the `AIRM Conceptual Model` every association (except specialisation/generalisation) shall have at least:<br>- One association name with a labelled direction, or<br>- One role name. The role names shall be added to the end of the association which has semantic significance (i.e. as the property of an entity). In the case of `UML::Aggregation` and `UML::Composition` the role name shall be added only at the “part” end of the association. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `23` |
| :- |
| In the `AIRM Logical Model` every association (except specialisation/generalisation) shall have at least one role name. The role names shall be added to the end of the association which has semantic significance (i.e. as the property of an entity). In the case of `UML::Aggregation` and `UML::Composition` the role name shall be added only at the “part” end of the association. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `114` |
| :- |
| Associations shall not be named in the `AIRM Logical Model`.<br><br>*Note: Role names should be used in preference to relationship names. However, it is accepted that naming relationships can improve the readability of the AIRM Conceptual Model which is why this rule is limited in scope.* | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `124` |
| :- |
| In the AIRM Conceptual Model, any association name information supplied shall be considered informative, i.e. it will not have to be respected by derived models or by the `AIRM Logical Model`. | 

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `22` |
| :- |
| `UML::Specialisation` should not be given an association name or a role name.<br><br>Rationale: `UML::Specialisation` has a pre-defined (semantic) meaning in UML as a special type of `UML::Association`. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `24` |
| :- |
| `UML::Aggregation` and `UML::Composition` should not be given an association name.<br><br>Rationale: `UML::Aggregation` has a pre-defined (semantic) meaning in UML as a special type of `UML::Association`. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `14` |
| :- |
| The use of association classes should be limited. However, they may be used to model attributes specific to one specific relationship, in situations where the association management business process is unspecified or out of scope of the model. |

### Aggregation and composition

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `11` |
| :- |
| The use of `UML::Aggregation` and `UML::Composition` between entities should be avoided where possible. They should be used only where there is a real-world constraint or they are otherwise allowed by a rule. |

### Generalisation- specialisation

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `6` |
| :- |
| An entity can be a specialisation of more than one general entity. <br><br>Rationale: Generalisation and specialisations commonly occur in models where concerns such as data structures, algorithms, technology, implementations etc. are not considered.<br><br>*Note: The UML terms of generalisation and specialisation is preferred over ‘inheritance’ in order to be aligned with UML and NAF terminology. The term inheritance is often associated with technical /programming thinking and aspects.*  |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `28` |
| :- |
| If a single-generalisation modelling construct can be found, with the same modelling effect as a multiple-generalisation modelling construct, then that construct shall be selected.<br><br>Rationale: Extensive use of multiple generalisation and specializations may create complex models that may be more difficult to extend over time. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `12` |
| :- |
| Deep generalisation and specialisation hierarchies should be avoided. |

### Data Types

#### Codelists

| <mark style="background-color:lightblue">AIRM_Rule</mark> `32` |
| :- |
| The issuing Authority of a codelist shall be identified and represented by an `AIRM::TaggedValue` `Authority`, attached to the codelist.<br><br>*Note: More than one Authority may be attached to a codelist in case of joint governance.* <br><br>Example: ICAO |

## Definition Conventions

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `30` |
| :- |
| A good definition:<br>- Is a dictionary-style statement that describes the concept designated by a term.<br>- Helps to establish the textual match between languages by stating the essential and delimiting characteristics of a concept (semantic feature).<br><br>*Note: The quality of the definition is crucial, because without knowing what is meant exactly, we cannot communicate effectively, and without fully understanding the concept, we cannot establish relationships between concepts in our subject field.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `3` |
| :- |
| All model elements within the AIRM shall have a definition. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `34` |
| :- |
| If Sparx Enterprise Architect is used to maintain the AIRM (see Recommendation 7), a definition of an AIRM model element shall be stored in the Notes feature. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `35` |
| :- |
| The definition shall use the following principles for good definitions:<br>- **Predictability** - the definition inserts the concept into a concept system.<br>- **Simplicity** - the definition is concise, clear, and whenever possible no longer than one sentence; it includes only essential information.<br>- **Affirmativeness** - the definition states what the concept is, rather than what it is not.<br>- **Non-circularity** - the definition does not use words whose definitions refer back to the concept in question, nor does it begin with the term itself.<br>- **Absence of tautology** - the definition is not a paraphrase of the term, but rather a description of the semantic features of the concept.<br>- **Part of speech** - the definition begins with a word of the same part of speech as the term being defined.<br><br>Example: aerodrome: a defined area on land or water (including any buildings, installations and equipment) intended to be used either wholly or in part for the arrival, departure and surface movement of aircraft/helicopters.<br><br>*Note: Stating a synonym is not a definition!* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `37` |
| :- |
| The source of a model element definition shall be represented in a `AIRM::TaggedValue`, `Definition:Source` that indicates its origin. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `63` |
| :- |
| The `Definition:Source` for a model element shall be listed in the AIRM Standards Catalog. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `26` |
| :- |
| Extra details concerning the source of a model element definition should be captured in the `AIRM::TaggedValue` `Definition:SourceDetail`.<br><br>Example: This can be used to pinpoint the exact ICAO document used or a section within a larger document. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `60` |
| :- |
| The `Definition:Adapted` `AIRM::TaggedValue` shall be completed in order to indicate the level of semantic correspondence with the source definition. The list of values is:<br>- `ExactCopy`: Definition of source and target are exact copy of each other. <br>- `SyntacticallyEqual`: Syntax corrections (grammar, spelling) <br>- `Rewritten`: The definition has been rewritten for improved quality. The meaning is the same, i.e. the definition still describes exactly the same entity as the target definition. <br>- `Specialised`: Source definition is a special case of the target definition.<br>- `Generalised`: Source definition is a generalised case of the target definition. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `38` |
| :- |
| A definition shall not contain references to a name of the submitter, origin or external model or source. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `39` |
| :- |
| A definition shall not contain references to how it is used.<br><br>Example: “This is primarily used by x, y, and z” is not an allowed definition. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `40` |
| :- |
| Definitions shall contain a “straight definition”. That is, they should not start with “This class defines…” or “This property represents…”. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `62` |
| :- |
| Any synonyms for a model element's name shall be represented as a comma separated list in an `AIRM::TaggedValue` `Definition:Synonyms`. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `17` |
| :- |
| Any abbreviation or acronym for a model element's name shall be represented in an `AIRM::TaggedValue` `Definition:Abbreviation`. |

## Diagram Conventions

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `31` |
| :- |
| In the `AIRM Conceptual Model`, UML is used to create two types of diagram:<br>- `Hierarchy` diagrams which are used to express taxonomies using `UML::Specialisations`<br>- `Analysis` diagrams which are used to give a narrative about the AIRM model elements contained on the diagram expressed as a (network) of, for example, `UML::Associations`, `UML::Roles` and `Diagram::Notes`. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `133` |
| :- |
| In the `AIRM Conceptual Model`, a diagram shall be either a `hierarchy` diagram or an `analysis` diagram. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `134` |
| :- |
| In the `AIRM Conceptual Model`, a diagram shall have a stereotype of `<<Analysis>>` or `<<Hierarchy>>` assigned. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `135` |
| :- |
| In the `AIRM Conceptual Model`, every `<<Analysis>>` diagram shall be documented by explaining the following:<br>- Content: What is this diagram about? (mandatory) |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `25` |
| :- |
| In the `AIRM Conceptual Model`, every `<<Analysis>>` diagram should be documented by explaining the following:<br>- (Maturity) Status - <free text> (optional)<br> - Assumptions (optional)<br>- Additional comments (optional)<br>- Link to Requirements (optional) |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `23` |
| :- |
| In the `AIRM Conceptual Model` all diagrams should be possible to read on an A4 format (either in landscape or portrait.) |

## Intellectual Property Rights

| <mark style="background-color:lightblue">AIRM_Rule</mark> `9` |
| :- |
| All parts of the AIRM shall have following the BSD-type licence attached: |

> Copyright (c) 2019, Members of the AIRM CCB
>
> ==========================================
> 
> All rights reserved.
> 
> Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
> 
> * Redistributions of source code must retain the above copyright notice, this list of conditions and the disclaimer.
> 
> * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the disclaimer in the documentation and/or other materials provided with the distribution.
> 
> * Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
> 
> DISCLAIMER
> 
> THIS SPECIFICATION IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE
> 
> ==========================================
> 
> Editorial note: this license is an instance of the BSD license template as provided by the Open Source Initiative: http://opensource.org/licenses/BSD-3-Clause
> 
> Details on the AIRM CCB and a list of its members is available on request from swim@eurocontrol.int.

## General Principles, Rules and Recommendations

### Evolution

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `22` |
| :- |
| Evolution refers to how model elements evolve over time (e.g. version, status, lifecycle, etc). |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `65` |
| :- |
| The status of a model element shall be given in the `Status` property. The value shall be one of the following: <br>- `Published`: The model element is implemented and has been included in an official AIRM release.<br>- `Deprecated`: The model element is no longer fit for use and will deleted in the version stated in the `AIRM::TaggedValue` `Deprecated:TargetRelease`. |

### Deprecation

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `8` |
| :- |
| Deprecation of a model element indicates that it is about to be deleted in a subsequent release. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `15` |
| :- |
| A model element that is marked as deprecated should not further be used and a warning or error should be emitted if it is actually used. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `50` |
| :- |
| A model element that is marked as deprecated shall contain the following `AIRM::TaggedValues`:<br>- `Deprecated:DecisionDate`: (mandatory) date of deprecation decision<br>- `Deprecated:Rationale`: (mandatory) short rational for the deprecation<br>- `Deprecated:TargetRelease`: (optional) planned release when the deprecated element will be deleted<br>- `Deprecated:Replacement`: (optional) reference to other elements that should or shall be used instead |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `51` |
| :- |
| A model element shall be deleted from the model only after it has been marked as “Deprecated” in a previous release. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `52` |
| :- |
| A model element that is to be deprecated shall be listed in the AIRM Release Notes. |

### AIRM Internal Semantic Trace from Logical Model to Conceptual Model

| <mark style="background-color:lightblue">AIRM_Rule</mark> `137` |
| :- |
| In the `AIRM Logical Model`, every entity shall have at least one semantic trace to at least one model element in the AIRM Conceptual Model. |

### Supplements

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `36` |
| :- |
| An `AIRM supplement` is a package within the AIRM that elaborates the AIRM content for a specific community |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `144` |
| :- |
| The supplements shall fit within the scope of the AIRM, meaning that it should be relevant to ATM. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `145` |
| :- |
| The supplement shall follow the same rules as other AIRM content.<br><br>*Note: this means following naming conventions, stereotypes, completion of metadata about a model element, etc.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `146` |
| :- |
| The supplement shall follow the structure of the main AIRM.<br><br>*Note: this means it may have a contextual, a conceptual and a logical model. Indeed, it must have at least one of these.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `147` |
| :- |
| The supplement shall not introduce new model types such as physical models. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `148` |
| :- |
| The supplement should not have dependencies on the content of other supplements.<br><br>*Note: this is to ensure that the change management of one supplement does not affect another supplement. However, reuse of definitions across supplements is to be encouraged.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `149` |
| :- |
| The supplement shall not remove or otherwise restrict the content of the main AIRM.<br><br>*Note: supplements are about elaborating the content of the main AIRM. The ability to restrict the AIRM is handled by the AIRM derivation rules and should be handled as a separate step in the development cycle.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `150` |
| :- |
| Supplements shall contain, where necessary: <br>- additional subjects;<br>- additional entities;<br>- additional objects;<br>- additional data types;<br>- additional relationships;<br>- additional properties;<br>- additional local definitions. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `151` |
| :- |
| The model elements in the supplement shall have URNs. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `37` |
| :- |
| The relationship between two model elements is owned by the source. This applies to associations between model elements and to the properties of a model element that are typed by another model element. For example, if Class1 "has" Class2, the "has" association is owned by Class1; if Class 1 contains a property "name" that is typed as a CharacterString, the "name" property is owned by Class 1. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `38` |
| :- |
| The main AIRM content cannot own an association or property where the target exists in a supplement. | 

| <mark style="background-color:lightblue">AIRM_Rule</mark> `152` |
| :- |
| When supplementing a model element from the main AIRM, the supplement shall use the same name as the model element that it is supplementing. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `153` |
| :- |
| When supplementing a model element from the main AIRM, the supplement shall use the same definition as the model element that it is supplementing. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `154` |
| :- |
| When adding properties to a model element from the main AIRM, the supplement shall use a specialization of the model element that it is supplementing. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `155` |
| :- |
| When adding relationships to a model element from the main AIRM, the supplement shall use a specialization of the model element that it is supplementing. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `156` |
| :- |
| The specialization association shall be stereotyped `<<supplement>>`. <br><br>*Note: This makes the exact nature of the specialization clear.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `157` |
| :- |
| Additional local definitions shall be added to the note field, below the existing definition, separated by a <<supplement>> stereotype |

### Derivation

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `23` |
| :- |
| Derivation refers to the way in which model elements can be restricted and subsetted by users of the AIRM. Adaptation is also related to compliance. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `10` |
| :- |
| An `AIRM Derived Model` is a model that uses the AIRM to define its semantics but serves a specific restricted purpose.<br><br>Examples:<br>- A NSV-11b product shall be a derived model.<br>- Existing models shall prove they are "derivable from" the AIRM as a key element in claiming compliance with the AIRM. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `11` |
| :- |
| AIRM Derivation Rules are the set of rules to apply in order to establish traceability of the semantics of a given model to the AIRM. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `12` |
| :- |
| Derivation of the AIRM works by restriction. Therefore:<br>- Any additional model elements of an AIRM Derived Model, assumed to be within the scope of the AIRM, should be traced to a Change Request identifier in the semantic correspondence statement of the Information Definition.<br>- Any additional model elements, assumed to be outside the scope of the AIRM, should be traced to the “Out-Of-Scope” construct in the semantic correspondence statement of the Information Definition. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `54` |
| :- |
| A derived model shall declare any deviation from the AIRM Rulebook.<br><br>*Note: For example, the AIRM naming conventions may not be applicable to an already existing model. In that case, deviations from the AIRM Rulebook shall be documented and explained.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `55` |
| :- |
| The upper bound of the multiplicity specified in a derived model shall be lower or equal to the upper bound of the multiplicity and greater or equal to the lower bound of the multiplicity specified in the AIRM. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `56` |
| :- |
| The lower bound of the multiplicity specified in a derived model shall be greater or equal to the lower bound of the multiplicity and lower or equal to the upper bound of the multiplicity specified in the AIRM. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `13` |
| :- |
| A derived model may declare leaf nodes final. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `14` |
| :- |
| A derived model may describe physical implementations of generalisation. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `16` |
| :- |
| A derived model may describe physical implementations of generalisation. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `15` |
| :- |
| A derived model may add navigability to its relationships.<br><br>*Note: This does not mean that the associations cannot be navigated in the other direction but the directionality is a hint that implementations should make the navigation in the primary direction convenient and efficient.* |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `17` |
| :- |
| Constraints and business rules present in the AIRM can be further restricted in a derived model. They cannot be extended.<br><br>Example: A business rule restricts the length of a CharacterString to 4 characters. It can be restricted to length [2] but cannot be extended to length [7]. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `18` |
| :- |
| Further constraints (including patterns, maximum values) may be added to a derived model.<br><br>Example: The length of datatypes may be restricted. For example, in the AIRM CharacterStrings are not given a maximum length. They can be restricted e.g. to length [10]. |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `20` |
| :- |
| A derived model may convert an attribute to a role name or vice versa. This means:<br>- A property modelled as an UML attribute in the AIRM may be converted into a property modelled as a role, with a complex “constructed” type.<br>- A property modelled as a role name in the AIRM may be converted into an attribute (e.g. if multiplicity is restricted to 1..1). |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `59` |
| :- |
| A derived model shall not use an AIRM term with a conflicting definition.<br><br>*Note: If a derived model does not use the original AIRM definition, a reference to the AIRM definition needs to be provided.* |

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `19` |
| :- |
| In a derived model, AIRM codelists:<br>- May remain as codelists; or<br>- May be converted to enumerations (which can be seen as a restricted codelist); or<br>- May be converted to a series of classes. |

### AIRM Uniform Resource Name (URN)

| <mark style="background-color:lightgrey">AIRM_Principle</mark> `35` |
| :- |
| To facilitate the referencing of the AIRM, each AIRM model element has a globally unique name. This unique name is defined according to the Uniform Resource Name (URN) standard [6]. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `76` |
| :- |
| The URN of an AIRM model element shall use the structure: `<URN>::`= "urn:" `<NID>``:``<NSS>`<br><br>Example: A full URN to a property of an entity: `urn:aero:airm:1.0.0:ConceptualModel:Subjects:AirTrafficOperations:AirportOperationsManagement:TaxiOut@EXOT`<br><br>*Note: An AIRM namespace identifier (`NID`) and namespace specific string (`NSS`) are defined in Rules 70-72 and 74, respectively.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `70` |
| :- |
| AIRM model elements shall use the namespace identifier (`NID`): `NID` = `aero` |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `71` |
| :- |
| The namespace specific string (NSS) shall use the structure: `NSS` = `<MODEL_NSS>` `:` `<ELEMENT_NSS>` |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `72` |
| :- |
| The Model Namespace Specific Strings (`MODEL_NSS`) shall use the structure: `MODEL_NSS` = `<ISSUER>`? `:` `<PRODUCT>`:`<VERSION>`<br>The following terms are used in `<MODEL_NSS>`<br>- `<ISSUER>` defines the agency responsible for the AIRM version in question (where applicable). This item shall be a URI itself.<br>- `<PRODUCT>` identifies the AIRM (or an AIRM Derived Model by the same issuer).<br>- `<VERSION>` is the version number of the product in question. The syntax and semantics are issuer specific (e.g. may or may not include issuer specific branch information).<br><br>*Note: The components of the `MODEL_NSS` are considered as case insensitive, e.g. AIRM and “airm” refer to the same product.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `74` |
| :- |
| The Element Namespace Specific Strings (`ELEMENT_NSS`) shall use the structure: `ELEMENT_NSS` = (`<NAME_OF_PACKAGE>` `:`)+(`<NAME_OF_CLASS>`(`@` `<NAME_OF_PROPERTY`)?)?<br>The following terms are used in `<ELEMENT_NSS>`<br>- `<NAME_OF_PACKAGE>` is the recursive definition of the model element’s position within the AIRM UML Package structure<br>- `<NAME_OF_CLASS>` is the name of the UML Class in question (where applicable)<br>- `<NAME_OF_PROPERTY>` is the name of the UML property within the class (where applicable)<br><br>*Note: The components of the `ELEMENT_NSS` are considered case sensitive.* |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `79` |
| :- |
| The `ISSUER` component of the `MODEL_NSS` shall be left empty. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `77` |
| :- |
| The `PRODUCT` component of the `MODEL_NSS` shall be: `PRODUCT` = `AIRM`. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `73` |
| :- |
| The URN of AIRM Contextual Model elements that already have a URN issued by their originator shall be respected. This means that these elements shall uniformly be referenced by the original URN and the AIRM shall not issue an additional URN for these elements. |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `16` |
| :- |
| Models derived from the AIRM should reference `MODEL_NSS` to disambiguate their semantic binding to the AIRM. |

| <mark style="background-color:lightblue">AIRM_Rule</mark> `75` |
| :- |
| Published AIRM model element semantics shall be backward compatible. <br>That is, a given `ELEMENT_NSS` referring to an AIRM model element in development status `published` or `deprecated` shall always refer to the same logical concept. Its semantics shall not depend on the context of a `MODEL_NSS`. |

## Detailed Rules on Specific AIRM Components

### AIRM Technical Standards Profile

| <mark style="background-color:lightblue">AIRM_Rule</mark> `127` |
| :- | 
| Each standard in `AIRM Standards Catalog:UML` shall follow the minimum standard description syntax as depicted below <br><br> ![Image](.//media/rulebook_minimum_standard_description.png "Minimum_Standard_Description") <br><br>- where the publishing organisation is either the organisation behind the standard or a concatenation of the organisation, a hyphen, and its publishing part, <br><br> ![Image](.//media/rulebook_publishing_organisation.png "Publishing Organisation")  <br><br>- and where the publishing organisation is either the organisation behind the standard or a concatenation of the organisation, a hyphen, and its publishing part <br><br> ![Image](.//media/rulebook_name_of_standard.png "Name of Standard") <br><br> Examples:<br>- OMG UML<br>- NATO STANAG 3809<br><br>*Note: The wording syntax is fully explained in Appendix B.* |

| <mark style="background-color:yellow">AIRM_Recommendation</mark> `19` |
| :- |
| Each standard in `AIRM Standards Catalog:UML` should follow the full standard description syntax as depicted below<br><br> ![Image](.//media/rulebook_full_standard_description.png "Full Standard Description") <br><br> - where the minimum standard description is explained as part of the AIRM_Rule 127<br>- where document name follows the syntax below<br><br> ![Image](.//media/rulebook_document_name.png "Document Name") <br><br>- where standard version follows the syntax below<br><br> ![Image](.//media/rulebook_standard_version.png "Standard Version") <br><br> - where Volume follows the syntax below. <br><br> ![Image](.//media/rulebook_volume.png "Volume") <br><br> Examples:<br>ICAO Doc 8168, Vol. I, 5th Ed<br>ICAO Doc 8400, 8th Ed<br>NATO NAF v.3<br><br>*Note: The wording syntax is fully explained in Appendix C.* |

## References

- [1]: [NATO Architecture Framework (NAF), v3](https://training-course-material.com/training/Category:NAF)
- [2]: [OMG Unified Modelling Language (UML), v2.1](https://www.omg.org/uml/)
- [3]: [OMG Semantics of Business Vocabulary and Business Rules (SBVR), v1.0](https://www.omg.org/spec/SBVR/1.0)
- [4]: [OMG UML Superstructure](https://www.omg.org/spec/UML/2.4.1/Superstructure/PDF)
- [5]: [UPDM](https://www.omg.org/spec/UPDM/1.0.1)

## Appendix A. AIRM Meta-Model

![Image](.//media/airm_meta_model_1.png "AIRM Meta-Model Overview")

Figure 1: AIRM Meta-Model Overview

![Image](.//media/airm_meta_model_2.png "AIRM Meta-Model Core")

Figure 2: AIRM Meta-Model Core

![Image](.//media/airm_meta_model_3.png "AIRM Meta-Model ISO")

Figure 3: AIRM Meta-Model ISO

![Image](.//media/airm_meta_model_4.jpg "Measures in the AIRM meta-model")

Figure 4: Measures in the AIRM meta-model

| Meta-Model Element Name | Description |
| :- | :------- |
| AIRMConstraint | An element of guidance that introduces an obligation or a necessity, i.e., a rule that applies to AIRM model element(s). Rules shall be satisfied by all instances of the AIRM Entities they apply to. Exception: AIRM::Constraint does not cover multiplicity nor ordering constraints. Those are captured as a part of standard UML. |
| Attribute | A defined property of an AIRM Entity. |
| Constraint:AppliesTo | Rule that applies to the AIRM Entity or property |
| Constraint:FormatType | Provides format for articulation of the constraint |
| defines | A formalised representation of data which is managed by or exchanged between systems. |
| Definition:Abbreviation | Abbreviations |
| Definition:InLexicon | Whether the term definition is in the ATM Lexicon. |
| Definition:Source | Source for a definition. |
| Definition:Synonyms | Synonyms for the definition. |
| Deprecated:Decision date | Date of deprecation decision. |
| Deprecated:Rationale | Short rationale for the deprecation. |
| Deprecated:Replacement | Reference to other elements to use instead. |
| Deprecated:TargetRelease | Planned release to delete deprecated element. |
| Mapping:Remarks | Remarks on a mapping from a source to a target. |
| SemanticTrace::Information_Entity | Trace between Data_Enitity to Information_Entity/Information_Message. |
| SemanticTrace::Information_EntityRole | Trace between Data_Entity and Conceptual Model role name. |
| MEGA:UniqueIdentifier | Unique identifier for integration with Mega. |
| represents | A formalized representation of information, subject to an operational process. |
| Data_Entity | A definition (type) of an data (ATM) item of interest that is implementation independent and it is subject to constraints. |
| Data_Object | A standardized or formalized collection of an (Logical Model) Entity's or Association’s Property/(ies).A Data_Object does not exist without the (Logical Model) Entity or Association it is associated with but can be part of the operational language or system-specific property. This appears as a UML class or association class in the AIRM. |
| ISO:CodeList | CodeList is used to describe a flexible and open enumeration UML::Enumeration. |
| ISO:CodelistLiteral | A value listed in the codelist |
| Entity | A definition (type) of an ATM item of interest that is subject to AIRM representational rules. |
| Contextual_Entity | Entity that internally represents part of a standard. |
| Information_Entity | A definition (type) of an operational ATM item of interest that is subject to constraints. |
| Information_Message | ATM specific message type. |
| NAF::Alias | lang=EN-US mso-ansi-language:EN-USAn alternative name for an element. |
| NAF::Attribute | A defined property of an Entity. |
| NAF::Definition | A definition of an element in the architecture. Note - every element added by an architect must have a definition. |
| NAF::Entity | A definition (type) of an item of interest. |
| NAF::Standard | A ratified and peer-reviewed specification that is used to guide or constrain the architecture. |
| Property | A property is a typed element that represents an attribute of a class hat is subject to AIRM representational rules. |
| Role | (AIRM) Role represents an attribute of the source Entity's associationEnd. |
| Standard | A document that provides requirements, specifications, guidelines or characteristics that can be used consistently to ensure that materials, products, processes and services are fit for their purpose. [ISO] |
| StereotypeAttribute | From UML version 2.0 the previously independent tagged value is considered to be a stereotype attribute. The name tagged value is still kept. Each stereotype has zero or more tag definitions, and all stereotyped UML elements have the corresponding number of tagged values. |
| Subject | Represents a field of specific knowledge. These appear as packages in the AIRM. |
| TaggedValue | Tagged Value is a string-based extension that could be attached to UML model elements in a flexible way. |
| UML: DataType | DataType is the abstract class that represents the general notion of being a data type (i.e., a type whose instances are identified only by their value). |
| ISO:Measure | A Measure is the result from performing the act or process of ascertaining the value of a characteristic of some entity. [ISO 19103] |
| ISO:UnitOfMeasure | A unit of measure is a quantity adopted as a standard of measurement for other quantities of the same kind. [ISO 19103] |
| UML::Element | An element is a constituent of a model. As such, it has the capability of owning other elements. |
| UML::ModelElement | An element is a constituent of the AIRM UML model. |
| UML::Property | A property is a typed element that represents an attribute of a class. |
| UML::Slot | A slot specifies that an entity modeled by an instance specification has a value or values for a specific structural feature. |

## Appendix B. Wording Syntax

This Appendix presents a notation for wording syntax, based on a visualisation of Extended Backus–Naur Form (EBNF) and is adopted as subset of the ISO/IEC 14977:1996(E) standard.

| Graphical Element | Interpretation |
| :- | :------- |
| ![Image](.//media/wording_syntax_1.jpg "") | Indicates a mandatory element. |
| ![Image](.//media/wording_syntax_2.jpg "") | Indicates order between two (mandatory) elements. Meaning that “name_1” has to be followed “name_2” in order to satisfy the “full_name” syntax. |
| ![Image](.//media/wording_syntax_3.jpg "") | Indicates an optional element. |
| ![Image](.//media/wording_syntax_4.jpg "") | Indicates a mandatory element, which may occur several times. |
| ![Image](.//media/wording_syntax_5.jpg "") | Indicates an optional element, but which may occur several times. |
| ![Image](.//media/wording_syntax_6.jpg "") | Indicates a choice between two elements. Either one or the other one must be used. |
| ![Image](.//media/wording_syntax_7.jpg "") | More than one element can appear on an optional, choice or mandatory branch. |

