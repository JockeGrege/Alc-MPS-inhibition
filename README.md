
# Alcohol & Muscle Protein Synthesis Calculators

A responsive web tool to:

- Calculate **total alcohol consumed** (in grams)
- Estimate **muscle protein synthesis (MPS) inhibition** based on alcohol dose and protein intake  
Based on research from [Parr et al., 2014 (PLOS ONE)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0088392)

---

## Alcohol Consumption Calculator

### ➤ How to Use

1. **Enter Beverage Details**
   - **Volume (mL):** e.g., 330 for a beer
   - **ABV (%):** e.g., 5.6 for 5.6% alcohol

2. **Click Calculate**  
   - Formula: `Alcohol (g) = Volume × ABV / 100 × 0.789`

3. **Manage Drinks**
   - **+Save:** Add the drink to the list
   - **Clear:** Reset inputs
   - **Delete:** Remove a saved drink

4. **View Total**
   - Shows total alcohol (grams)
   - Automatically sent to MPS Calculator

---

## MPS Inhibition Calculator

### ➤ Inputs

- **Fat-Free Mass (kg):** e.g., 64 kg (usually ~80–85% of body weight)
- **Alcohol Consumed (g):** Auto-filled or manual
- **Protein Intake:**
  - "With 25g Whey Protein"
  - "Without Protein"

### ➤ Click “Calculate MPS Inhibition”

- **Alcohol Dose:** `Alcohol (g) / FFM (kg)`

### ➤ MPS Inhibition Results

| Dose (g/kg FFM) | With Protein | Without Protein |
|-----------------|--------------|-----------------|
| ≤ 0.5           | 0%           | 0%              |
| 0.5 – 1.5       | 0–24%        | 0–37%           |
| ≥ 1.5           | Max 30%      | Max 45%         |

**Protein Tip:** Add 25 g whey post-workout for better recovery.

---

## Output

- Alcohol dose per kg of FFM
- Estimated MPS inhibition %
- Protein recommendation if missing

---

Stay smart. Train hard. Drink responsibly. 
