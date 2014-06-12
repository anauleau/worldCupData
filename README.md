World Cup Data - JSON
============
Get Data
----
```sh
git clone 
cd worldCupData
```
Files Included
----
* teams.json
* games.json
* tournamentSummaries.json

teams.json structure
----
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
tournamentSummaries.json structure
----
```sh
{
  tournamentYearValue: {
    host: hostNameValue (str),
    summary: {
      totalGoals: totalGoalsValue (int),
      matchesPlayed: matchesPlayedValue (int),
      attendance: attendanceValue (int)
    },
    teams: [
      participantTeamName (str),
      participantTeamName (str)
    ],
    results: {
      champion: championTeamNameValue (str),
      second: secondTeamNameValue (str),
      third: thirdTeamNameValue (str),
      fourth: fourthTeamNameValue (str),
      quarters: [
        quartersTeamName (str),
        quartersTeamName (str)
      ],
      roundOf16: [
        roundOf16TeamName (str),
        roundOf16TeamName (str)
      ],
      group: [
        groupTeamName (str),
        groupTeamName (str)
      ]
    }
}
```
