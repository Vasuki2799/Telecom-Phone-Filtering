
# 📱 Telecom Phone Recommendation Based on Feature Filtering

This project filters and analyzes a telecom dataset to recommend the most suitable mobile phones based on child-friendly feature requirements. It includes data cleaning, feature engineering, visualization, and final recommendation logic.

---

## 📌 Project Objective

To identify **best-value mobile phones** that meet specific needs such as:
- Bluetooth, WiFi, Touchscreen, External Memory support
- High screen resolution and screen size
- Good camera quality (both front and rear)
- Sufficient internal memory, RAM, and battery power
- Lightweight and slim design

---

## 🔍 Dataset Overview

- Contains technical specifications of various mobile phones
- Includes features such as `Px_h`, `Scr_w`, `RAM`, `Price`, `Blue`, `Wi_Fi`, etc.

---

## ⚙️ Tools Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib** & **Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis

---

## ✅ Key Steps Performed

1. **Data Cleaning**
   - Converted binary features from object to numeric
   - Removed rows with invalid or missing entries (if any)

2. **Feature Engineering**
   - Created `Px` (screen resolution) = `Px_h` × `Px_w`
   - Created `Scr_d` (diagonal size) using Pythagoras' theorem

3. **Logical Filtering Conditions**
   - Filtered phones with child-friendly features (WiFi, Bluetooth, etc.)
   - Applied statistical thresholds (mean, median, quartiles) to filter phones

4. **Visualization**
   - Plotted histograms and annotated them with mean/median
   - Created a bar chart for most varied features

5. **Final Output**
   - Generated a filtered list of best-value phones sorted by price
   - Analyzed feature variability using coefficient of variation
   - Exported top phone recommendations as CSV

---

## 📈 Sample Output

- `best_value_phones.csv`: List of phones meeting all conditions, sorted by price
- `Top 5 Most Varied Features`:
   * Int_Mem 1.50
   * Price 0.74
   * PC 0.71
   * FC 0.71
   * RAM 0.47

 
---
## Author

**Vasuki A**  
📧 vasukiarul27@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/posts/vasuki27_datascience-python-telecom-activity-7341502953402306560-7DTO?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFWofHABP5vZ1q4SVksdeQ_qxpl9ilnOKXM)


---

## 🚀 How to Run This Project

1. Clone this repository  
 ```bash
 git clone https://github.com/your-username/telecom-phone-recommendation.git
 cd telecom-phone-recommendation

---

## Install dependencies

pip install pandas numpy matplotlib seaborn

---

## Open and run the Jupyter Notebook

jupyter notebook telecom_analysis.ipynb

---

## Author

**Vasuki A**  
📧 vasukiarul27@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)





