# Survival Analysis
Analyzing Lung Cancer Patient Data 

### Data
Columns  
**inst**:       Institution Code  
**time**:       Survival time in days  
**status**:     Censoring status 1=censored, 2=dead  
**age**:        Age in years  
**sex**:        Male=1, Female=2  
**ph.ecog**:    ECOG performance score as rated by the physician. 0=asymptomatic, 1= symptomatic but completely ambulatory, 2= in bed <50% of the day, 3= in bed > 50% of the day but not bedbound, 4 = bedbound  
**ph.karno**:   Karnofsky performance score (bad=0-good=100) rated by physician Karnofsky performance score as rated by patient  
**meal.cal**:   Calories consumed at meals  
**wt.loss**:    Weight loss in last six months     

### Dependencies
python3  
lifelines `pip install lifelines`  
pandas  