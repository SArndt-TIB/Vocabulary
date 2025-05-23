:warning: THIS REPOSITORY IS A FORK!<br>
The fork has been created, to make some changes to the [Geochemical Analytical Methods Vocabulary](https://github.com/amds-ldeo/Vocabulary/blob/master/geochemistry/GeochemAnalyticalMethod.ttl) in order to import it into the [TIB Terminology Service](https://terminology.tib.eu/ts).<br>
These changes include:
* deactivate the import of dcterms: because this results in a missing import error on OLS4
* making skos:narrower relations explicit so that a term hierarchy view can be generated on TIB Terminology Service

Issues concerning this fork and the changes made here can be adressed [here](https://github.com/SArndt-TIB/Vocabulary/issues).

Issues concerning the contents and any of the other resources on this fork that were not changed, should be reported to the [original repository](https://github.com/amds-ldeo/Vocabulary/issues).

⬇️ From here on down, you find the content of the original repo's README.md: 

# What is here:
This repository is a workspace for developing and maintaining vocabularies to support interoperable sample-based analytical data from astromaterials. 

## Geochemistry folder
Vocabularies for for analytical techniques in geochemistry and cosmochemistry.  The directory contains SKOS vocabulary drafts, serialized using turtle (ttl). HTML versions are generated in the *html* folders in this repo using the scripts in the *scripts* folder on the pages branch.  The html is accessible on the github.io pages for the repo, links included in vocabulary descriptions.

### Analytical methods for geochemistry and cosmochemistry
Vocabulary of analytical techniques for analyzing Earth,  astronomic, and planetary materials. 
- [HTML view of Geochemical analytical methods vocabulary]( https://amds-ldeo.github.io/Vocabulary/geochemistry/html/GeochemAnalyticalMethod.html)
- Research Vocabularies Australia vocabulary service to access vocabulary; [landing page](https://vocabs.ardc.edu.au/viewById/650)
- SKOS vocabulary, serialized using Turtle. [SKOS Analytical Techniques vocabulary]( https://github.com/amds-ldeo/Vocabulary/blob/master/geochemistry/GeochemAnalyticalMethod.ttl)

### GeoXAnalyticalTechnique.ttl
SKOS vocabualary, serialized using Turtle. Based on Geo-X spreadsheet from Manja Luzi (GFZ Potsdam), with some general categories added to fill out the hierarchy. 
[GeoX Analytical Techniques vocabulary draft]( https://github.com/amds-ldeo/Vocabulary/blob/master/geochemistry/GeoXAnalyticalTechnique.ttl)

## Extraterrestrial materials folder (ETmaterials)

This folder contains development work for a vocabulary to classify types of meteorites and other extraterrestrial (ET) materials. Classes based on Meteorite Bulletin (MetBull) classes that were extracted into Mindat. Some MetBull classes are not included in Mindat and will be added. There are some lunar materials based on Apollo return samples, and links to a few terrestrial material classes that subsume the ET material.

### Extraterrestrial Materials classes
Vocabulary of categories of meteorites and lunar materials. 
- [HTML view of Extraterrestrial materials vocabulary]( https://amds-ldeo.github.io/Vocabulary/ETmaterials/html/ExtraterrestrialMaterialsMindat.html)
- SKOS vocabualary, serialized using Turtle. [SKOS Extraterrestrial materials vocabulary]( https://github.com/amds-ldeo/Vocabulary/blob/master/ETmaterials/ExtraterrestrialMaterialsMindat.ttl)

### Minerals
Draft vocabulary for mineral species. Information pulled from Wikipedia, RRUFF, and MinDat.  Includes hierarchy from Strunz classes and Mindat mineral groups. 
- [HTML view of Mineral vocabulary](https://geosamples.github.io/vocabularies/mineralSKOS.html).  This is a big file, takes awhile to load.
- [SKOS Turtle file, Mineral vocabulary draft](https://github.com/GeoSamples/vocabularies/blob/main/vocabulary/mineralSKOS.ttl).  Draft is in the vocabularies 
repo for geosamples.org. 
