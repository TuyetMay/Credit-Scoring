# Credit-Scoring
This project develops and evaluates credit scoring models using the Lending Club dataset to predict loan repayment outcomes (“Fully Paid” vs. “Charged Off”). It systematically compares two preprocessing strategies—traditional encoding (Label and One-Hot) with Random Forest–based feature selection, and Weight of Evidence (WOE) encoding with Information Value (IV)–driven feature selection—to assess their impact on model performance and interpretability. Three classifiers (Logistic Regression, Random Forest, and LightGBM) are trained and evaluated using metrics such as AUC, Gini index, accuracy, and F1-score. The results demonstrate that WOE/IV encoding consistently enhances discriminatory power and stability, particularly for linear models and ensemble methods, making it a preferred approach in regulated credit risk environments.






