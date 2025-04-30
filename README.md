# Investigating the Effects of Diabetes Diagnoses on the Development of Cardiovascular Disease


## Background

Cardiovascular disease remains the leading cause of death in the United States and is the most common cause of death among people with diabetes. Both conditions share many risk factors:

- High BMI
- Hypertension
- Elevated cholesterol
- Smoking


## Data Sources

This research utilized three main data sources:

1. **CAIR-CVD-2025 Dataset**: 1,529 patient samples from Jamalpur Medical College Hospital (Bangladesh) containing demographic, anthropometric, clinical, biochemical measurements, lifestyle choices, and Framingham risk scores

2. **National Center for Health Statistics**: Diabetes prevalence and glycemic control data among adults aged 20 and over, by sex, age, and race

3. **Research All of Us Database (NIH)**: Comprehensive clinical, demographic, and social determinants of health data, including lab results, vital signs, and behavioral factors

## Methodology

The research employed several analytical approaches:

- Linear regression to identify key predictors of CVD risk
- Matching strategies to ensure comparability between treatment and control groups (diabetic and non-diabetic)
- Average Treatment Effect (ATE) estimation to determine the causal impact of diabetes on CVD
- Analysis of age-diabetes interaction on CVD Risk Score

## Key Results

### CAIR-CVD-2025 Dataset Analysis
- Diabetes status had the largest coefficient in predicting CVD Risk Score (coeff=2.005, p<0.001)
- ATE calculation showed diabetes increases Framingham Risk Score by over 2.2%
- Matching analysis revealed younger adults (20-50) are statistically more at risk for CVD than initially concluded

### Diabetes Prevalence Dataset Analysis
- Diabetes associated with 4.87% higher probability of heart disease (p<0.001)
- ATE calculation showed individuals with diabetes have a 14.95% higher probability of developing heart disease
- Other significant factors included high blood pressure (3.36% increase), high cholesterol (3.88% increase), and stroke history (18.77% increase)

### Research All of Us Database Analysis
- Matching analysis estimated the ATE of diabetes on CVD to be 3.22% (95% CI: [0.0074, 0.0570])
- Effect remained statistically significant after balancing clinical, demographic, and socioeconomic variables

## Implications

This research highlights the urgent need for:

1. Enhanced early screening strategies for both diabetes and CVD risk factors
2. Targeted interventions for younger adults
3. Integrated approaches to address shared risk factors between diabetes and CVD
4. Improved access to care and affordable medication, especially considering the high cost burden for diabetes patients

## Repository Structure

```
├── data/
├── notebooks/
├── images/
└── README.md
```

## Contributors

**Team Panda:** Lilah DuBoff, Mu Niu, Sam Wang, and Su Zhang
