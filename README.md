# Alc-MPS-inhibition
Alcohol & Muscle Protein Synthesis Calculators

A modern, responsive web application to calculate total alcohol consumed (grams) from beverages and estimate muscle protein synthesis (MPS) inhibition based on alcohol dose and protein intake, using findings from Parr et al. (2014, PLOS ONE, link).

How to Use

Alcohol Consumption Calculator

This calculator computes the amount of alcohol (grams) in a beverage based on its volume and alcohol by volume (ABV) percentage.





Enter Beverage Details:





Volume (mL): Input the volume of the drink in milliliters (e.g., 330 for a 33cl beer).



ABV (%): Input the alcohol by volume percentage (e.g., 5.6 for 5.6% ABV).



Calculate:





Click the Calculate button to display the alcohol content (grams) for the current drink, calculated as Volume (mL) × ABV (%) / 100 × 0.789.



Manage Drinks:





+Save: Saves the drink’s details (volume, ABV, alcohol grams) to a list and updates the total alcohol consumed.



Clear: Resets the volume and ABV inputs without affecting saved drinks.



Delete: Removes a specific drink from the saved list by clicking the "Delete" button next to it.



View Total:





The total alcohol consumed (grams) from all saved drinks is displayed below the drink list and automatically populates the MPS Inhibition Calculator’s "Alcohol Consumed (g)" field.

MPS Inhibition Calculator

This calculator estimates the percentage of muscle protein synthesis (MPS) inhibition based on alcohol dose (g/kg fat-free mass) and protein intake, per the study’s findings.





Enter Inputs:





Fat-Free Mass (kg): Input your fat-free mass (e.g., from a DEXA scan or estimated as ~80–85% of body weight for active males).



Alcohol Consumed (g): Pre-filled with the total from the Alcohol Consumption Calculator but editable for manual input.



Protein Intake: Select "With 25g Whey Protein" or "Without Protein" from the dropdown.



Calculate:





Click Calculate MPS Inhibition to compute:





Alcohol Dose: Calculated as Alcohol Consumed (g) / Fat-Free Mass (kg) (g/kg FFM).



MPS Inhibition:





≤0.5 g/kg FFM: 0% inhibition.



0.5–1.5 g/kg FFM: Interpolated between 0% and 24% (with protein) or 37% (without).



1.5 g/kg FFM: Capped at 30% (with protein) or 45% (without).



Protein Recommendation: Suggests consuming 25 g whey protein post-exercise if not selected.



View Results:





Results display the alco