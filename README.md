# NLP-Women-Ecommerce


Data Exploration and Preprocessing
The project begins with exploring a dataset of 23,486 customer reviews from a women’s clothing e-commerce platform. The dataset includes key features such as product category, subcategory, location, channel, customer age, review text, ratings, and recommendation flags. Missing values in textual data were handled by dropping incomplete records, reducing the dataset to 19,662 entries. Reviews were preprocessed to standardize the text, removing punctuation, converting to lowercase, and eliminating stop words, ensuring a clean and uniform dataset for analysis.

Sentiment Analysis
Sentiment polarity was calculated using the TextBlob library, providing a numeric representation of customer sentiment for each review. The distribution analysis revealed that the majority of sentiments ranged between -0.2 (slightly negative) and 0.8 (positive), indicating an overall favorable customer response. Sentiments were categorized as positive, neutral, or negative, allowing a deeper analysis of customer opinions.

Exploratory Data Analysis (EDA)
EDA provided valuable insights into customer behavior and product performance. Visualizations showed that the average reviewer age was 43, with most reviewers falling between 20 and 70 years old. Ratings predominantly clustered around 4 and 5 stars, emphasizing general customer satisfaction. Word count analysis indicated that reviews contained an average of 62 words, with the longest reviews exceeding 500 words.

Feature Engineering and Visualization
The textual data was transformed using TF-IDF vectorization, resulting in a feature space of 1,000 key tokens for machine learning models. Visualizations using Plotly highlighted sentiment polarity distributions, ratings across subcategories, and the correlation between recommendation flags and review ratings. These visualizations provided actionable insights into customer preferences for specific product types.

Machine Learning Models
Machine learning models, including Linear SVC, were developed to predict review ratings and recommendation flags based on review text. The rating prediction model achieved an accuracy of 72%, while the recommendation classification model reached 89% accuracy. The models provided a robust method for automating customer feedback analysis, with F1-scores reflecting the dataset’s imbalanced nature.

Topic Modeling and N-grams
Topic modeling using Latent Dirichlet Allocation (LDA) identified key themes in customer reviews, with the top topics including terms related to product fit, material quality, and style. Additionally, bigram and trigram analysis revealed common phrases, such as "fits perfectly" and "love this dress," underscoring recurring customer sentiments and preferences.
