# 🧑‍💼Guest Loyalty Predictor
A Python-based analysis tool that identifies high-potential guests for loyalty program enrollment.

Open notebook.ipynb in Jupyter or VS Code.

## Visual Insights
1. Loyalty Distribution            
We found that nearly 50% of our guests are not yet enrolled in any tier.
![Loyalty Distribution](images/Loyalty-Tiers.png)

2. Marketing Consent Overview               
The vast majority of guests are reachable via marketing channels.
![Marketing Consent](images/Marketing-Consent.png)

3. Relationship: Tier vs. Consent          
Critically, 157 guests in the "None" category have already provided consent—this is our primary growth target.
![Tier vs Consent](images/Loyalty-Tier-Marketing-Consent.png)

## Key Features / Insights
* Validated 400 rows of guest data with 0% duplicates.
* Visualized the relationship between loyalty tiers and marketing consent.
* Calculated a baseline Loyalty Enrollment Rate of 51.75%.

## Project Structure
A simple text tree showing what the files are.          

├── Images/     ---> Plots and charts for the README        
├── data/       --->                Raw and processed data               
├── notebooks/  --->                Jupyter notebook for analysis         
└── README.md



## Technologies Used
* Pandas for data manipulation.
* Seaborn/Matplotlib for visualization.
* Jupyter for interactive analysis.
