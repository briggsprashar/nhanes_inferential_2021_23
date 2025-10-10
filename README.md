# Inferential-Stats
## Project

This is a Google Colab based Python project that exlores the relationship between various variables in a NHANES dataset. 

<details>
<summary>Steps</summary>  
<br />

- Data loading and preperation
  - Clean data before performing analyses
    - Categorical variables: check and document frequency counts to confirm data consistency
    - Continuous variables: check for placeholder values (7777, 9999) and handle these as appropriate (e.g., by removing or imputing)
- Analysis and/or transformations
- Visualizations (where relevant)
- Brief summaries
- Code, results, and any explanations are documented clearly within the notebook.
  
</details>

## Analyses

<details>
<summary>1. Marital Status</summary>  
<br />

> Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)"

Variables: DMDMARTZ (marital status) and DMDEDUC2 (education level). Recode as specified.
  
</details>
<br />

<details>
  <summary>2. Mean Sedentary Behavior</summary>  
<br />

> Is there a difference in the mean sedentary behavior time between those who are married and those who are not married??

Variables: DMDMARTZ (marital status, recoded) and PAD680 (sedentary behavior time, cleaned).
  
</details>
<br />

<details>
  <summary>3. BP Systolic </summary>  
<br />

> How do age and marital status affect systolic blood pressure?

Variables: RIDAGEYR (age), DMDMARTZ (marital status, recoded), and BPXOSY3 (systolic blood pressure).


</details>
<br />

<details>
  <summary>4. Weight and sedentary behavior  </summary>  
<br />

> Is there a correlation between self-reported weight and minutes of sedentary behavior?

Variables: WHD020 (self-reported weight, cleaned) and PAD680 (sedentary behavior time, cleaned).

</details>
<br />

<details>
  <summary>5. Misc. Analysis</summary>  
<br />

</details>

</details>
<br />
