<h4>Data Glossary</h4>
<ul class="sub-menu">
  <li class="menu-item"><a class="active" href="https://www.datalinker.org/legal">Legal</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/biophysical">Biophysical</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/management">Management</a></li>
  <li class="menu-item"><a href="https://www.datalinker.org/outcome-metrics">Outcome Metrics</a></li>
</ul>
<hr>

<h2 id="datalinker">Activity</h2>
<p></p>


| Preferred Term 	| Synonyms 	| Definition  	| Data Type 	| Regulatory Requirement Context 	| Source 	| Data Specifications 	|
|---	|---	|---	|---	|---	|---	|---	|
| Area Measurement 	| Area 	| Area of a surface determined from its geometrical dimensions, not including surface roughness. The area measurement specification shall include units (mandated or explicitly listed). International Units or UN-CEFACT units are preferred. 	| Object 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.iso.org/obp/ui/#iso:std:iso:ts:20177:ed-1:v1:en:term:3.2){:target="_blank"} 	| https://github.com/Datalinker-Org/Geospatial/blob/master/types/AreaMeasureType.json 	|
| Business Name 	| Organization name,  Enterprise name,  Venture name,  Company name,  Firm name   	| A name for a company, incorporated society, or other businesss entity. 	| String 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.legislation.govt.nz/act/public/1993/0105/latest/DLM320108.html){:target="_blank"} 	| https://schema.org/Organization 	|
| Cadastral Parcel 	| Land parcel, Field book, titles, Cadastral boundary 	| Cadastral survey data that represents the spatial extent of interests under a tenure system. 	| Object 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](https://www.legislation.govt.nz/act/public/2002/0012/latest/whole.html){:target="_blank"} 	|  	|
| Farm Name 	| Field name,  Estate name 	| The name by which a farm is known to its management, owners, employees, suppliers and/or customers. 	| String 	| Fresh water 	|  	| https://github.com/Datalinker-Org/Geospatial/blob/master/resources/HoldingResource.json 	|
| Farm Operator 	| Farmer 	| The person with ultimate responsibility for the operation of a farm 	| Object 	| Fresh water 	| [View](https://www.legislation.govt.nz/act/public/1991/0069/latest/whole.html){:target="_blank"} 	|  	|
| Geographic Coordinate System 	| Coordinate System, GPS Coordinates 	| Defines locations on the earth using a three-dimensional spherical surface. It is a reference system that uses latitude and longitude to identify locations on a spheroid or sphere. A datum, prime meridian, and angular unit are parts of a Geographic Coordinate System. 	| Coordinates 	| RMA, Fresh water, Emissions, Biodiversity 	| [View](http://wiki.gis.com/wiki/index.php/Geographic_coordinate_system){:target="_blank"} 	|  	|
| Leased Area 	| Hire area, Rent area, Let area 	| An area of an operating farm holding that is not owned by the operating business entity or another entity within the business group. 	| Area Measurement 	| Fresh water 	|  	|  	|
| New Zealand Business Number 	| NZBN 	| A New Zealand Business Number (NZBN) is a globally unique identifier, available to all New Zealand businesses. 	| Integer 	| Fresh water 	| [View](https://companies-register.companiesoffice.govt.nz/help-centre/getting-support-to-use-the-companies-register/new-zealand-business-number-nzbn/){:target="_blank"} 	| https://schema.org/leiCode 	|
| Operating Farm 	| Farm Unit, Agribusiness Unit, Farm Entity 	| The whole area and all infrastructures included on it, under the control of an operator to perform agricultural or aquaculture activities. It must be composed of one or more Sites. It could be considered as the synthetic geographical representation of a unique operational, economical or legal body. 	| String 	| Fresh water; Emissions; Biodiversity 	| [View](https://github.com/Datalinker-Org/Farm-Data-Standards/blob/master/Farm%20Features%20and%20Attributes/FFADS_Feature-Catalogue.md){:target="_blank"} 	|  	|
| Protected Site 	| wāhi tapu 	| An area designated or managed within a framework of international, Community and Member States' legislation to achieve specific conservation objectives. In NZ, this could be used for QEII Conservation zones. 	| String 	| RMA 	| [View](https://github.com/Datalinker-Org/Farm-Data-Standards/blob/master/Farm%20Features%20and%20Attributes/FFADS_Feature-Catalogue.md){:target="_blank"} 	|  	|
| Total Area 	|  	| Calculated or measured surface area of a spatial feature. 	| Area Measurement 	| Fresh water; Emissions; Biodiversity 	|  	| https://github.com/Datalinker-Org/Geospatial/blob/master/types/SpatialResourceType.json 	|



| Common name  | Definition | Source |
| ------------- | ------------- | ------------- |
| Farm Operation  | The activities carried out on a farm to prepare land, manage livestock, produce crops, or achieve environmental or social outcomes.  | - |
| Equipment calibration  | Equipment calibration deals with assessing the accuracy of equipment’s results by measuring the variation against a defined standard to decide upon the relevant correction factors.  | [View](https://learngxp.com/good-validation-practices/defining-calibration-qualification-of-equipment/){:target="_blank"} |
| Grazing management  | 1. Grazing management is the planning, implementation and monitoring of animal grazing to achieve sustained animal, plant, land, environmental and economic results under a range of environmental conditions. <br /> 2.Grazing management is the manipulation of animal grazing to achieve optimum and sustained animal, plant, land, environmental or economic results while ensuring a continuous supply of forages to grazing animals.| [View](http://www.nagrasslands.org/category/beneficial-management-practices/grazing-management/){:target="_blank"} [View](https://www.cost869.alterra.nl/SERA17_BMP/BMP_grazing_management.pdf){:target="_blank"} |
| Pasture renewal | Pasture renewal refers to any method of establishing new pasture plants. | [View](https://www.dairynz.co.nz/media/5793055/dairynz-pasture-renewal-guide-2020.pdf){:target="_blank"} |
| Paddock selection | This means selecting the appropriate paddocks to minimize run-off while maintaining the highest standards of animal welfare. | [View](https://beeflambnz.com/news-views/paddock-selection-critical-when-establishing-winter-crops){:target="_blank"} |
| Intensive winter grazing | Intensive winter grazing is a farming practice where livestock are grazed on paddocks planted with forage crops. | [View](https://www.mpi.govt.nz/agriculture/farm-management-the-environment-and-land-use/protecting-freshwater-health/intensive-winter-grazing/){:target="_blank"} |
| Carbon Capture and Sequestration | Carbon capture and sequestration is a set of technologies that can greatly reduce carbon dioxide emissions from new and existing coal- and gas-fired power plants, industrial processes, and other stationary sources of carbon dioxide. | [View](https://www.greenbuildinglawupdate.com/2022/06/articles/ghg/glossary-of-greenhouse-gas-terms/){:target="_blank"} |
| Carbon neutrality | Carbon-neutral (or carbon neutrality) is the balance between emitting carbon and absorbing carbon emissions from carbon sinks. Or simply, eliminate all carbon emissions altogether. | [View](https://www.google.com/){:target="_blank"} |
| GHG Mitigation | Any action that results, by design, in the reduction of greenhouse gas emissions by sources or removals by sinks. Mitigation and abatement are considered equivalent terms | [View](https://environment.govt.nz/publications/discussion-paper-on-measures-to-reduce-greenhouse-gas-emissions-in-new-zealand-post-2012/12-glossary/){:target="_blank"} |
| Feature Identifier	 | Identifier used to identify the feature. | [View](https://github.com/Datalinker-Org/Farm-Data-Standards/blob/master/Farm%20Features%20and%20Attributes/FFADS_Location-Identification_&_Spatial-Attributes.md#Location-Identification){:target="_blank"} |


