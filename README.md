# ⚽ Psychological Pressure in the FIFA World Cup (1930–2022)

## Overview
Got inspired during the World Cup games and decided to do some analysis on how teams have managed psychological pressure historically.
This project proposes two custom indices built from match event data to mesure psychological damage & response.

## Indices

### CCI — Collapse Control Index
Measures how often a team concedes goals in high-pressure moments:
- Goals conceded in the last 10 minutes of regular time
- Goals conceded during extra time (90–120 min)
- Goals conceded in quick succession (< 10 min apart)

Higher CCI = more psychologically stable (inverted scale)

### PCR — Pressure Conversion Rate
Measures how often a team converts adverse situations into positive outcomes:
- Was behind in a penalty shootout and won
- Conceded the first goal but won the match
- Was 2+ goals behind and managed to draw or win

Higher PCR = more resilient under pressure

## Dataset
FIFA World Cup match data 1930–2022 from Kaggle  
Source: https://www.kaggle.com/datasets/piterfm/fifa-football-world-cup

## Key Findings
- Croatia — most stable and resilient team in modern football. Their penalty shootout record is not a coincidence.
- Belgium — biggest transformation between eras, from mediocre to one of the best mental profiles in recent World Cups.
- Germany — ultimate comeback team in the old era, more controlled but rigid in modern football. Less chaos, less magic.
- Spain — consistently stable across both eras, rarely in danger but also rarely fights back when needed.
- Brazil — well positioned in the old era, lost almost all resilience in modern football. The shift is real.
Overall — football became much more controlled. Teams collapse less, but also come back less.

## Explore It Yourself
The code is built with configurable filters — you can easily adjust (in # define what will be plotted cell):
Year range — compare any two eras you define
Round type — knockout rounds only, group stage only, or all rounds combined
Teams to display — add or remove any team from the scatter plot
Minimum matches threshold — control how many matches a team needs to appear in the analysis

## Tools
Python · pandas · matplotlib · scikit-learn · Google Colab

## How to Run
1. Open the notebook in Google Colab
2. The dataset loads automatically via kagglehub
3. Run all cells in order
