# 251MI71_Group05_FinalProject_SourceCode
**Course**: 251MI71 - Data Analytics in E-Commerce  
**University of Economics and Law (UEL)**
# Analyzing Seasonal Trends in Tourist Reviews to Support Service Optimization and Marketing Strategies in  Hotels and Attractionss

---
##  Team Members

**Group 05 - Faculty of E-commerce**

| No. | Full Name | Student ID |
|-----|-----------|------------|
| 1 | Lữ Hồng Quân | K224111500 |
| 2 | Hồ Thị Ngọc My | K224111491 |
| 3 | Lê Nguyễn Thanh Nhã | K224111497 |

**Advisor**: Lecturer Ho Trung Thanh

---
##  Acknowledgments

We express our sincere gratitude to:
- **Lecturer Ho Trung Thanh** for invaluable guidance and feedback
- **Faculty of E-commerce, UEL** for providing resources and academic support
- **TripAdvisor reviewers** whose feedback enabled this research

---
##  Project Overview

This report presents a comprehensive sentiment analysis study of hotel customer reviews from TripAdvisor. We analyzed **2,499 reviews** for **The Milner York Hotel** to identify seasonal sentiment patterns and provide data-driven recommendations for service optimization.

**Key Achievement**: Our ensemble model achieved **89% accuracy** in sentiment prediction, offering actionable insights for hospitality management.

##  Document Structure

This report contains **4 main chapters** with detailed analysis and findings:

### Chapter 1: Business Problem
- Business needs and demands in the hospitality industry
- Problem statement and research challenges
- Six core business questions addressing:
  - Overall satisfaction factors
  - Seasonal trend analysis
  - Service optimization opportunities

### Chapter 2: Data Collection and Preprocessing
- **Data Source**: 2,499 TripAdvisor reviews (2018-2025)
- **Data Understanding**: Review structure, distribution, and quality considerations
- **Preprocessing Pipeline**: 
  - Text cleaning and normalization
  - Sentiment analysis (VADER + TextBlob)
  - Seasonal categorization
  - Feature engineering (TF-IDF, Word Embeddings)

### Chapter 3: Modeling
Three comprehensive modeling approaches:
- **Lexicon-Based**: VADER sentiment analyzer (82% accuracy)
- **Machine Learning**: Logistic Regression (86%), XGBoost (29%)
- **Deep Learning**: LSTM (84%), BERT (86%)
- **Ensemble Methods**: Majority Voting (87%), Stacking Ensemble (89%)

### Chapter 4: Visualization and Managerial Actions
- **Visualizations**: Sentiment distribution, seasonal trends, word clouds
- **Business Recommendations**:
  - Room upgrades and facility improvements
  - WiFi infrastructure enhancement
  - Staff training programs
  - Employee reward policies
- **Advanced Techniques**: Class imbalance handling, BERT fine-tuning, ABSA, Continuous Learning

---

##  Key Findings

### Sentiment Distribution
- **Positive**: 83.75% (2,093 reviews)
- **Negative**: 13.77% (344 reviews)  
- **Neutral**: 2.48% (62 reviews)

### Seasonal Performance

| Season | Avg. Rating | % Positive | % Negative | Key Insight |
|--------|-------------|------------|------------|-------------|
| **Spring** | 3.99 | 86.3% | 10.8% | Highest satisfaction period |
| **Summer** | 3.57 | 79.8% | 17.7% | Service strain from high demand |
| **Autumn** | 3.67 | 83.7% | 14.1% | Stabilization after peak season |
| **Winter** | 3.93 | 85.9% | 11.7% | Consistent service quality |

### Model Performance Summary

| Model | Accuracy | AUC | F1 (Negative) |
|-------|----------|-----|---------------|
| VADER | 82% | 0.81 | 0.48 |
| Logistic Regression | 86% | 0.88 | 0.45 |
| BERT | 86% | 0.88 | 0.65 |
| **Stacking Ensemble** | **89%** | **0.93** | **0.75** |

---

##  Business Value

This analysis provides actionable insights for:
- **Service Optimization**: Identify specific aspects (rooms, staff, WiFi) needing improvement
- **Seasonal Strategy**: Tailor marketing and operations to peak/low periods
- **Reputation Management**: Detect and address negative feedback patterns
- **Resource Allocation**: Data-driven staffing and budget decisions

---



##  Repository Contents

- **`251MI71_Group05_FinalProject.docx`**: Complete project report
- **`data/`**: Raw and processed review datasets
- **`code/`**: Python notebooks and scripts
  - Data preprocessing
  - Feature engineering (TF-IDF, LSTM, BERT)
  - Model training and evaluation
  - Visualization generation
- **`results/`**: Figures, charts, and performance reports
- **`references/`**: Academic papers and resources

---


##  How to Read This Report

1. **For Business Stakeholders**: Focus on Chapter 1 (Business Problem) and Chapter 4 (Visualizations & Recommendations)
2. **For Technical Audience**: Review Chapters 2-3 for methodology, preprocessing, and modeling details
3. **For Researchers**: See References section and Advanced Techniques (Section 4.3) for academic foundations

---

##  Key Contributions

This project demonstrates:
-  **Comprehensive NLP pipeline** from raw text to business insights
-  **Multiple modeling approaches** (Lexicon, ML, Deep Learning, Ensemble)
-  **Practical business applications** with specific recommendations
-  **Advanced techniques** including BERT fine-tuning and class imbalance handling
-  **Seasonal analysis framework** applicable to tourism and hospitality sectors

---

##  License & Usage

This project is submitted as academic coursework for the University of Economics and Law (UEL). 




** Last Updated**: November 2, 2025  
** Contact**: Available through GitHub repository

---

*This README provides an overview of the project report. For complete technical details, methodology, and results, please refer to the full document.*
