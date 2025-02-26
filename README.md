# Information Retrieval, Extraction and Integration - CBIR

### Authors 
- Davis Siemens
- Inés Simón del Collado
- Xiya Sun

---

## Project Overview
This project is the 'Non-textual data extraction' for the Information Retrieval, Extraction and Integration course. This project implements a Content-Based Image Retrieval (CBIR) system designed to match real-world facial images with visually similar artistic portraits. 

---

## Notebooks
The project consists of **one notebook** with all the code:
1. `irei-cbir-faces.ipynb` – CBIR implementation.

---

## Folders

### `/feature_db`
- Contains the face feature vectors of the image database used.

### `/input/query_images`
- Contains the query images used for retrieval.

---

## Execution Instructions
1. Ensure all necessary dependencies are installed.
2. To run the notebook locally, download the dataset from Kaggle (https://www.kaggle.com/datasets/deewakarchakraborty/portrait-paintings) and place it in the `/input/portrait_painting` directory.

### Notes
- Ensure the `/input/query_images` folder is populated with the query images we want to retrieve before execution.
- Review results and model outputs in the `/feature_db` folder after completion.
- `irei-cbir-faces.html` is the HTML report with CBIR results
