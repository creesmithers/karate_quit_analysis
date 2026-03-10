# Karate quit analysis

## Overview
This project compiles quit records from late 2016 until late 2025. The goal of this analysis is to find where quits are more likely to happen and as a result how to change instruction or where to focus instruction to retain as many students as possible, thus increasing revenue. 

## Tools
Pandas, Seaborn, collections, NumPy, PowerBi, Excel

## Dataset
The data contains information such as program, rank, age, attendance notes / notes, month and year quit. 

## Methods
- Cleaned differences in spelling and capitalizaion of programs and ranks
- Consolidated ranks for more accurate analysis

## Results
Found overall fewer quits at higher ranks with occasional spikes. Spikes occurred at: White, purple/blue, brown/black, and first degree.

## Actions recommended following results
- Have smaller beginner classes for more one-on-one instruction
- Change sparring curriculum at purple/blue belt to ease transitions
- Create earlier preperation classes for tests after brown/black
- Create clear goals and requirements after first degree

## Files
karate_quit_visual.pbix       - Power BI dashboard to visualize quit trends by rank and year
karate_quit_visual.pdf        - PDF export of Power BI Dashboard
quits_analysis.ipynb          - Jupyter notebook containing data cleaning, exploratory analysis, and explanations of steps. 
