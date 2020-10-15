# FIFA 19 Exploration

## Dataset

This [dataset](https://www.kaggle.com/karangadiya/fifa19) contains detailed attributes for every player registered in the latest edition of FIFA 19 database.

## Table of contents

- [Project Motivation](#project-motivation)
- [Before Starting](#before-starting)
- [Summary of Findings](#summary-of-findings)
- [Key Insights](#key-insights)
- [Author](#author)
- [Copyright and License](#copyright-and-license)

## Project Motivation

The goal of this presentation is to answer some intriguing questions about FIFA 19 players. Some of which are:

- Which positions do football players play in the most?
- Which clubs have the top 100 world class players?
- Which clubs pay the highest salaries?
- On average, who has a higher value, a left or a right foot player?
- How are the skill moves distributed between left and right foot players?
- Do a player height and weight affect his balance?
- How can ball control affect the player dribbling skills? Are those releated to the skill moves?
- For each player role, how does the player positioning affect his finishing skills? Does the player skill moves and international reputation affect the previous results?

## Before Starting

Before starting the exploration process, some data wrangling steps were performed. Those can be summerized as follows:

- Drop unwanted columns
- Drop rows with so much missing values
- Make sure that the correct data format is given for each column.
- Convert prices, height, and weights to numeric values and removing their units.

## Summary of Findings

After exploring the dataset, we can summerize our findings as follows:

- Players age, overall rating, weight and height almost follow a normal distribution curve while the release clause, value and wage columns show a right skewed graph.

- The striker position (ST) has the most players followed by the goal keeper position (GK) while the least positions are the RF and LF.

- There are more than 3 times right foot players than left foot ones.

- The majority of the players have skill moves rating of 2 out of 5, while those with the maximum skill moves rating (5) are the least, which can be a reason to increase their value or overall rating.

- Real Madrid has the highest number of top class players, which is 11 players, followed by Juventus, FC Barcelona, and Manchester City, who all have 10 top class players.

- Real Madrid pays the highest salaries, followed by FC Barcelona, then Juventus, and Manchester City.

- There is an exponential relationship between the Potential and Release Clause column indicating that the more potential a player has, the harder it is for his club to let him go, thus increasing his release clause exponentially.

- The Overall vs Wage plot shows an exponential relationship which is expected because better players are supposed to have higher salary. It is also clear that most players have an income below €150,000 and only few of them receive higher wage since only few of them have high overall rating.

- For the Height vs Value graph, a normal distribution curve is seen, showing that players with height between 170 and 185 cms approximately tend to have higher value. This may be due to the balance between the player height and stability, since the taller the player is, the less stable he will be, and the shorter the player is, the lower his jumping or heading might be.

- The Weight vs Height graph shows a linear relationship indicating that as the player's height increases, his weight also increases, which is expected.

- Left foot players on average have higher value than right foot players.

- Both left and right foot player show almost the same overall rating distribution.

- Although the RF, LF, LAM, RAM positions have the highest wages, they have the highest errors or standard deviation, this is because we saw in our univariate exploration that they have the least number of players.

- There is a slight difference between the skill moves levels when they are compared to the age variable.

- Higher skill moves will result in a higher overall rating.

- Left foot players are generally more skilled than right foot ones.

- Players with high balance tend to be short and light, while tall and heavy players tend to have less balance.

- There is a linear relationship between the dribbling and the ball control skills.

- Players with low dribbling and ball control have lower skill moves, and those with high dribbling and ball control skills have high skill moves.

- There is generally a linear relationship between the player positioning and his finishing skills, the better a player can position himself, the more chances he can get to score goals. This linear relationship increases as the skill moves category increases. This event also occures as the player role changes, so for the defence role, the linear relationship is weak, then it is stronger in the midfield role, and is strongest in the attacking role.

- The international reputation increases with the increase in skill category, as seen by reduction in the blue color, and with the increase in positioning and finishing.

## Key Insights

- Best clubs to play for in terms of salary and world class players.
- Skill moves distribution for left and right foot players.
- Factors that affect player's balance.
- Ball control effect on dribbling skills and skill moves.
- Other kills to be developed for a player to have high finishing skills.

## Author

### Ahmad Sherief

- [linkedin.com/in/ahmadsherief/](https://www.linkedin.com/in/ahmadsherief/)
- [github.com/AhmadSherief](https://github.com/AhmadSherief)

## Copyright and License

Code is released under the [MIT License](https://github.com/AhmadSherief/Boston-Airbnb-Data-Analysis/blob/master/LICENSE).
