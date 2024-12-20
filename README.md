# Week 2: Telecommunication Business Analysis Project

## Project Overview
This project involves analyzing customer data from TellCo, a telecommunications company in the Republic of Pefkakia. The goal is to evaluate growth opportunities, provide actionable recommendations, and build a comprehensive dashboard to present insights to stakeholders.

The analysis focuses on:
- **User Overview**: Device preferences and data usage patterns.
- **Engagement Analysis**: Clustering users based on session metrics.
- **Experience Analytics**: Network performance and user satisfaction.
- **Satisfaction Analysis**: Predicting and quantifying user satisfaction scores.

---

## Tasks Overview
### Technical Tasks:
1. **User Overview Analysis**
   - Identify top 10 handsets and top 3 manufacturers.
   - Analyze application usage and session data.
   - Aggregate metrics such as session duration and total data traffic.

2. **User Engagement Analysis**
   - Identify top users by session metrics (frequency, duration, traffic).
   - Normalize metrics and group users into engagement clusters using k-means clustering.
   - Analyze application usage patterns.

3. **Experience Analytics**
   - Evaluate network performance metrics (TCP retransmission, RTT).
   - Analyze device characteristics and usage trends.
   - Cluster users based on experience metrics.

4. **Satisfaction Analysis**
   - Assign engagement and experience scores to users.
   - Compute overall satisfaction scores and rank users.
   - Build a regression model to predict satisfaction scores.

5. **Dashboard Development**
   - Develop an interactive dashboard to present findings.
   - Deploy the dashboard on a public platform.

---
## How to Run the Project
### Prerequisites
1. Install Python 3.13.2 .
2. Set up a PostgreSQL database using the provided `telecom_data.sql` schema.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Lemlem-Tsifete/Tnx-academy-week-2.git
   cd Tnx-academy-week-2
2. Dashboard Deployment:
Deploy the dashboard using Streamlit:
    cd dashboards/
    streamlit run app.py

## Project Structure

```plaintext
.
├── .vscode/
│   └── settings.json                # Editor-specific settings
├── .github/
│   └── workflows/
│       └── unittests.yml            # CI/CD workflow for unit tests
├── .gitignore                       # Ignored files for version control
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
├── src/                             # Source code
│   ├── __init__.py                  # Initialize src module
├── notebooks/                       # Jupyter notebooks
│   ├── __init__.py                  # Initialize notebooks module
│   └── README.md                    # Notebook-specific documentation
├── tests/                           # Unit tests
│   ├── __init__.py                  # Initialize tests module
└── scripts/                         # Utility scripts
    ├── __init__.py                  # Initialize scripts module
    └── README.md                    # Documentation for scripts
