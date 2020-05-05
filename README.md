# Mobile Games Analysis

Data Analysis workflow and study of Mobile Games data.

The study will cover 2 analysis with 2 different datasets. <br>
The first analysis will be done in Python while the second one will be done in R.



#### Analysis 1 - Insight Search

##### Analysis of special in-game events for players. These events tend to last 2 - 3 days and give users the chance to win special prizes and power ups. The event rules are as follows:

- The event is held on a different map to the main map. <br>
- The players can play the event as many times as they want, as long as they do it. <br>
during the event’s time period and they have lives available. <br>
- The map only has 5 levels. <br>
- The levels are played consecutively. After completing level 2, you can play level 3.<br>
- If you lose a level, you must go back to the start of the event - returning to level 1.<br>
- If a player completes level 5, the event will be considered ‘complete’ and the user will win a prize. <br>
- The player can use a power up at any moment, if they want to. <br>

##### Possible insights/questions:
- What percentage of users completed the event in comparison to the users who participated? <br>
- What can be said about the event’s difficulty? Do you think it was difficult or easy? <br>
- How were power ups used during the event? <br>
- Undertake an analysis of the current data and create a recommendation for the design of new event levels. <br>
- What analysis would you undertake if you had access to additional data? <br>

### About the data

###### event_levels.csv

- `user_id`: User identifier
- `client_time`: Timestamp when the event happened
- `action`: This can represent the following value:
- `action.game_start`: When a user starts a level
- `action.success`: When a user completes a level
- `action.fail`: When a user loses a level
- `action.use_powerup`: When a user uses a power up
- `level`: The level in which the action takes place
