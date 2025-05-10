# Privacy-Preserving-Data-Analysis
Applying Differential Privacy Techniques to Protect Sensitive Information

## Project Overview
This project demonstrates fundamental differential privacy techniques applied to a loan applicant dataset from CMPUT 200 (University of Alberta). The implementation includes:

- Randomized response for binary data (loan approval status)
- Laplace noise addition for continuous data (occupation counts)
- Privacy-accuracy trade-off analysis

## Key Features
- **Randomized Response**:
  - Implemented die-roll mechanism (50% truthfulness)
  - Derived an unbiased estimator for true proportions
- **Laplace Mechanism**:
  - Added ε-differentially private noise
  - Analyzed impact across privacy budgets (ε = 0.1 to 100)
- **Visualizations**:
  - True vs. noisy distributions
  - Privacy-utility trade-off curves


## Randomized Response: True vs. Noisy Loan Approvals
![image](https://github.com/user-attachments/assets/4eb1ba03-8dce-4ccf-91d5-8954446a97dc)

## Impact of ε on Laplace Noise (Occupation Counts)
![image](https://github.com/user-attachments/assets/59cb630a-3fca-4ce4-886c-e17b89826986)

## Distribution of True vs. Noisy Occupation Counts
![image](https://github.com/user-attachments/assets/1fcdb5cc-e733-4e4e-beb9-e7c331692746)

## Privacy-Accuracy Trade-off Curve
![image](https://github.com/user-attachments/assets/9b8f1211-2261-4c66-98e7-b5fdfabef633)
