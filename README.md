# AH Computing Science Project
This is a project I created for the coursework part of Advanced Higher Computing Science 2023/24.
It follows the recommended guide for AH CS projects which can be found on the SQA website.

This project was created using Livecode, a english-like syntax based programming language designed for easy implementation of full stack development, meaning I was able to create a professional looking UI along with having a sophisticated backend  to support it. Although not my most efficient work, this project submission was sufficient enough to get me a very good mark for the coursework part of this course.

In order to run this project, you must have an up-to-date licensed (or earlier unlicensed version) of Livecode (version 9.0.0+) installed and ideally a program to view SQLite databases (although not required).

Examples of this include:
- DB Browser for SQLite
- DBeaver

This project will not receive any further support or updates past March 2024, and complete intended functionality is not guaranteed, the purpose of this is simply to store the code and report if I ever require it again.

## Game

This program  uses cards from EA FC 24 to create a game which the user can play. The game is based on Higher/Lower, a game where you are given a search term and have to guess if the next search term has more or less monthly searches.

In this game, you are given a player's card from EA FC 24. You are then given hints as to what the next card will be (nation, club, position), as well as the individual statistic that it is referring to. 

Individual statistics consist of either one of these:
- Pace (PAC)
- Shooting (SHO)
- Passing (PAS)
- Dribbling (DRI)
- Defending (DEF)
- Physicality (PHY)

An example of what is asked to the user:
> Will the DEF on the next card be higher or lower?

The user has to use the hints given to them to determine what the next card is and if the given statistic is higher or lower on the next card.
If they are correct, a point is added. If they are incorrect, the game is over.
The user is given the option to save their score, and if it is in the top 10, it is displayed on the leaderboard alongside their username.
A user can also save login credentials (username and password) to try and beat their score another time, or login as a guest where progress is not saved.