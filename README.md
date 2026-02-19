# shark_tank_india-analysis

I did a basic analysis on two shark tank datasets.
I merged the two datasets - shark_tank_india_pitches.csv — pitch-level data (pitch number, ask amount, deal amount, etc.)
shark_tank_india_sharks.csv — shark-level data (which sharks were present, which closed a deal per episode)

Loading and merging the two datasets on pitch_number
Comparing merge methods (join vs. merge) and verifying equivalence
Exploratory analysis — df.info(), df.describe()
Feature engineering — creating a deal_difference column (ask amount minus deal amount)
Outlier detection using IQR (Q1, Q3, lower/upper bounds) and filtering
Shark participation rates — raw vs. presence-adjusted rates per shark

This was a different dataset from what I have worked on. Different from the type of data and how it is stored. Names of the shark, episodes they were present in, deals they aquired for how much. 

Additionally this data had outliers which were removed when needed. 
