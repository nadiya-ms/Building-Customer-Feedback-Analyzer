# Build a Customer Feedback Analyzer

Python project to build a customer feedback analyzer

## **Introduction**

### Dataset Overview:
- The `guest_data_with_reviews.xlsx` dataset contains customer feedback from a hospitality business.
- Key columns include:
  - `How likely are you to recommend us to a friend or colleague?` for Net Promoter Score (NPS) calculations.
  - `Review` for textual feedback, useful for sentiment analysis and topic modeling.

### Key Concepts:
1. **Net Promoter Score (NPS):** Measures customer loyalty. Scores:
   - 9–10: Promoters
   - 7–8: Passives
   - 0–6: Detractors
   - Formula: NPS = percentage of promoters - percentage of detractors

2. **Sentiment Analysis:** Identifies the emotional tone (positive, negative, or neutral) in reviews using pre-trained AI models.

3. **Topic Modeling:** Uses embeddings to identify recurring themes in text data.
