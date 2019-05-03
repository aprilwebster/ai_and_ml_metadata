# metadata

## metadata standards
- to be useful and understandable, metadata must be standardized to provide a common language with clear semantics
- without a common language, integration and interoperability are not possible
- XML is the language of choice for industry standards

### standards bodies
- ISO
- IEEE

### industry standards
- many other industries have come up with solutions in the form of standards and schemas for recording metadata to provide information to end users of datasets and models
- it would be wise of the ML domain to look into what other domains have done over the past few decades to address this problem

## machine learning domain
- this is not a new concept, but the ML domain is struggling with how to manage this with the explosion of ML models in the wild

### model cards (Google + U of T)
- general concepts and a framework for what metadata is necessary to clarify the intended usage of ML models
- NOT an actual machine-readable implementation/schema 
- good starting point for identification of what information is useful, but will require a machine-readable definition to become truly useful

### datasheets for datasets (Google + Microsoft Research + AI Now + universities) - April 2019
- "motivation, composition, collection process, recommended uses"
- creation, distribution, and maintenance process
- provide a set of questions covering the information that a datasheet for a dataset might contain, they are not intended to be prescriptive
- propose a reflective and manual process of creation, not automated to avoid the pitfalls

### factsheets for datasets (IBM) - August 2018 (revised February 2019)
- https://www.ibm.com/blogs/research/2018/08/factsheets-ai/ - link to the paper included in this blog post; submitted to FAT 2019
- IBM refers to this sort of metadata as a 'Supplier's Declaration of Conformity (SDoC)'
- similar to Google/Microsoft's concept of a datasheet, it prescribes dataset metadata categories and questions for each that the supplier of the dataset should provide
- goal of the factsheet is to address concerns over fairness, explainability, 

### data statements (U of W)
https://openreview.net/pdf?id=By4oPeX9f
-  more ethically responsive models
