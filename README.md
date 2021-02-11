# nba_shot_analysis

## Description
An exploratory analysis of 3pt shooting percentage during the 2014-2015 NBA Season. Specificially this analysis looks 3pt shooting percentage vs average distance of closest defender.

## Dataset
NBA shot log dataset from https://www.kaggle.com/dansbecker/nba-shot-logs. This dataset contains a collection of shots data from the 2014-2015 NBA Season. Analyzed data from the dataset includes "PTS_TYPE", "player_name", "SHOT_RESULT", "CLOSE_DEF_DIST".

## Discussion
![3pt Shooting Avg vs Closest Defender Avg Distance](https://github.com/ehrlichj/nba_shot_analysis/blob/master/images/chart1.png)

One thing that we should notice when looking at our resulting graph is the are blue points which appear above some of gold points. This should be impossible to occur since this would suggest that one of the blue points is would in fact be a Top 15 Shooter. This could be explained by our inital dataset being incomplete and missing some data. I assume this to be true since the Top 15 shooter list was taken from "basketball-reference.com" a reliable source on the subject.

Some other important points to note are two outliers that we see in the graph representation of our data. The first is the most vertical gold point. This point which appears to have almost .05 shooting pct better than anyone else is in fact Kyle Korver. In the 2014-15 season, Kyle Korver's 3pt shooting percentage was the 9th best of all time (basketball-reference.com). Even more impressively his 3pt shot attempts had less than the average amount of defenseive distance per shot than the average 3pt shot attmept in the league.

The last point of discussion is the most horizontal point which appears to be an outlier in terms of the average distance of the closest defender during his 3pt shot attempt. This player is Harrison Barnes and in the following year both his 3pt Field Goal percetage dropped as did his number of attempts. This might imply that in the following year teams began to defend him closer to the league average and as a result his stats dropped. A possible reason for why he was not guarded as closely as the league average is that two of the other top 15 shooters in the league where his teammates: Steph Curry and Klay Thompson.
