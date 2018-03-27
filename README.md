# ICA4

Q1: Rank the players' height from highest to lowest

```sql
SELECT player_name, height
FROM datasets.college_football_players
ORDER BY height DESC
```
![ICA4-1](Visualization/ICA4-1.png)

Q2: Rank the players' weight from highest to lowest

```sql
SELECT player_name, weight
FROM datasets.college_football_players
ORDER BY weight DESC
```
![ICA4-1](Visualization/ICA4-2.png)

Q3: Rank the players' height from highest to lowest in Junior yr student

```sql
SELECT player_name, height
FROM datasets.college_football_players
WHERE year = 'JR'
ORDER BY height DESC
```
![ICA4-1](Visualization/ICA4-3.png)

Q4: In Ohio state, rank the ID from lowest to highest

```sql
SELECT player_name, state, id
FROM datasets.college_football_players
WHERE state = 'OR'
ORDER BY id ASC
```
![ICA4-1](Visualization/ICA4-4.png)

Q5: In the position QB, rank the id from lowest to highest

```sql
SELECT player_name, position, id
FROM datasets.college_football_players
WHERE position = 'QB'
ORDER BY id ASC
```

![ICA4-1](Visualization/ICA4-5.png)

