# My Excel Projects
This folder contains spreadsheets, pivot tables, and data cleaning examples using MS Excel.

---

## 📂 Project: Data Transformation & Recovery
In this project, I cleaned a "dirty" dataset and changed its structure.

### What I did:
* **Saved valuable data:** The instructions said to delete rows with missing values. However, I noticed that in the last 3 columns, the missing values could be calculated from other cells. I used logic to fill them instead of deleting, preserving important information.
* **Format Change:** I transposed the data from "Long" to "Wide" format to make it better for reporting.
* **Text Cleaning:** * Used `=TRIM()` to remove hidden spaces (especially the tricky ones from web-imports).
    * Fixed text casing ('=UPPER()') for Region to make them consistent.
* **Cleaned Formatting:** Removed all colors and styles to have a "fresh" dataset.
* **Final Formatting (Readability):** I enhanced data readability by bolding headers, applying borders, and freezing the top row to ensure the dataset remains professional and easy to navigate for stakeholders.

## 💡 Key Takeaway
This project taught me that data cleaning isn't just about following a checklist. By looking for patterns, I was able to save data instead of just deleting it. Good formatting is the final touch that makes a "cleaned" file a "professional" report.

---

## 📂 Project: Student Performance (Portugal)
I analyzed a dataset of high school students to prepare it for academic research.

### What I did:
* **Business Logic:** I found students aged 20-22. Since this is a high school dataset, I identified them as outliers and removed them based on school rules.
* **Categorical Data:** Converted parental education levels from text into numbers (0-4). This makes the data ready for math models.
* **Completeness:** Filled missing "reason" fields with "none_given" so the rows stay in the analysis.

## 💡 Key Takeaway
I believe that **"Garbage In, Garbage Out"**.
---
