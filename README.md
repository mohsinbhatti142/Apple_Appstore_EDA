# 📊 EDA on Apple App Store Dataset

This project presents an in-depth **Exploratory Data Analysis (EDA)** of the Apple App Store, offering valuable insights into app genres, user ratings, pricing, content rating categories, and developer activity.

---

## 📁 Dataset Overview

The dataset contains detailed metadata for Apple App Store applications, including app names, genres, user ratings, pricing, and developer information.

### 🔑 Key Columns:
- `App_Id` – Unique identifier for each app  
- `App_Name` – Name of the application  
- `AppStore_Url` – Direct link to the app on the App Store  
- `Primary_Genre` – Main category/genre of the app  
- `Content_Rating` – Age group classification (e.g., Everyone, Teens)  
- `Size_Bytes` / `Size_MBs` – Size of the app  
- `Required_IOS_Version` – Minimum iOS version required  
- `Released` / `Updated` – App release and last update dates  
- `Version` – Latest app version available  
- `Price` – Cost of the app  
- `Currency` – Currency type (usually USD)  
- `DeveloperId`, `Developer`, `Developer_Url` – Developer details  
- `Average_User_Rating`, `Reviews` – User engagement metrics  
- `Current_Version_Score`, `Current_Version_Reviews` – Ratings and reviews specific to the current version  
- `type` – Indicates whether the app is **Free** or **Paid**  
- `Reviews_category` – A categorized representation of review counts  

---

## 📌 Objectives of This EDA
- Analyze the distribution of free vs. paid apps  
- Identify top genres based on the number of apps and reviews  
- Examine app sizes, prices, and their effect on ratings  
- Study developer activity and review patterns  
- Investigate content rating trends (age-appropriateness)

---

## 📊 Key Findings (Sample Highlights)
- **Games** is the most dominant genre by app count.  
- Free apps significantly outnumber paid ones.  
- Some developers have released a large number of apps.  
- Certain genres show consistently higher user ratings.

---

## 🛠️ Tools & Libraries Used
- `Python` (Pandas, NumPy)
- `Matplotlib`, `Seaborn` for data visualization
- `Jupyter Notebook` for analysis and interactive exploration

