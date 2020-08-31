# Uganda APIs
This repo has information about Uganda written in JSON format. Depending on your development language (e.g JavaScript), you should be able to decode the JSON result to suit your need.

This repo needs loads of help to get to a really stable version. Check out the **How to contribute section**.

## Districts of Uganda
Based on English names published at [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-2:UG)

## Usage - Stable version
- [Districts](https://raw.githubusercontent.com/bahiirwa/uganda-APIs/master/districts.json)
- [Planned Districts -> Village](https://raw.githubusercontent.com/bahiirwa/uganda-APIs/master/districts_large_map.json)

## How to Contribute

### Non-Developers
- Improve the documentation of the project and usage.
- Update the current details of the geographical mapping.
- Suggest needed endpoints.
- Proposal of way forward for project.
- Converting the details from [District, County, sub-county, villages](https://raw.githubusercontent.com/bahiirwa/uganda-APIs/master/gismapping.md)

#### How to build the GIS Mapping file.
- Download and Unzip the [GIS-Parishes-2016.zip file](https://raw.githubusercontent.com/bahiirwa/uganda-APIs/master/GIS-Parishes-2016.zip)
- Install a GIS software like Google Earth
- Import the .gis file into Google Earth and pick the different places and add to the file.
- Always record the last entry you make with the Last Object ID number.

### Developers
- Proposal on converting the raw json to an admin centred API generator
- Converting the details from [District, County, sub-county, villages](https://raw.githubusercontent.com/bahiirwa/uganda-APIs/master/gismapping.md) into consumable JSON files.
- Suggest needed endpoints.
- Proposal of way forward for project.

## Testing Progress
* use Abim district as a test. it has relatively complete data like

` District : Abim -> County : Labwor -> Sub-county: Abim -> Parish: Atunga -> Sub-Parish: Atugo `

## Data Research

### Electoral Commission Statistics:
* No. of Districts: 122
* No. of Consistencies: 296
* No. of Sub counties: 1671
* No. of Parishes: 8386
* No. of Polling Stations: 28749
* No. of Villages: 60800
* No. of Voters: 17073493

## Information Credits
[Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-2:UG)

[Uganda Electoral Commission](https://www.ec.or.ug/)

[Africa Open Data](https://africaopendata.org/dataset/size-of-uganda-districts-in-square-kilometers/resource/ec5795f2-fb79-4f23-91ea-bad356aae555)

[District, County, sub-county ](https://www.ec.or.ug/sites/VoterCount/registration%20statistics2011.pdf)

[County, parish by district & sub-county](https://www.ec.or.ug/?q=2016-presidential-results-tally-sheets-district)
