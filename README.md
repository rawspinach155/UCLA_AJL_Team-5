# Kaggle Project: UCLA AJL Team 5

## Team Members
- [Emma Wu](https://github.com/rawspinach155)
- [Carina Curiel Alaniz](https://github.com/CarinaCurielAlaniz)
- [Carolina Caraballo Vélez](https://github.com/carolcv04)
- [Kayne Maniti](https://github.com/kemsig)
- [Paige Caskey](https://github.com/paigecaskey)
- [Yuancheng (Kaleo) Cao](https://github.com/Cao1224)

## Project Overview

### Kaggle Competition & Break Through Tech AI Program
This project is part of the **Equitable AI for Dermatology** Competition, hosted by Break Through Tech and the Algorithmic Justice League (AJL). The competition highlights the biases present in AI-powered dermatology tools and aims to create more inclusive models that work effectively across diverse skin tones. Our participation aligns with the Break Through Tech AI Program’s mission to provide hands-on experience in AI and data science while addressing real-world equity challenges.

### Objective of the Challenge
The goal of this competition is to develop a machine learning model capable of classifying **21 different skin conditions** across diverse skin tones. Our model’s performance is evaluated using a **weighted average F1 score**, and we aim to maximize accuracy while ensuring fairness in dermatology AI applications.

### Real-World Significance
AI is increasingly being used in healthcare, yet **dermatology AI tools often underperform for individuals with darker skin tones** due to non-representative training data. This disparity can lead to **diagnostic errors, delayed treatments, and worsened health outcomes for marginalized communities**. Our project seeks to build an inclusive dermatology AI model, contributing to ongoing efforts from institutions like **Stanford and MIT Media Lab** to create equitable, explainable AI systems.

## Data Exploration

### Dataset Description
The dataset used in this project consists of images and metadata related to **21 dermatological conditions** across patients with varying skin tones. This data is provided by Kaggle and serves as the foundation for our model. To enhance the inclusivity of our AI model, we are exploring potential additional datasets that offer more diverse training samples.

### Data Exploration & Preprocessing
Our initial data exploration steps included:
- Handling missing values by **imputing missing metadata and ensuring balanced representation**
- Performing feature engineering to **augment images and extract useful attributes**
- Normalizing/scaling data using **standardization techniques**
- Encoding categorical variables with **one-hot encoding for categorical metadata**

### Exploratory Data Analysis (EDA)
We conducted visualizations to understand data distribution and model fairness considerations. Below are some key insights:

#### Distribution of Skin Tones in Dataset
![skin dist](https://github.com/user-attachments/assets/07288522-b302-43ed-86a8-f84850e0d24d)

#### Visualizing Augmented Images
![augmented images](https://github.com/user-attachments/assets/921c73a0-aa48-4c71-ab03-0867e1146480)

## Next Steps
- Train and optimize model for high accuracy and fairness
- Use **fairness and explainability tools** to assess AI bias
- Document findings and develop a storytelling approach to highlight inclusivity efforts

## Repository Structure
```
|-- data/                 # Contains raw and processed datasets
|-- notebooks/            # Jupyter notebooks for data exploration & modeling
|-- src/                  # Source code for model training & evaluation
|-- README.md             # Project documentation (
