# Synthetic-Dataset
Synthetic Dataset - Student Dropout

## Descripción
This dataset simulates information about undergraduate students to predict whether they will drop out (yes=1, no=0).

## Included Variables
- **Age**: Student's age (16-30 years).
- **Gender**: Gender (Male, Female, Other).
- **Origin**: Place of origin (Urban/Rural).
- **HS_Average**: High school GPA (2.0–5.0).
- **Admission_Score**: Admission score (100–400).
- **Semester1_Grade**: First semester GPA (0.0–5.0).
- **Socioeconomic_Level**: Low, Medium, High.
- **Scholarship**: 1=Scholarship, 0=No scholarship.
- **Loan**: 1=Scholarship, 0=No loan.
- **Dropout**: 1=Dropped out, 0=Did not drop out.

## Dataset Features
- **Total Records**: 600.
- **Null Values**: Introduced in ~5% of rows in academic columns.
- **Outliers**:
- School GPAs of 10.0.
- Admissions Scores of 999.
- **Categorical Variables**: gender, origin, socioeconomic status.

## Use
This dataset can be used for:
- Practicing data preprocessing.
- Training supervised classification models.
- Testing imputation and outlier detection algorithms.
