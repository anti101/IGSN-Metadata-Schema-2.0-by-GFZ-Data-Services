This is a simplified mapping designed to provide a quick overview of the elements used. However, there are elements that are mapped to other elements in DataCite depending on their type. A fine-grained and precise mapping is not, however, the aim of Core and is only provided in sample-specific profiles using an XSLT.

| core position | IGSN Core by GFZ Dataservices| DataCite |
| :--: | :--: | :--: |
| 1       | `<identifier>`           |[`<identifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/identifier/#id1) | 
| 1.1     | `@identifierType`        | [@identifierType](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/identifier/#a-identifiertype) | 
| 2       | `<name>`                 | [`<title>` ](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/title/)|
| 2.1     | `@titleType`             | [@titleType](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/title/#a-titletype)  | 
| 2.2     | `@lang`                  | [ `xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/title/#lang-xml-lang) | 
| 3       | `<agents>`               | - |  `<contributers>` (ID 10) |
| 3.1     | `<contributor>` | [`<contributor>` ](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#contributor)  |
| 3.1.1   | `@contributorType`  |[`@contributorType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#a-contributortype)  |
| 3.1.2   | `<contributorName>`  | [`<contributorName>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#contributorname) |
| 3.1.2.1 | `@nameType` | [`@nameType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#a-nametype) | 
| 3.1.2.2 | `@lang` |  [`xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#lang-xml-lang) | 
| 3.1.3   | `<givenName>`  | [`<givenName>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#givenname) | 
| 3.1.4   | `<familyName>` | [`<familyName>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#familyname) | 
| 3.1.5   | `<nameIdentifier>`  | [`<nameIdentifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#nameidentifier) |
| 3.1.5.1 |  `@nameIdentifierScheme` | [`@nameIdentifierScheme`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#a-nameidentifierscheme) | 
| 3.1.5.2 | `@schemeURI`  | [`<schemeURI>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#a-nameidentifierscheme) |
| 3.1.6   | `<affiliation>` | [`<affiliation>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#affiliation) |
| 3.1.6.1 | `@affiliationIdentifier` | [`@affiliationIdentifier`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#a-affiliationidentifier) |
| 3.1.6.2 | `@affiliationIdentifierScheme`  | [`@affiliationIdentifierScheme`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#b-affiliationidentifierscheme) | 
| 3.1.6.3 | `@schemeURI`  | [`<schemeURI>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/contributor/#c-schemeuri) |
| 3.2     | `<publisher>`   | [`<publisher>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publisher/#publisher)   |
| 3.2.1   | `@publisherIdentifier` | [`@publisherIdentifier`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publisher/#a-publisheridentifier) |
| 3.2.2   | `@publisherIdentifierScheme`  | [`@publisherIdentifierScheme`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publisher/#b-publisheridentifierscheme)  | 
| 3.2.3   | `@schemeURI`  | [`<schemeURI>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publisher/#c-schemeuri) |
| 3.2.4   | `@lang` |  [`xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publisher/#lang-xml-lang)  |
| 4       | `<entityTypeClassifications>`   | - |
| 4.1     | `<resourceType>`  | [`<resourceType>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/resourcetype/)  |
| 4.1.1   | `@resourceTypeGeneral`  | [`@resourceTypeGeneral`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/resourcetype/#a-resourcetypegeneral)  |
| 4.2     | `<sampleTypeClassificationPlaceHolder>` |[ `<subjects>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#subject)   |
| 4.3     | `<material>` | [`<subject>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#subject) |
| 4.3.1   | `@subjectScheme`  | [`@subjectScheme`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#a-subjectscheme) | 
| 4.3.2   | `@schemeURI`  | [`@schemeURI`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#b-schemeuri)  |
| 4.3.3   | `@valueURI` | [`@valueURI`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#c-valueuri) |
| 4.3.4   | `@classificationCode` | [`@classificationCode`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#d-classificationcode) |
| 4.3.5   | `@lang` |  [`xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#lang-xml-lang)  |
| 4.4     | `<alternateMaterial>`   | [`<subject>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#subject) |
| 4.4.1   | `@subjectScheme`  | [`@subjectScheme`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#a-subjectscheme) | 
| 4.4.2   | `@schemeURI`  | [`@schemeURI`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#a-subjectscheme) | 
| 4.4.3   | `@valueURI` | [`@valueURI`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#c-valueuri) | 
| 4.4.4   | `@classificationCode` | [`@classificationCode`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#d-classificationcode) |
| 4.4.5   | `@lang` |  [`xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/subject/#lang-xml-lang) |
| 4.5     | `<description>` | [`<description>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/description/#description)   |
| 4.5.1   | `@descriptionType`  | [`@descriptionType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/description/#a-descriptiontype)  |
| 4.5.2   | `@lang` |  [`xml:lang`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/description/#lang-xml-lang)  |
| 5       | `<dates>`   | [`<dates>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/date/#date) |
| 5.1     | `<date>`  | [`<date>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/date/#date)  |
| 5.1.1   | `@dateType` | [`@dateType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/date/#a-datetype) |
| 5.1.2   | `@dateInformation`  | [`@dateInformation`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/date/#b-dateinformation)  |
| 5.2     | `<publicationYear>`   | [`<publicationYear>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/publicationyear/#publicationyear)   |
| 8       | `<relationshipIdentifiers>`   | [`<relatedIdentifiers>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#relatedidentifier) |
| 8.1     | `<alternateIdentifier>` | [`<alternateIdentifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/alternateidentifier/) |
| 8.1.1   | `@alternateIdentifierType`  | [`@alternateIdentifierType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/alternateidentifier/#a-alternateidentifiertype) |
| 8.2     | `<parentIdentifier>`  | [`<relatedIdentifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#relatedidentifier) |
| 8.2.2   | `@identifierType` | [`@relatedIdentifierType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#a-relatedidentifiertype) |
| 8.3     | `<relatedIdentifier>`   | [`<relatedIdentifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#relatedidentifier) | 
| 8.3.1   | `@relationType` | [`@relationType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#b-relationtype) |
| 8.3.2   | `@identifierType` | [`@relatedIdentifierType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/relatedidentifier/#a-relatedidentifiertype) |
| 9       | `<geoLocations>`  | [`<geoLocations>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/)  |
| 9.1     | `<geoLocationPlace>`  | [`<geoLocationPlace>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#geolocationplace)  |
| 9.1.1   | `@lang` | - |
| 9.2     | `<geoLocationPoint>` | [`<geoLocationPoint>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#geolocationpoint)  |
| 9.2.1   | `@coordinateSystem` | - |
| 9.2.2   | `<pointLongitude>` | [`<pointLongitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#pointlongitude) |
| 9.2.3   | `<pointLatitude>` | [`<pointLatitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#pointlatitude) | -  |
| 9.3     | `<geoLocationBox>`  | [`<geoLocationBox>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#geolocationbox)  | 
| 9.3.1   | `@coordinateSystem` | - | `@sridType` (ID 11.1.1.2)  |
| 9.3.2   | `<westBoundLongitude>`  | [`<westBoundLongitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#westboundlongitude)  | 
| 9.3.3   | `<eastBoundLongitude>`  | [`<eastBoundLongitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#eastboundlongitude)  |
| 9.3.4   | `<southBoundLatitude>`  | [`<southBoundLatitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#southboundlatitude)  |
| 9.3.5   | `<northBoundLatitude>`  | [`<northBoundLatitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#northboundlatitude)  |
| 9.4     | `<geoLocationPolygon>`  | [`<geoLocationPolygon>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#geolocationpolygon)  | 
| 9.4.1   | `<polygonPoint>`  | [`<polygonPoint>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#polygonpoint)  |
| 9.4.1.1 | `@coordinateSystem` | - | `@sridType` (ID 11.1.1.2)  |
| 9.4.1.2 | `<pointLongitude>`  | [`<pointLongitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#id13)  |
| 9.4.1.3 | `<pointLatitude>`   | [`<pointLatitude>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/geolocation/#id15) |
| 10      | `<fundingReferences>`   | [`<fundingReferences>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#fundingreference)   |
| 10.1    | `<fundingReference>`  | [`<fundingReference>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#fundingreference)  |
| 10.1.1  | `<funderName>`  | [`<funderName>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#fundername) |
| 10.1.2  | `<funderIdentifier>`  | [`<funderIdentifier>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#funderidentifier) |
| 10.1.2.1| `@funderIdentifierType` |[ `@funderIdentifierType`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#a-funderidentifiertype) | 
| 10.1.2.2| `@schemeURI`  | [`<schemeURI>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#b-schemeuri) | 
| 10.1.3  | `<awardNumber>` | [`<awardNumber>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#awardnumber) | 
| 10.1.3.1| `@awardURI` | [`@awardURI`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#a-awarduri) | 
| 10.1.4  | `<awardTitle>`  | [`@awardTitle`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/fundingreference/#awardtitle) |
| 11      | `<language>`  | [`<language>`](https://datacite-metadata-schema.readthedocs.io/en/4.7/properties/language/#language) |