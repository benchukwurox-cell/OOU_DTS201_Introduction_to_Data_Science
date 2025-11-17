# 📂 DTS201 Data Folder

This folder contains all datasets used throughout the **OOU DTS 201 – Introduction to Data Science** course.

Students can access these datasets directly from **Google Colab** using the raw GitHub URL.

---

## 📌 How to Load a CSV and Excel File in Google Colab

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Sakinat-Folorunso/OOU_DTS201_Introduction_to_Data_Science/main/data/your_dataset.csv"
df = pd.read_csv(url)

df.head()


import pandas as pd

url = "https://raw.githubusercontent.com/Sakinat-Folorunso/OOU_DTS201_Introduction_to_Data_Science/main/data/your_file.xlsx"
df = pd.read_excel(url)

df.head()
