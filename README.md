World Cup Data - JSON
============

Files Included
----

* teams.json
* tournaments.json
* tournamentSummaries.json

Get Data
----
```sh
git clone 
cd worldCupData
```
Angular.js Service
----

Data Structure
----
- teams.json
```sh
{
  countryNameValue: {
    totalAppearances: totalAppearancesValue (int),
    appearances: [
       {
          year: yearValue (str),
          host: hostNameValue (str),
          result: resultValue (str)
       }
    ]
  }
}
```
