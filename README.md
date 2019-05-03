# metadata

## metadata standards
- to be useful and understandable, metadata must be standardized to provide a common language with semantics that are as clearly defined (and unambiguous) as possible
- without a common language, integration and interoperability are not possible
- XML is the language of choice for most industry standards due to its semi-structured nature which provides a way to organize properties and facilitate easier analysis and comparison, while still providing support for unstructured data

### industry standards
- many industries have come up with solutions in the form of standards and schemas for recording metadata to provide information to end users for datasets, models, and code
- it would be wise for the ML domain to look into the state of the art for metadata management in other domains that have been addressing these issues over the past few decades.  Metadata to help end users understand and evaluate appropriate usage and handle bias have already been baked into metadata standards in these domains.

### issues with standards
- are top-down and require 

## gis domain
- http://desktop.arcgis.com/en/arcmap/10.3/manage-data/metadata/a-quick-tour-of-creating-and-editing-metadata.htm#ESRI_SECTION1_CC2F6DEED69B428D8C694D2804F00640
- http://desktop.arcgis.com/en/arcmap/latest/manage-data/metadata/illustrated-guide-to-complete-fgdc-metadata.htm#GUID-16DC4914-3953-405B-BFEC-555C129961F3
- https://www.fgdc.gov/resources/factsheets/documents/GeospatialMetadata-July2011.pdf
- https://www.fgdc.gov/metadata/documents/ValueOfMetaFiles/ValueOfMetaPDF

## computer science domain
- 1997: https://www.cs.waikato.ac.nz/~ml/publications/1997/Cunningham-Cataloging97.pdf


## machine learning industry - 2018-19
- this is not a new concept, but the ML domain is struggling with how to manage this with the explosion of ML models in the wild

### [model cards](http://delivery.acm.org/10.1145/3290000/3287596/p220-Mitchell.pdf?ip=170.225.9.141&id=3287596&acc=NO%20RULES&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2ED2E531DB056F4A45%2E4D4702B0C3E38B35&__acm__=1556846985_823be4d723bed277a13ad2335eecd8d8) (Google + U of T) - January 2019
- general concepts and a framework for what metadata is necessary to clarify the intended usage of ML models
- NOT an actual machine-readable implementation/schema 
- good starting point for identification of what information is useful, but will require a machine-readable definition to become truly useful

### [datasheets for datasets](https://arxiv.org/pdf/1803.09010.pdf) (Google + Microsoft Research + AI Now + universities) - April 2019
- "motivation, composition, collection process, recommended uses"
- creation, distribution, and maintenance process
- provide a set of questions covering the information that a datasheet for a dataset might contain, they are not intended to be prescriptive
- propose a reflective and manual process of creation, not automated to avoid the pitfalls

### [factsheets for datasets](https://www.ibm.com/blogs/research/2018/08/factsheets-ai/) (IBM) - February 2019 (August 2018)
- IBM refers to this sort of metadata as a 'Supplier's Declaration of Conformity (SDoC)'
- similar to Google/Microsoft's concept of a datasheet, it prescribes dataset metadata categories and questions for each that the supplier of the dataset should provide
- goal of the factsheet is to address concerns over fairness, explainability, bias, etc

### [data statements](https://www.mitpressjournals.org/doi/abs/10.1162/tacl_a_00041) (U of W) - 2018
- more ethically responsive models
- mitigating bias
