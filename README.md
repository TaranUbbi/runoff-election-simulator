# Runoff Election Simulator

A C program that simulates a ranked-choice runoff election system where voters rank candidates by preference.

## Description

This project models an instant runoff voting election. If no candidate wins a majority in the first round, the lowest-ranked candidate is eliminated and votes are redistributed until a winner is found.

## Features

- Supports ranked-choice voting
- Eliminates lowest candidates each round
- Detects ties
- Recalculates vote totals dynamically

## Tech Used

- C
- CS50 Library

## What I Learned

- Structs in C
- Multi-dimensional arrays
- Election algorithm logic
- Candidate elimination systems

## How to Run

1. Compile:
gcc runoff.c -o runoff -lcs50

2. Run:
./runoff Alice Bob Charlie
