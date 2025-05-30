# Training Analytics

This project automates the collection and analysis of data from:

- **TrainingPeaks**: TSS, CTL, ATL, and completed workouts
- **Garmin**: Sleep, stress, and HRV
- **Renpho**: Weight, body fat %, BMI

### 🔁 Daily ETL Pipeline

- Pull data from each API
- Store in SQLite or CSV
- Scheduled with `cron` or GitHub Actions

### 📊 Weekly Digest

- Summary tables of key metrics
- Weight loss tracking
- Sleep/stress vs. training load alignment
- Workout compliance report

### 📂 Project Structure# training-analytics
  training-analytics/
├── data/
├── scripts/
├── notebooks/
├── reports/
└── README.md
