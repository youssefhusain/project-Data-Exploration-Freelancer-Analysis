# 📂 Freelancer Data Documentation

This document provides details about various freelancer-related datasets and extracted features.

---

## 📌 1️⃣ Freelancer Data (`freelancer_data.csv`)
This file contains information about freelancers, including pricing, skills, and reviews.

### 🔹 Columns:
- **`price`** → The price of the freelancer's services.  
- **`image`** → URL or file path to the freelancer's image.  
- **`country`** → The freelancer's location.  
- **`description`** → A brief summary of the freelancer's expertise and services.  
- **`skills`** → A list of skills the freelancer possesses.  
- **`rating`** → The freelancer's rating (e.g., 1 to 5).  
- **`reviews`** → The number of reviews received.  
- **`name`** → The freelancer's name.  

---

## 📌 2️⃣ PeoplePerHour Data (`peopleperhour.csv`)
This dataset contains freelancer information from the **PeoplePerHour** platform.

### 🔹 Columns:
- **`price`** → The cost of the freelancer's services.  
- **`total votes`** → The total number of votes the freelancer has received.  
- **`name`** → The freelancer's name.  
- **`country`** → The freelancer's location.  
- **`description`** → A brief summary of their expertise.  

---

## 📌 3️⃣ Kolabtree Data (`kolabtree_data.csv`)
This dataset contains freelancer details from the **Kolabtree** platform.

### 🔹 Columns:
- **`price`** → The cost of the freelancer's services.  
- **`total votes`** → The total number of votes the freelancer has received.  
- **`name`** → The freelancer's name.  
- **`country`** → The freelancer's location.  

---

## 📌 4️⃣ Fiverr Data (`fiver_data.csv`)
This dataset contains freelancer information from the **Fiverr** platform.  
❗ **(Details for this file were not provided; consider adding column descriptions.)**

---

## 📌 5️⃣ Cleaned Freelancer Data (`freelancer_data_after_clean.csv`)
This file contains **the cleaned and processed version** of `freelancer_data.csv`.

### ✅ Modifications include:
- 🧹 **Data cleaning and preprocessing**  
- 🔄 **Standardization of country names, skills, and pricing formats**  
- ❌ **Removal of duplicates and invalid entries**  
## 📌  Extracted Features  
During the data preprocessing, we extracted the following features:

### 🔹 **New Columns:**
- **`Region`** → The geographical region of the freelancer based on their country.  
- **`skills_list`** → Extracted list of skills from the freelancer's profile.  
- **`skills_count`** → Number of skills the freelancer has.  
- **`level`** → Extracted membership level from freelancer profiles.  
- **`categories`** → Categorized skills based on predefined categories.  
- **`skills_list_standardization`** → Standardized skills for consistency.  
- **`description_Length`** → Length of the freelancer's description in characters.  
- **`Extracted_Skills_from_description`** → Skills extracted from the description text.  
- **`Extracted_Skills_from_description_list`** → List of unique skills extracted from the description.  
- **`Extracted_Skills_from_description_number`** → Total number of extracted skills from the description.  

---



