## Project Background

Bumble is a popular dating platform where users connect based on mutual interests, lifestyle preferences, and compatibility. User profiles contain rich information such as demographics, physical attributes, lifestyle habits, and activity patterns, making them a valuable source for behavioral analysis.
<br><br>
This project analyzes Bumble user profile data to uncover patterns in user demographics, lifestyle choices, and engagement behavior. The goal is to identify meaningful trends that can help improve matchmaking strategies, user segmentation, and overall platform experience.

---

## Insights and recommendations are provided on the following key areas:

- **Demographic Analysis**: Distribution of users across age groups, gender, and relationship status to understand platform composition.

- **Lifestyle Behavior Analysis**: Examination of habits such as diet, drinking, and their interrelationships to identify behavioral patterns.

- **Profile Engagement & Completeness**: Analysis of how factors like age, gender, income, and status influence profile completeness and user engagement.

- **Income & Socioeconomic Trends**: Evaluation of income distribution across age and gender to identify progression patterns and disparities.

- **Physical Attributes & Preferences**: Exploration of relationships between body type and height to understand physical profile distributions.

---

## Data Structure & Initial Checks

The dataset consists of **user profile records**, where each row represents an individual user. It captures demographic details, lifestyle preferences, and activity information used to analyze user behavior and engagement.

| Column Name     | Data Type | Description                                                                 |
|----------------|----------|-----------------------------------------------------------------------------|
| age            | INT      | Age of the user                                                             |
| status         | VARCHAR  | Relationship status (e.g., single, married, seeing someone)                |
| gender         | VARCHAR  | Gender of the user (e.g., m, f)                                            |
| body_type      | VARCHAR  | Physical appearance description (e.g., athletic, curvy, thin)              |
| height         | FLOAT    | Height of the user                                                         |
| diet           | VARCHAR  | Dietary preference (e.g., vegetarian, vegan, anything)                     |
| drinks         | VARCHAR  | Drinking habits (e.g., socially, often)                                    |
| education      | VARCHAR  | Education level (e.g., college, masters)                                   |
| income         | FLOAT    | Annual income (user-reported)                                              |
| location       | VARCHAR  | User location (city, state)                                                |
| last_online    | DATETIME | Last active timestamp                                                      |

---

## Project Resources

- **Notebook:** [View Analysis Notebook](notebook/Case_Study_Analyzing_Bumble_Profiles.ipynb)  
- **Dataset:** [Download Dataset](data/bumble.csv)
