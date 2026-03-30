**Task 1 — Label and Data Leakage**

1) Label: repeat_purchase_flag
   This is the target variable because it represents whether the customer made a repeat purchase within 30 days, which is exactly what the model is trying to predict.

2) Data Leakage Column: discount_used_on_repeat_order
   This feature contains information about the repeat purchase itself (which occurs in the future), so including it would leak target-related information into the model.

**Task 2 — Missing ML Workflow Steps**

1) Establish a Baseline Model
   A simple baseline (e.g., predicting the majority class) provides a reference point to evaluate whether the complex model actually adds value.

2) Data Splitting (Train/Test or Train/Validation/Test)
   Splitting the data ensures that model performance is evaluated on unseen data, preventing overfitting and giving a realistic estimate of performance.
   
