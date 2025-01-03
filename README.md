# Analysing the Impact of Phone Usage and Physical Activity on Mental Health  

## Introduction  
This is a personal project where I analyzed the impact of phone usage and physical activity on my mental health. In 2024, I set two main goals:  
1. **Increase physical activity**: Achieve 10,000 steps per day.  
2. **Reduce phone usage**: Limit screen time to under 3 hours per day.  

Throughout the year, I tracked these metrics to evaluate my progress and assess their potential influence on my mental health. To add depth to the analysis, I incorporated data from my journal entries, hypothesizing that excessive phone usage and reduced physical activity might correlate with depressive symptoms.  

This project aims to answer the following questions:  
- Were my 2024 goals met?  
- How did screen time and physical activity relate to my mental health, as reflected in my journal entries?  

## Notebooks Overview  

### 1. **Journal Data Preprocessing, Topic Modeling, and Sentiment Analysis**  
- **Purpose**: Process text-based journal data to derive meaningful insights about mental health.  
- **Key Features**:  
  - **Preprocessing**: Clean and organize journal entries by extracting dates and corresponding text.  
  - **Topic Modeling**: Identify themes in journal entries using techniques such as LDA, NMF, and LSA from the `scikit-learn` library.  
  - **Sentiment Analysis**: Use the `VADER` sentiment analysis tool to categorize journal entries and calculate sentiment scores.  
- **Output**: A dataset containing sentiment categories and scores for each journal entry, which serves as input for further analysis.  
- **Note**: The journal text file is not shared publicly to protect personal information. However, the resulting sentiment data (categories and scores) is available.  

### 2. **Impact of Phone Usage and Physical Activity on Mental Health**  
- **Purpose**: Analyze the relationship between screen time, physical activity, and mental health.  
- **Key Features**:  
  - **Exploratory Data Analysis (EDA)**: Investigate patterns and correlations among screen time, steps, and sentiment scores.  
  - **Data Integration**: Combine all variables (screen time, steps, and sentiment scores) into a unified dataset.  
  - **Modeling**: Predict sentiment scores based on screen time and physical activity.
  - **Explanation of Modeling Results**: A detailed explanation of what the results mean. 

## Data Privacy  
- The raw journal entries are private and excluded from the repository.  
- Sentiment analysis results (categories and scores) are shared for reproducibility and further analysis.  

## How to Use  
1. Clone the repository.  
2. Access and explore the shared datasets and notebooks.  
3. Run the (Impact of Phone Usage and Physical Activity on Mental Health) notebook to reproduce the analysis.  

## Dependencies  
- Python 3.8+  
- Jupyter Notebook  
- Libraries:  
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (for data manipulation and visualization)  
  - `scikit-learn` (for topic modeling)  
  - `VADER` (for sentiment analysis)
 
## Project Limitations  
The limited dataset size affects the robustness of the analysis and the reliability of predictive models, as smaller datasets may not capture the full range of variability or allow for generalizable insights. Future iterations of this project could benefit from:  
- **More frequent journaling**: Increasing the availability of journal entries.  
- **Longer tracking periods**: Extending data collection beyond a single year to improve dataset size and diversity.  
- **Additional variables**: Incorporating complementary metrics, such as sleep quality or stress levels, to enrich the dataset.  

While this limitation is notable, the analysis still offers valuable insights and serves as a foundation for further exploration.

## Future Work  
- Include additional data sources (e.g., sleep patterns or diet) for a more comprehensive analysis.
- Be more constitent with my journaling. 
- Explore alternative modeling techniques for better prediction accuracy.  
- Make anonymized journal data available for broader research applications.  

## Acknowledgements  
Thanks to the developers of the tools and libraries that made this analysis possible.  

---

Feel free to suggest improvements or contribute to the analysis!
