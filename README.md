Smiler - AI-Powered Protein-Ligand Interaction Predictor

Smiler is a standalone desktop application designed to assist researchers in predicting protein-ligand interactions. Utilizing cutting-edge machine learning techniques, it simplifies the process of bioactivity prediction by processing molecular structures (SMILES strings) and providing confidence scores. With its user-friendly interface and robust features, Smiler accelerates drug discovery and molecular research, making it accessible to non-programmers and experts alike.

Key Features:

-Data Input: Accepts SMILES strings via direct input or CSV upload.

-Bioactivity Prediction: Predicts active/inactive molecules and estimates regression values like IC50.

-Molecular Feature Extraction: Computes properties such as molecular weight and LogP.

-Visualization: 

--Displays molecular structures and prediction confidence scores.

--View 2D structures of SMILES strings.

--Download 3D structures for further analysis.

-Batch Processing: Handles up to 500 molecules efficiently.

-Test File: Includes a sample CSV file containing SMILES data for MET protein, obtained through a ChEMBL search, to test the tool.

Built With:

-Programming Language: Python

-Libraries & Tools: RDKit, scikit-learn, PyTorch, pandas, numpy, matplotlib, seaborn

-Data Sources: ChEMBL API

Purpose:
Smiler aims to save time and effort in molecular research, providing reliable and quick results for researchers with limited resources.

⚠️ Caution for Beginners:

-RDKit in Jupyter: Smiler uses RDKit for molecular data processing. If running this project in Jupyter Notebook, ensure that the Jupyter environment is properly configured to support RDKit. Failure to do so may result in errors during execution.

-Code Errors Before GUI: Some cells in the pre-GUI code may produce errors due to adjustments made for GitHub upload (e.g., reducing the number of cells and focusing on key functions). These errors are harmless and do not affect the functionality of the main tool. Users can safely ignore them.
