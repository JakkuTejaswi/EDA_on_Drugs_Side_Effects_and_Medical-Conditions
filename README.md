# EDA: Drugs, Side Effects, and Medical Conditions

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset of drugs, their side effects, associated medical conditions, and user ratings. The aim is to uncover insights about the distribution of drug ratings, most common side effects, and the relationship between drug classes and ratings.

The analysis is done using **Python**, with visualizations created using **Matplotlib** and **Seaborn**.

---

## 📊 Dataset
- **File**: drugs_side_effects_drugs_com.csv
- **Features**:
  - `drug_name` – Name of the drug
  - `medical_condition` – Medical condition the drug is used for
  - `side_effects` – Reported side effects
  - `drug_classes` – Drug category/class
  - `rating` – User rating for the drug



---

## 🚀 Project Workflow
1. **Data Loading & Cleaning**
   - Read the dataset using Pandas
   - Removed null values
   - Removed duplicates
2. **Exploratory Data Analysis**
   - Distribution of ratings
   - Ratings per drug
   - Top medical conditions and their drugs
   - Most common side effects
   - Ratings by drug class
   - Availability of drugs for different medical conditions
3. **Visualizations**
   - Histograms
   - Bar plots
   - Box plots

---

## 📈 Key Insights
- Distribution of ratings shows variations in drug effectiveness and user experience.
- Certain medical conditions have significantly more drug options.
- Some drug classes receive consistently higher ratings.
- A few side effects are very common across multiple drugs.

---

## 📷 Sample Visualizations
- **Ratings Distribution** – Histogram of drug ratings
- **Ratings by Drug** – Bar chart of average rating for each drug
- **Top Side Effects** – Frequency of reported side effects
- **Drugs per Medical Condition** – Bar chart showing drug availability

---

## 🔮 Future Improvements
- Perform sentiment analysis on drug reviews (if available)
- Explore time-based trends in ratings
- Apply clustering to group similar drugs based on side effects and ratings

---

## 📜 License
This project is licensed under the MIT License.


