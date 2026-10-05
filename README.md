# Race the Replay
An interactive jumbotron fan experience built for the 2026 SMT Data Challenge.

## Demo
Live app: https://adfoster234.github.io/race-the-replay/scoreboard.html

## Overview
Race the Replay transforms Minor League Baseball player tracking data into 
an interactive scoreboard game. Fans watch an animated replay of a big play 
and guess how long it took a key runner to reach a target base.

## Tech Stack
- R (arrow, tidyverse, jsonlite) for data processing
- HTML/JavaScript for the scoreboard app

## Files
- scoreboard.html — full scoreboard and fan interface
- SMT_Analysis.Rmd — complete analysis pipeline
- SMT_Setup.R — data loading and helper functions
- play*.json — tracking data for each featured play
