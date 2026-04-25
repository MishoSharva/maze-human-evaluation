# Maze Human Evaluation Dataset

This repository contains the dataset and interface used in the paper:

"Perfect Orthogonal Procedural Maze Generation Algorithms: Human-Centric Evaluation"

## Contents

- interface/: Web-based maze solving interface
- data/solves.csv: Human solve-time dataset (5,244 solves)

## Description

Mazes were generated using six classical algorithms:
DFS, Prim, Kruskal, Aldous–Broder, Wilson, Hunt-and-Kill.

Each solve records:
- algorithm used
- maze size (8x8)
- solve time in milliseconds

## Reproducibility

The interface can be run locally by opening index.html in a browser.
And can be connected to Appscript Project to keep track of the data on Sheets.
