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
```sh
**teams.json**
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
