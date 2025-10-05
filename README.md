# Fuzzy Diabetes Risk Analysis

This project is a comparative study of two fuzzy inference systems — Mamdani and Sugeno — for predicting diabetes risk based on medical parameters. The goal is to analyze how each method handles fuzzy reasoning and determine which produces more accurate and interpretable results.

## 1. Overview
Fuzzy logic provides a flexible and human-like approach to reasoning with uncertainty, which makes it suitable for medical diagnosis problems. In this project, we implement and compare Mamdani and Sugeno fuzzy inference systems for diabetes risk classification using inputs such as Glucose, BMI, and Blood Pressure.

## 2. Objectives
- To design fuzzy inference systems (FIS) using Mamdani and Sugeno methods.
- To compare the accuracy, efficiency, and interpretability of both methods.
- To evaluate the effectiveness of fuzzy logic in predicting diabetes risk.

## 3. Dataset
The dataset used is based on standard medical attributes relevant to diabetes diagnosis. Key features include:
- Glucose Level
- Body Mass Index (BMI)
- Blood Pressure

Each record is classified as either Low, Medium, or High risk for diabetes based on fuzzy rules.

## 4. Methodology
1. Data Preprocessing: Normalize input variables and remove outliers.
2. Fuzzy Membership Function Design: Define fuzzy sets for each input parameter.
3. Rule Base Construction: Build expert-based rules for both Mamdani and Sugeno models.
4. Inference System Implementation: 
   - Mamdani uses min-max composition with centroid defuzzification.
   - Sugeno uses weighted average for crisp output.
5. Evaluation: Compare both systems using test data and analyze performance metrics such as accuracy and rule interpretability.

## 5. Tools and Technologies
- Python 3.x
- NumPy, scikit-fuzzy
- Matplotlib for visualization
- Jupyter Notebook (for prototyping)

## 6. Results
- Mamdani FIS provides more interpretable reasoning and visual rule mapping.
- Sugeno FIS demonstrates faster computation and smoother output surface.
- Performance differences highlight trade-offs between interpretability and computational efficiency.

## 7. Conclusion
Both Mamdani and Sugeno fuzzy systems perform well for diabetes risk prediction. 
Mamdani is preferable for explainability and medical decision support, while Sugeno is better suited for integration with optimization and adaptive systems.

## 8. How to Run
1. Clone this repository:
   ```
   git clone https://github.com/mragilsa/fuzzy-diabetes-risk-analysis.git
3. Navigate to the project folder:
   ```
   cd fuzzy-diabetes-risk-analysis
5. Install dependencies:
   ```
   pip install -r requirements.txt
7. Run the notebook or Python file to see results. 

## 9. License
This project is licensed under the MIT License.
