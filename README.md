# Fragrances Recommender System

## Overview
The **Fragrances Recommender System** delivers personalized perfume recommendations based on customer preferences and fragrance reviews. Designed for businesses like Macy's, it enhances customer engagement and satisfaction by offering tailored suggestions.

## Features
- **Personalized Recommendations**: Matches user preferences (e.g., "exotic") with fragrance reviews.
- **Sentiment Analysis**: Evaluates reviews to determine sentiment (positive, negative, neutral).
- **Topic Modeling**: Extracts key themes from reviews using advanced NLP techniques like BERT.
- **Customer Insights**: Identifies popular attributes and fragrances based on customer feedback.
- **API Integration**: Supports both online and in-store applications.

## Data Source
- Collected **44,000+ fragrance reviews** from the **Base Notes** forum (up to December 2019).
- Reviews contain sentiment ratings and detailed fragrance descriptions.

## Use Case
Example: A customer looking for an "exotic" fragrance enters their preference into an in-store kiosk system. The system analyzes historical reviews and attributes to recommend the most suitable perfumes.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rony-99/Fragrances-Recommender-System.git
   cd Fragrances-Recommender-System
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Run the `Fragrance_recommender_system_Base_Notes.ipynb` notebook to execute the recommendation engine.
- Use `Base_note_scrapper.ipynb` to scrape and process additional fragrance reviews.
- The uploaded notebook `Fragrance_recommender_system_Base_Notes.ipynb` contains additional insights and implementation details.

## Future Enhancements
- **Sentence Transformers** for scalable and efficient topic modeling.
- Incorporation of **customer behavior metadata** (e.g., demographics, clickstream data) for enhanced personalization.
- **Pricing API** integration to offer budget-based recommendations.
- **In-store Mapping**: Displays aisle locations for easier product discovery.

## License
This project is licensed under the [MIT License](LICENSE).
