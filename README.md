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
games.json structure
----
```sh
  {
    date: dateValue (str),
    tournament_year: tournament_yearValue (int),
    time: timeValue (str),
    location: locationValue (str),
    attendance: attendanceValue (int),
    stage: stageValue (str),
    team_1: team_1Value (str),
    team_1_goals: team_1_goalsValue (int),
    team_2: team_2Value (str),
    team_2_goals: team_2_goalsValue (int),
    overtime: overtimeValue (bool),
    penalties: penaltiesValue (bool),
    team_2_penalties: team_2_penaltiesValue (int),
    team_1_penalties: team_1_penaltiesValue (int),
    stage_details: stage_detailsValue (str)
  }
```
  
