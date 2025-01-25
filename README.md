# chess-analysis

This project was originally a project completed for my class, Independent Research DS-UA 301-004, in my Fall 2024 semester at NYU. Motivated primarily by understanding how long chess players think, I created some questions that I found interesting and answered them using Lichess's Open Data Catalog and Python. I worked on this project under Professor Carlos Fernandez-Granda from Courant. 

Near the end of the semester, I also created a presentation to share my findings, for which I selected only a few of my findings and which I have also uploaded to this repo. I presented my results to an audience not necessarily assumed to have a background in chess, so I presented my findings with this in mind. However, after the semester ended but before I was able to move the notebooks to Github, my files were wiped off the university machine that I was working on. As a result, I am working on recovering my previous findings, filtering for the most interesting results first, and expanding on my previous analyses using new sub-questions.

# Table of Contents
The below captures the questions that I have answered, by question number. All of these results are merely observational in nature, not causal.
1. How do the distributions of thinking time differ between moves that are blunders and moves that are not?
2. What is the relationship between time spent thinking and the change in evaluation caused by the move?
3. Do more experienced players spend more time thinking?
4. How often do players who make the first check win the game?
5. Do more experienced players keep their queens on the board for longer?
6. How do blunder rates vary during a game?

The following also demonstrates the breakdown of particular sub-questions for each overarching question topic. The Jupyter notebook for each question also contains the code and diagrams relevant to the sub-questions as well.

Question 1. How do the distributions of thinking time differ between moves that are blunders and moves that are not?
- 1.1 Given a time spent thinking, what is the likelihood that the resulting move is a blunder?
- 1.2.1 What if we stratify on elo?
- 1.2.2 What if we stratify on board evaluation?
- 1.2.3 What if we stratify on the amount of time remaining that the player has on their clock?

Question 2. What is the relationship between time spent thinking and the change in evaluation caused by the move?
- No sub-questions.

Question 3. Do more experienced players spend more time thinking?
- 3.1 Do more experienced players play games that last more moves?
- 3.2 Do more experienced players spend more time thinking per move?
- 3.2.1 Is the average amount of time spent per move independent of the number of moves?
- 3.3 Do more committed players play games that last longer?

Question 4. How often do players who make the first check win the game?
- 4.1.1 Is the result consistent upon stratification on time control?
- 4.1.2 Is the result consistent upon stratification on elo?
- 4.2.1 How often is the first check also linked with the end of the game?
- 4.2.2 How often is the first check used as a last ditch effort?

Question 5. Do more experienced players keep their queens on the board for longer?
- 5.1.1 Are players who kept their Queen more likely to have a higher elo?
- 5.1.2 Are more experienced players more likely to keep their Queens until the end of the game?

Question 6. How do blunder rates vary during a game?
- No sub-questions.

Question 7. Is playing a check a symbol of being on the offensive or on the defensive?
- 7.1.1 How is the relative board evaluation distributed among moves that are checks?
- 7.1.2 How often is a check followed up by another check (by the same or opposing player)?
- 7.2 How is the number of checks in a game correlated with the number of plies in the game?
- 7.3 Do players play more checks when they are under time pressure?
- 7.4 How is the number of checks correlated with the elos and elo difference between the two players?
- 7.5 Do players check more often when in a disadvantageous position?

Question 8. Which pieces are used to deliver a check or checkmate most often?

# Acknoledgements
Special thanks to Professor Carlos Fernandez-Granda for his invaluable advice over the course of the project, as well as to the team at the University of Toronto's Computational Social Sciences Lab for their work in partially preprocessing the Lichess data into CSV format.

## Links
- https://csslab.cs.toronto.edu/datasets/#maia_kdd
- https://database.lichess.org/
