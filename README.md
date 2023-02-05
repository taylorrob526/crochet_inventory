# sql_projects
A collection of SQL files for my various projects


CREATE TABLE card_games(id INTEGER PRIMARY KEY AUTOINCREMENT,
    date_played TEXT,
    game_name TEXT,
    player_name TEXT,
    score INTEGER);
    
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/07','Rummy','Spunky Sam',226);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/07','Rummy','Marcimus',418);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/07','Rummy','Winston',523);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/07','Rummy','Hopper',311);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Go Fish','Spunky Sam',7);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Go Fish','Marcimus',5);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Go Fish','Winston',4);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Go Fish','Hopper',10);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Crazy Eights','Spunky Sam',215);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Crazy Eights','Marcimus',167);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Crazy Eights','Winston',109);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/14','Crazy Eights','Hopper',192);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/21','Rummy','Spunky Sam',473);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/21','Rummy','Marcimus',324);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/21','Rummy','Hopper',516);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/28','Crazy Eights','Spunky Sam',119);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/28','Crazy Eights','Marcimus',212);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/28','Crazy Eights','Purple Pi',314);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/01/28','Crazy Eights','Hopper',252);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Go Fish','Spunky Sam',3);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Go Fish','Marcimus',11);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Go Fish','Winston',12);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Go Fish','Hopper',0);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Pitch','Spunky Sam',17);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Pitch','Marcimus',22);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Pitch','Winston',-3);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/04','Pitch','Hopper',9);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/11','Rummy','Amelia',525);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/11','Rummy','Marcimus',419);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/11','Rummy','Winston',316);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/11','Rummy','Hopper',398);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/18','Crazy Eights','Spunky Sam',119);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/18','Crazy Eights','Marcimus',231);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/18','Crazy Eights','Winston',153);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/18','Crazy Eights','Hopper',175);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Pitch','Spunky Sam',12);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Pitch','Marcimus',6);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Pitch','Winston',21);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Go Fish','Spunky Sam',6);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Go Fish','Marcimus',7);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/02/25','Go Fish','Winston',13);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/04','Rummy','Spunky Sam',378);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/04','Rummy','Marcimus',327);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/04','Rummy','Winston',413);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/04','Rummy','Hopper',517);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/11','Pitch','Spunky Sam',-1);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/11','Pitch','Marcimus',-5);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/11','Pitch','Winston',7);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/11','Pitch','Hopper',22);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/18','Crazy Eights','Spunky Sam',91);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/18','Crazy Eights','Marcimus',153);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/18','Crazy Eights','Amelia',174);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/18','Crazy Eights','Mr. Pink',216);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/25','Rummy','Spunky Sam',416);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/25','Rummy','Marcimus',505);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/25','Rummy','Winston',397);
INSERT INTO card_games(date_played,game_name,player_name,score) VALUES ('2015/03/25','Rummy','Hopper',443);
    
SELECT * FROM card_games;

/* Looking at average, max and min scores*/

SELECT AVG(score), MAX(score), MIN(score) FROM card_games;

/* Average date played by player name with scores > 400 */

SELECT AVG(date_played) AS avg_date_played, 

FROM card_games

GROUP BY player_name

HAVING score > 400;

/* Displaying and grouping by player names with total scores >1000 */

SELECT player_name, SUM(score) as total_score FROM card_games GROUP BY player_name 
HAVING total_score > 1000;

/* Displaying the number of times the scores were >=100 and <=300*/

SELECT score, COUNT (*) FROM card_games WHERE score >=100 AND score <=300; 

/* Creating a gamer_experience level based on score and grouped by player name*/
SELECT player_name, score,
CASE 
WHEN score <=200 THEN "beginner"
WHEN score >=350 THEN "advanced"
ELSE "average"
END AS "gamer_experience_level"
FROM card_games
GROUP BY player_name;

/*Displaying player names and scores where based score and dates played*/

SELECT player_name, score FROM card_games WHERE score > 200 AND date_played > "2015/03/04";

/* Displaying player names, game names, and scores based on score grouping by games*/

SELECT player_name, score, game_name FROM card_games WHERE score <100 OR score >300 
GROUP BY game_name; 












