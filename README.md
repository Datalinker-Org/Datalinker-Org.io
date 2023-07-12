# DataLinker.org - Home of the Farm Data Standards
  
The specifications on this web site started life as the **New Zealand Farm Data Standards**, an early effort by the New Zealand (and later, international) agricultural and agritech community to define common vocabularies to define farm data. Over time, the specifications have grown and aligned with other standardisation, specification, and controlled vocabulary projects. 

## Glossaries and Data Dictionaries
The Farm Data Standards were not approved by any [international standards body](https://en.wikipedia.org/wiki/Standards_organization), so it is better to refer to them as agricultural glossaries or data dictionaries. Originally delivered as PDF files, the glossaries and data dictionaries are now maintained using GitHub and presented as markdown for easy maintenance by the community.

* **Analysts** should consider using the data dictionaries for consistent naming and description of things (entities), observations or events, and data elements (attributes).
* **Technology developers** may use the information in the design of new software or databases.
* We particularly encourage the use of these definitions to develop **API schemas and support data interoperability**. More about this below.

Widespread alignment with the standards will mean that farmers can spend less time entering data for different farm solutions, and more time using the insights from these solutions to make better decisions on their farms.

<a href="https://www.datalinker.org/overview" class="btn" style="align-items:center">Glossaries and Data Dictionaries</a>

## Common API Specifications
The DataLinker framework was developed as a set of common JSON schemas and API specifications designed to support and encourage API interoperability between agricultural sector businesses, including farm supply companies, processors and retailers, and agritech products. Key elements of the DataLinker specifications include:
* Reusable data schemas in [JSON-LD](https://json-ld.org/) (now mainly replaced by [JSON Schema](https://json-schema.org/) equivalents),
* Use of [OAUTH 2.0](https://oauth.net/2/) token-based mechanisms to allow farmers and growers to control access to their data,
* A registry to allow organisations to discover which other organisations in their region had implemented compliant APIs, and
* A specification based on an extension of OAUTH that would allow data providers to electronically agree to each other's data access terms.

The last two elements of this list proved hard for providers to manage, both for legal reasons and limitations in commonly used OAUTH 2 implementations.
Much of the DataLinker work has been superseeded but is still available:
* The source code for the DataLinker registry and its applications are in GitHub (DataLinker Application)
* Livestock data schemas developed in the DataLinker project were submitted to the [International Committee for Animal Recording](https://www.icar.org/) and form a large part of the ICAR [Animal Data Exchange specification](https://github.com/adewg/ICAR). This is widely used in livestock recording and software technologies internationally.
* Spatial data schemas for field and paddock maps were converted to JSON Schema and extended by a New Zealand and Australian working group, these can be found in the [Geospatial Repository](https://github.com/Datalinker-Org/Geospatial).
* The remaining DataLinker schemas for pasture management, benchmarking, and farm assurance status can be found in various [DataLinker Schema Repositories](https://www.datalinker.org/schemas).

<a href="https://github.com/Datalinker-Org/Geospatial" class="btn" style="align-items:center">Geospatial Data Schemas</a>

<a href="https://github.com/adewg/ICAR" class="btn" style="align-items:center">Animal Data Exchange</a>
