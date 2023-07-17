<h4>Data Glossary</h4>
<ul class="sub-menu">
  <li class="menu-item"><a class="active" href="https://www.datalinker.org/legal">Legal</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/biophysical">Biophysical</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/management">Management</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/outcome-metrics">Outcome Metrics</a></li>
</ul>
<hr>

<h2 id="datalinker">Activity</h2>
<a href="/assets/files/Farm Data Terms & Definitions- updated list - Master 2023-02.xlsx" class="btn" style="align-items:center" download="">Download Glossary (.xlxx)</a>


| Preferred Term 	| Synonyms 	| Definition  	| Data Type 	| Regulatory Requirement Context 	| Source 	| Data Specifications 	|
|---	|---	|---	|---	|---	|---	|---	|
| Area Measurement 	| Area 	| Area of a surface determined from its geometrical dimensions, not including surface roughness. The area measurement specification shall include units (mandated or explicitly listed). International Units or UN-CEFACT units are preferred. 	| Object 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.iso.org/obp/ui/#iso:std:iso:ts:20177:ed-1:v1:en:term:3.2){:target="_blank"} 	| [View](https://github.com/Datalinker-Org/Geospatial/blob/master/types/AreaMeasureType.json){:target="_blank"} 	|
| Business Name 	| Organization name,  Enterprise name,  Venture name,  Company name,  Firm name   	| A name for a company, incorporated society, or other businesss entity. 	| String 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.legislation.govt.nz/act/public/1993/0105/latest/DLM320108.html){:target="_blank"} 	| [View](https://schema.org/Organization){:target="_blank"} 	|
| Cadastral Parcel 	| Land parcel, Field book, titles, Cadastral boundary 	| Cadastral survey data that represents the spatial extent of interests under a tenure system. 	| Object 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.legislation.govt.nz/act/public/2002/0012/latest/whole.html){:target="_blank"} 	|  	|
| Farm Name 	| Field name,  Estate name 	| The name by which a farm is known to its management, owners, employees, suppliers and/or customers. 	| String 	| Fresh water 	|  	| [View](https://github.com/Datalinker-Org/Geospatial/blob/master/resources/HoldingResource.json){:target="_blank"} 	|
| Farm Operator 	| Farmer 	| The person with ultimate responsibility for the operation of a farm 	| Object 	| Fresh water 	| [View](https://www.legislation.govt.nz/act/public/1991/0069/latest/whole.html){:target="_blank"} 	|  	|
| Geographic Coordinate System 	| Coordinate System, GPS Coordinates 	| Defines locations on the earth using a three-dimensional spherical surface. It is a reference system that uses latitude and longitude to identify locations on a spheroid or sphere. A datum, prime meridian, and angular unit are parts of a Geographic Coordinate System. 	| Coordinates 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](http://wiki.gis.com/wiki/index.php/Geographic_coordinate_system){:target="_blank"} 	|  	|
| Leased Area 	| Hire area, Rent area, Let area 	| An area of an operating farm holding that is not owned by the operating business entity or another entity within the business group. 	| Area Measurement 	| Fresh water 	|  	|  	|
| New Zealand Business Number 	| NZBN 	| A New Zealand Business Number (NZBN) is a globally unique identifier, available to all New Zealand businesses. 	| Integer 	| Fresh water 	| [View](https://companies-register.companiesoffice.govt.nz/help-centre/getting-support-to-use-the-companies-register/new-zealand-business-number-nzbn/){:target="_blank"} 	| [View](https://schema.org/leiCode){:target="_blank"} 	|
| Operating Farm 	| Farm Unit, Agribusiness Unit, Farm Entity 	| The whole area and all infrastructures included on it, under the control of an operator to perform agricultural or aquaculture activities. It must be composed of one or more Sites. It could be considered as the synthetic geographical representation of a unique operational, economical or legal body. 	| String 	| Fresh water; Emissions; Biodiversity 	| [View](https://github.com/Datalinker-Org/Farm-Data-Standards/blob/master/Farm%20Features%20and%20Attributes/FFADS_Feature-Catalogue.md){:target="_blank"} 	|  	|
| Protected Site 	| wāhi tapu 	| An area designated or managed within a framework of international, Community and Member States' legislation to achieve specific conservation objectives. In NZ, this could be used for QEII Conservation zones. 	| String 	| RMA 	| [View](https://github.com/Datalinker-Org/Farm-Data-Standards/blob/master/Farm%20Features%20and%20Attributes/FFADS_Feature-Catalogue.md){:target="_blank"} 	|  	|
| Total Area 	|  	| Calculated or measured surface area of a spatial feature. 	| Area Measurement 	| Fresh water; Emissions; Biodiversity 	|  	| [View](https://github.com/Datalinker-Org/Geospatial/blob/master/types/SpatialResourceType.json){:target="_blank"} 	|
