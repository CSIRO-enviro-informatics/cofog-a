# COFOG-A in RDF
This code repository contains am [RDF](https://www.w3.org/RDF/) representation of the  Classification of the functions of government - Australia (COFOG-A). The COFOG-A data is from the [Australian Bureau of Statistics](http://www.abs.gov.au)' [Australian System of Government Finance Statistics: Concepts, Sources and Methods](http://www.ausstats.abs.gov.au/ausstats/subscriber.nsf/0/418BDDEBD088A012CA257F230019D433/$File/55140_2015.pdf) and in an Australian-specific version of UN's [COFOG](https://unstats.un.org/unsd/iiss/Classification-of-the-Functions-of-Government-COFOG.ashx).


## Repository Contents
This repository contains the following files:

* [README](README.md) - this file
* [LICENSE](LICENSE) - the deed of the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/)
* [55140_2015.pdf](55140_2015.pdf) - a copy of the PDF document [Australian System of Government Finance Statistics: Concepts, Sources and Methods](http://www.ausstats.abs.gov.au/ausstats/subscriber.nsf/0/418BDDEBD088A012CA257F230019D433/$File/55140_2015.pdf) from which this COFOG-A data is taken
* [cofog.ttl](cofog.ttl) - a copy of the international COFOG vocabulary (from <http://registry.it.csiro.au/def/agldwg/cofog>) for reference
* **[cofog-a.ttl](cofog-a.ttl) - this COFOG-A vocabulary in RDF**
  * this file is a concatenation of [conceptScheme.ttl](conceptScheme.ttl), [data.ttl](data.ttl) & [broaders.ttl](broaders.ttl), reformatted using <http://rdf-translator.appspot.com/>
  * [data.xlsx](data.xlsx) - an Excel spreadsheet used to create RDF statements from the data taken from Appendix C tables in [55140_2015.pdf](55140_2015.pdf)
  * [data.ttl](data.ttl) - RDF data from [data.xlsx](data.xlsx)
  * [conceptScheme.ttl](conceptScheme.ttl) - just the Concept Scheme information in RDF
  * [broaders.ttl](broaders.ttl) - broader RDF statements from [data.xlsx](data.xlsx)


## Rights & License
The content of this repository is licensed for use under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) all details.

Please note that the content of COFOG-A itself is derived from the [Australian Bureau of Statistics](http://www.abs.gov.au)' [Australian System of Government Finance Statistics: Concepts, Sources and Methods](http://www.ausstats.abs.gov.au/ausstats/subscriber.nsf/0/418BDDEBD088A012CA257F230019D433/$File/55140_2015.pdf).


## Contacts
*Product owner:*  
**Australian Bureau of Statistics**  

*Technical contact:*  
**Nicholas Car**  
CSIRO Land & Water, Environmental Informatics Group  
<nicholas.car@csiro.au>  
