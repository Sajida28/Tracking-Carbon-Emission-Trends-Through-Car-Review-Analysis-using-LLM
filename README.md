# Tracking-Carbon-Emission-Trends-Through-Car-Review-Analysis-using-LLM

**Project Description**

- Conducted carbon emission tracking within the entirety of the project's code and assessed its trend over time.
- Used a pre-trained LLM to classify the sentiment of the five car reviews in the car_reviews.csv dataset, and evaluated the classification accuracy and F1 score of predictions.
- Extracted and passed the first two sentences of the first review in the dataset to an English-to-Spanish translation LLM for Spanish customers. 
- Calculated the BLEU score to assess translation quality, using the content in reference_translations.txt as references.
- Loaded an extractive QA LLM such as "deepset/minilm-uncased-squad2" to formulate the question "What did he like about the brand?" and obtain an answer from 2nd Review to emphasize on brand aspects.
- Summarized the last review in the dataset, into approximately 50-55 tokens long. 
