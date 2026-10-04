# DATA 620 Project 1: Congressional Network Analysis

## Overview

This project analyzes bill sponsorship and cosponsorship relationships among members of the U.S. House of Representatives during the 118th Congress. The data was collected from the official Congress.gov API.

Each representative is represented as a node. A connection is created when one representative sponsors a bill and another representative cosponsors it. Political party is used as the categorical variable.

## Project Objectives

- Calculate degree centrality for each representative
- Calculate eigenvector centrality for each representative
- Compare centrality scores between Democrats and Republicans
- Use Welch’s t-tests to determine whether the differences are statistically significant

## Key Findings

The network contains 448 representatives and 3,038 connections. Republicans had higher average degree centrality and eigenvector centrality than Democrats. The statistical tests showed significant differences between the two parties for both measures.

Garret Graves had the highest degree centrality, while Jeff Duncan had the highest eigenvector centrality.

## Files

- `DATA620_Project1_Congress_Network_Sachi_Kapoor.ipynb`: Complete analysis and visualizations
- `congress_centrality_results.csv`: Centrality results for every representative

## Tools Used

Python, Jupyter Notebook, pandas, NetworkX, SciPy, Matplotlib, and Seaborn

## Video Presentation

[Watch the project presentation](https://youtu.be/u1S6C_D-qwk)
