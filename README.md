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
- Croatia is the most resilient team in knockout rounds
- Germany shows the highest combination of volatility and resilience
- Spain's tiki-taka era produced the most psychologically stable profile
- Brazil's collapse tendency is real but moderate — not as extreme as perception suggests

## Tools
Python · pandas · matplotlib · scikit-learn · Google Colab

## How to Run
1. Open the notebook in Google Colab
2. The dataset loads automatically via kagglehub
3. Run all cells in order
