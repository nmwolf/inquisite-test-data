# inquisite-test-data

Test data for Inquisite (data has been validated for structure and content, but not finalized for use for analysis).

**Wilson 1852 Directory Data**

 - wilson-perris-matched-v4.json: Business/occupation entries from the 1852 NYC Business Directory with OCR validating information and occupational groupings. Each json record ("records") can contain up to six addresses, and each, where possible, have been matched to a building footprint coordinate from Perris Fire Insurance maps data provided by NYPL.
 
 - wilson-perris-matched-v4-metaflag.json: Same file as json file above, but with a record metadata set of elements added on to the json object to identify the non-digital source. These consist of "title" and "sourceOCLC" elements in addition to the "records" element.
 
 - wilson-perris-matched-v4.geojson: Same data, but in a FeatureCollection geojson format.
 
**Municipal Archives**

 - bodies-transit-inquisite.csv: Records of the NYC municipal archives containing names of deceased, occupation, place and date of death, etc.
 
**NYU Fales**

 - downtown-nyc-venue-inquisite.csv: Ongoing composite information on post-1950s music/art venues in NYC
