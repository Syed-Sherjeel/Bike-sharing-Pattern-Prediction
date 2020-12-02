# Bike-sharing-Pattern-Prediction
A bicycle company wants to take a decision wether their is a requirement to buy additional bicycles or not.Company also wants to know when their is a high demand for bicycles to comprehend whole supply chain.This will enable company to make better decision such as renting extra bikes/employees during peak time.
# Getting started
First we will download required dependencies to get started with this project
```
pip install numpy
pip install sklearn
pip install matplotlib
pip install pandas
```
Now your setup is ready for running this project.
# Outcome
<img src="Outcome.png" width=750px>
This model appears to be performing well in central 10 days of month but it performs very poorly on last 10 days on month.
The reason could be obvious.This dataset contains a lot of salaryman whose salary runs out at the end of month so actual spike was less then predicted spike.Because model memorizes this trend of initial days where salaryman have more money os they can rent out cycle hence predicted and actual both spikes are high. 
                                                                                                                 
# License
This project is licensed under [MIT License]('https://choosealicense.com/licenses/mit/')
