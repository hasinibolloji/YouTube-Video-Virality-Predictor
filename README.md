# Virality Prediction Engine for YouTube Trending Videos  
### A Business Analytics Lab Project (Minor in Innovation & Entrepreneurship)  
### VNR VJIET — 2025

This is a **course-based project** developed as part of the **Business Analytics Lab** for the **Minor Degree in Innovation & Entrepreneurship** at **VNR VJIET**.

The project uses **real YouTube trending data** (INvideos.csv from Kaggle) to analyze what makes a video go **viral**, and builds a simple ML model to **predict view counts** based on features like title length, publish hour, likes, and comment count.

---

##  **Project Summary**

### ✔ What this project does  
- Loads and cleans the **YouTube Trending Videos (India)** dataset  
- Performs feature engineering  
- Finds patterns in:
  - Title length  
  - Publish time  
  - Likes  
  - Comments  
- Builds a **Random Forest ML model** to predict video view count  
- Generates **data-driven insights** for:
  - Creators  
  - Brands  
  - Social media marketing teams  
- Acts as an early version of a **“Virality Engine”** for content strategy

---

##  **Why This Project? (Market Relevance)**

In today’s content-heavy world:

- Companies spend crores on Instagram/YouTube marketing  
- Creators want higher reach  
- Startups need viral content for traction  
- Brands want predictable performance  

This project directly solves that need.

It acts like a **micro-version of tools used by Content AI Startups**, enabling:

- Predicting video performance  
- Suggesting best posting times  
- Understanding engagement patterns  
- Helping creators optimize their titles/descriptions  

##  **Dataset Used**
**Kaggle Dataset:** Trending YouTube Video Statistics  
File used: `INvideos.csv` (India)

Dataset includes:
- Video titles  
- Views, likes, comments  
- Publish time  
- Trending dates  
- Categories  
- Tags  

Link (search this on Kaggle):  
`kaggle trending youtube video statistics`

---

##  **Tech Stack**
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-Learn**  
- **Google Colab**

---

##  **Features Implemented**
### **1. Data Cleaning**
- Removed missing values  
- Parsed timestamps  
- Organized dataset  

### **2. Feature Engineering**
- Title length  
- Publish hour  
- Engagement ratios  

### **3. Visualization**
- Heatmaps  
- Feature importance  
- Title buckets  

### **4. Machine Learning Model**
Algorithm used:  
✔ Random Forest Regressor  

Output:  
→ Predict estimated view count  

### **5. Insights Generated**
- Best time to publish  
- Ideal title length  
- Which engagement metric matters most  
- Correlation analysis  

---

## 🛠 **How to Run This Project**

### **Method 1: Google Colab (Recommended)**  
1. Open `ViralityPredictionEngine.ipynb`  
2. Click **Open in Colab**  
3. Upload `INvideos.csv` when asked  
4. Run all cells → You will get:
   - Predictions  
   - Insights  
   - Graphs  
   - Model scores  

### **Method 2: Run Locally**  
Requires Python 3.10+.

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
