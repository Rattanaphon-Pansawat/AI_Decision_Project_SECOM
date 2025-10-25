# AI Decision System for Semiconductor Manufacturing

This repository is the central KNIME workflow for our group project on AI Decision-making Manufacturing.

## Project Goal
To build a machine learning pipeline in KNIME that predicts Pass/Fail yield and identifies key sensor parameters from the UCI SECOM dataset.

## Technology
- **Main Tool:** KNIME Analytics Platform
- **Version Control:** Git

## Workflow Structure
- **/Data:** Contains the raw `uci-secom.csv`.
- **/01_Data_Prep_EDA:** KNIME workflow for data cleaning, EDA, and preprocessing.
- **/02_Modeling_Evaluation:** KNIME workflow for model training (DT, RF, GBT), cross-validation, and tuning.
- **/03_Analysis_Dashboard:** KNIME workflow for results analysis (Feature Importance) and dashboarding.

---

### **Rules for Team (Important!)**
1.  **Workspace Setup:** To work on this project, you MUST set your KNIME workspace to point to the folder you cloned from this repository.
    * (In KNIME: `File` > `Switch Workspace` > `Other...` > Select the cloned folder).
2.  **Data Files:** The `.gitignore` is set to ignore `.csv` files. Please add the `uci-secom.csv` to your local `/Data` folder manually after cloning (it is not tracked by Git).