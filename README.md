# DNN-for-Absenteeism

This project was carried out to predict if a given indivdual will be absent from wotk for more than 3 hours. 

The project result was then displayed using Tableau to carry out analysis
The steps and csv used are:
- **Preprocessing and Building ML model (the .ipynb file)** 
1. For data preprocessing - `Absenteeism_data.csv`.
2. The preprocsessed data used for the ML model - `Absenteeism_preprocessed.csv`.
3. The used Pickle to save the ML named `model` and the scaler (for data scaling) named `scaler`.
- **Absenteeism Module (the .py file)**
4. It contains all the class that would be used to load, clean, and predict the new Absenteeism data (the `Absenteeism_new_data.csv`).
- **Absenteeism Deploying the Absenteeism Module (the ipynb file)**
5. The `absenteesim_model.py` was loaded and used to create a csv file called `Absenteeism_predictions.csv`
- Tableau
6. The  `Absenteeism_predictions.csv` was analysed on Tableau (the link is: ) i.e. to explore the inputs that seem to be most important according to our model.
