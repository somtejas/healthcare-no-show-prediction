
# Healthcare Appointment No-Show Prediction

### Data Science | Machine Learning | Healthcare Intelligence

## Project Overview

An end-to-end data science project designed to analyze
healthcare appointment no-shows, identify operational
risk factors, and support data-driven decision-making
through predictive analytics and interactive dashboards.

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Appointments | 1,000 |
| Healthcare Clinics | 8 |
| Cities Covered | 6 |
| Attended Appointments | 777 |
| No-Shows | 219 |
| Unknown Outcomes | 4 |
| Overall No-Show Rate | 21.99% |
| Potential Revenue at Risk | INR 152,050 |

## Project Objectives

- Clean and validate healthcare appointment data.
- Identify factors associated with patient no-shows.
- Develop and evaluate machine learning models.
- Compare model performance.
- Build interactive healthcare dashboards.
- Provide actionable business recommendations.

## Key Business Insights

- No-show rate without reminders: 30.86%.
- No-show rate with reminders: 15.22%.
- Reminder recipients had approximately 50.7% lower
  observed no-show rates.
- Appointments booked 31+ days in advance recorded
  a 60.47% no-show rate.
- Phone bookings recorded the highest no-show rate
  among booking channels at 27.93%.
- Gomti Nagar Care Point recorded the highest
  clinic-level no-show rate at 33.70%.

These findings represent observed associations,
not proof of causation.

## Machine Learning Performance

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Test Accuracy | 67.40% | 71.82% |
| Precision | 33.85% | 34.15% |
| Recall | 57.89% | 36.84% |
| F1 Score | 0.4272 | 0.3544 |
| Test ROC-AUC | 0.7113 | 0.6583 |
| CV ROC-AUC | 0.8090 | 0.7949 |

### Selected Model: Logistic Regression

Selected based on stronger cross-validation recall,
F1 score and ROC-AUC performance.

Patient-level separation was used for the holdout
split, with zero patient overlap.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly
- Google Colab
- GitHub

## Planned Repository Structure

- notebooks/ - Data science notebooks
- cleaned_data/ - Processed datasets
- eda_outputs/ - Exploratory analysis
- ml_outputs/ - Model evaluation and artifacts
- dashboard/ - Interactive HTML dashboards
- documentation/ - Capstone project report

Data and artifacts will be shared only where authorized.

## Business Recommendations

- Pilot targeted appointment reminders.
- Reconfirm long-lead-time appointments.
- Improve patient communication.
- Review high no-show clinics.
- Provide flexible scheduling options.

## Limitations

This project is an analytical prototype.
Further validation, privacy review and performance
assessment are required before operational deployment.

Revenue at risk represents potential exposure,
not confirmed financial loss.

## Author

**Somya Ranjan Sahoo**

Data Science & Artificial Intelligence

November 2026

---

Transforming Healthcare Data into Actionable Intelligence.
