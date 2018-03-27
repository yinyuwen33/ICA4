# ICA4

Q1

```sql
SELECT player_name, height
FROM datasets.college_football_players
ORDER BY height DESC
```
![ICA4-1](Visualization/ICA4-1.png)

Q2

```sql
SELECT player_name, weight
FROM datasets.college_football_players
ORDER BY weight DESC
```
![ICA4-1](Visualization/ICA4-2.png)

Q3

```sql
SELECT player_name, height
FROM datasets.college_football_players
WHERE year = 'JR'
ORDER BY height DESC
```
![ICA4-1](Visualization/ICA4-3.png)

Q4

```sql
SELECT player_name, state, id
FROM datasets.college_football_players
WHERE state = 'OR'
ORDER BY id ASC
```
![ICA4-1](Visualization/ICA4-4.png)

Q5

```sql
SELECT player_name, position, id
FROM datasets.college_football_players
WHERE position = 'QB'
ORDER BY id ASC
```

![ICA4-1](Visualization/ICA4-5.png)

