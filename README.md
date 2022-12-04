# Canoe_technical_task
Technical task from Canoe

## Task Description

Using the given data on passing the levels of players in match3 games and the possibility of obtaining a task:

### Task 1

Assume a metric describing the levels of levels, and calculate it.

### Task 2

Based on the results of the tasks received, the levels are divided into groups according to complexity and conclusions are drawn about the distribution of difficult levels in the game.

### Task 3

Calculate the "funnel" of passing the levels of a new user after installing the game.

## Description of the files

The input data is the **plr_smpl_attempts.csv** file containing the event log for a certain period of time for the first 500 levels in the game.

The file contains four columns:

  - uid - unique player id;
  - action - 'completed' for a successful attempt to pass the level, 'failed' for an unsuccessful one;
  - level - the level at which the event occurred;
  - event_time - event_time/1000 is the unix timestamp of the time the event was received
