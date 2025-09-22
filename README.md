# Netflix Movies and TV Shows: Exploratory Data Analysis

### [View the full analysis in the Jupyter Notebook](./Netflix_EDA_Project.ipynb)

---

## 📝 Project Objective

This project performs an exploratory data analysis (EDA) on the Netflix dataset to uncover insights into its content library. The goal is to answer business-focused questions about content strategy, key market trends, and audience focus, providing a clear picture of Netflix's strategic priorities.

---

## 📊 Dataset

* **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* **Acquisition:** The dataset was downloaded directly from Kaggle using the official Kaggle API, ensuring a reproducible and up-to-date data pipeline.
* **Description:** This dataset contains a listing of all movies and TV shows available on Netflix as of 2021, along with details such as cast, directors, ratings, release year, and duration.

---

## 🚀 Key Business Questions & Insights

This analysis was framed to answer key strategic questions for Netflix:

1.  **What is Netflix's primary content focus?**
    * **Insight:** The library is dominated by **Movies** (~70%), suggesting a strategy focused on single-viewing experiences over long-term series.

2.  **Which countries are key markets for content production?**
    * **Insight:** The **United States and India** are the top two content producers, highlighting their strategic importance for acquiring licenses and producing original content.

3.  **How has Netflix's content acquisition strategy evolved?**
    * **Insight:** There was a dramatic acceleration in content acquisition starting around **2016**, indicating a major strategic shift towards aggressive, high-volume library expansion.

4.  **Who is Netflix's primary target audience?**
    * **Insight:** The largest share of content is rated **TV-MA (Mature Audience)**, indicating that Netflix's primary target demographic is adults.

5.  **Do top creators specialize in certain genres?**
    * **Insight:** Yes, there is a strong pattern of specialization. For example, top actors from India focus on **Dramas and International Movies**, while top directors often specialize in a single niche like **Kids' TV**. This provides a clear roadmap for casting and production partnerships.

---

## 🛠️ Tools Used

* **Programming Language:** Python
* **Data Acquisition:** Kaggle API
* **Libraries:**
    * **Pandas:** For data manipulation and cleaning.
    * **Plotly Express:** For creating interactive data visualizations.
    * **Matplotlib:** For basic plotting.