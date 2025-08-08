# OTPless Signup Funnel & Retention Analysis

This project analyzes the signup funnel conversion and user retention for OTPless, a passwordless authentication platform.  
All data is simulated but reflects real-world business logic and reporting.

**Tech Stack:**  
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

---

## 🚀 Project Highlights

- **Funnel Analysis:** Where users drop off during signup, step-by-step
- **Cohort Retention Analysis:** Track user login activity after signup
- **Signup Source Segmentation:** Web vs Mobile breakdown
- **Charts:** Modern visualizations for funnel, retention, and DAU
- **Business Insights:** Recommendations to improve onboarding & retention

---

## 📁 Structure


---

## 📊 How to Run

1. **Clone this repo**
    ```bash
    git clone https://github.com/yourusername/signup-funnel-retention-otpless.git
    cd signup-funnel-retention-otpless
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**
    ```bash
    jupyter notebook notebooks/funnel_analysis.ipynb
    ```

---

## 📈 Example Analyses

- **Funnel Drop-off Chart**
- **Signup Completion by Source (Web/Mobile)**
- **Retention Heatmap (Cohort by days since signup)**
- **DAU (Daily Active Users) trend**
- **Churn/Retention Curve**

*(See full results in the notebook!)*

---

## 📦 Data

- All user and event data is simulated, with random drop-offs and multiple return logins.
- See [`data/sample_events_retention_fixed.csv`](data/sample_events_retention_fixed.csv) for details.

---

## 💡 Key Insights & Recommendations

- The biggest drop-off is at OTP verification—suggest UX improvements.
- Mobile users convert at a lower rate than web users.
- Retention is highest in the first 2 days after signup—focus engagement there.

---

## 📝 Author

- Ansh Dankhara(https://github.com/AnshD109)
- Inspired by real-world work at OTPless

---



