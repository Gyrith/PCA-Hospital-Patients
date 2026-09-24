# PCA: Hospital Patients

Principal Component Analysis on simulated hospital patient data, reducing 11 health metrics to 6 components while keeping 96% of the variance.

## Files

- `hospital_pca_lab.ipynb`: analysis notebook
- `hospital_patients.csv`: dataset (300 patients, 11 features plus `length_of_stay`)

## Results

- 6 components retained (96.3% variance explained)
- PC1: infection and vitals (white blood cells, temperature, blood pressure, age)
- PC2: metabolic factors (cholesterol, glucose, BMI)
- PC3: heart rate and respiratory rate
