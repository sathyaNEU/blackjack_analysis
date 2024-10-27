# Blackjack Odds Analysis

This repository contains a comprehensive analysis of Blackjack odds using Power BI and Python. The goal is to explore player strategies, particularly focusing on the scenario of hitting with a total of 12 against a dealer's upcard of 10 or higher.

## Overview

Blackjack is not just a game of chance; it's a strategic battle between the player and the dealer. This analysis leverages data from over 1.2 million simulations to uncover the intricacies of the game, revealing how various player hands interact with dealer upcards.

## Key Findings

- The analysis reveals that hitting on 12 against a dealer's 10 provides a player win probability of **42.39%** on average.
- Players face odds that are nearly **20% lower than average**, highlighting the importance of strategic decision-making.
- The odds of winning vary significantly based on the dealer's upcard, with certain configurations providing a better chance for players.

## Tools Used

- **Python**: For conducting simulations and data analysis.
- **Power BI**: For visualizing data and presenting insights.

## Repository Structure

- `src/`: Contains Python scripts for simulations and calculations.
- `data/`: Includes the CSV file with simulation results.
- `powerbi/`: Power BI dashboard files for interactive data visualization.

## Getting Started

To run the analysis locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blackjack-odds-analysis.git

2. Navigate to the directory
     cd src
   
3. Open bj.ipynb in jupyyter/google colab or other runtime enviroments that supports ipynb extension

