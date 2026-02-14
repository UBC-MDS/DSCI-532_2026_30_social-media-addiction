## 2. Description of the Data

We use the **Students Social Media Addiction Dataset**, from kaggle which contains structured survey responses capturing students’ demographic characteristics, social media usage behavior, and indicators of addiction.

The dataset contains **705 observations (rows)** and **13 variables (columns)**. Each row represents one individual student’s survey response.

### Key Variables

The variables can be grouped into three major categories:

####  Demographic Variables
- **Age**
- **Gender**
- **Academic_Level**
- **Country**
- **Relationship_Status**

These variables allow us to compare addiction patterns across different student subgroups (e.g., age groups, academic levels, or countries).

---

#### Social Media Usage Behavior
- **Avg_Daily_Usage_Hours** – Average number of hours spent on social media per day.
- **Most_Used_Platform** – Primary platform used (e.g., Instagram, TikTok, etc.).
- **Conflicts_Over_Social_Media** – Whether usage causes interpersonal conflicts.

These variables help measure the intensity and behavioral patterns of social media use.

---

####  Academic & Psychological Impact Indicators
- **Affects_Academic_Performance** – Whether social media impacts studies.
- **Sleep_Hours_Per_Night** – Average sleep duration.
- **Mental_Health_Score** – Numerical indicator of mental well-being.
- **Addicted_Score** – Numerical score quantifying addiction severity.

These variables are central to our problem, as they measure the consequences of excessive social media use on academic performance, sleep quality, and mental health.

---

### Relevance to the Problem

This dataset is highly relevant to our dashboard’s goal of supporting healthier digital behavior among students.

- The **Addicted_Score** provides a measurable indicator of addiction severity.
- **Avg_Daily_Usage_Hours** allows us to examine whether increased usage correlates with higher addiction.
- **Sleep_Hours_Per_Night** and **Mental_Health_Score** help assess psychological and physiological effects.
- **Affects_Academic_Performance** directly connects usage to educational outcomes.

By integrating these variables into an interactive dashboard, users (e.g., educators, counselors, or policymakers) can:

- Identify high-risk student groups.
- Compare addiction levels across demographic categories.
- Explore relationships between screen time, sleep, and mental health.
- Support data-driven interventions for digital well-being.

Because the dataset is clean and tabular, it supports filtering, grouping, and comparative visualizations, making it well-suited for an interactive decision-support dashboard.
