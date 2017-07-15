# TableTennisSkill

Some random thoughts
```
Table Tennis Skill

//# Kent beat Stephen by 2-1
ReportScoreIntent {Player1} beat {Player2} by {Player1Score} {Player2Score}

//# Stephen won the first game against Kent by 11-5
ReportGameIntent {Player1} won the {first|second|third} game against {Player2} by {Player1Score} {Player2Score}

//# Kent won game 2 against Stephen by 13-11
ReportGameIntent {Player1} won game {1|2|3} against {Player2} by {Player1Score} {Player2Score}

//# What is Kent's standing?
QueryRankingIntent What is {Player}'s standing?
QueryRankingIntent What is {Player}'s ranking?
QueryRankingIntent What is the ranking of {Player}?

// --- Chatbot

//# Kent is starting a game against Stephen
// -- Good luck X, you can do it this time. (if Y has higher vs score)
// -- Always exciting with even games
// -- May the best player win! (gender neutral, always)
// -- Do you mean Kent Karlsson vs Stephen Han?

//# Stephen won the first game by 11-5
//# Kent won the second game by 13-11
//# Kent won the last game by 11-6
// -- Congratulations {Player}, well done!
// -- Congratulations {Player}, good comeback!
```
