## Sentiment Analysis with BERT

This GitHub repository contains code for performing sentiment analysis using the BERT model. The project is divided into several key steps:

### 1. Preparing Libraries
- Importing necessary Python libraries, including `transformers`, `tensorflow`, `requests`, `BeautifulSoup`, `re`, `pandas`, and `numpy`.
- Filtering out warnings to enhance code readability.

### 2. Instantiate Model
- Loading the BERT model directly using the Hugging Face Transformers library.
- Utilizing the `nlptown/bert-base-multilingual-uncased-sentiment` model.

### 3. Encode and Calculate Sentiment
- Tokenizing a sample text and obtaining token IDs.
- Decoding token IDs to reconstruct the original text.
- Processing text to determine its sentiment score using the loaded BERT model.
- Converting sentiment score to a numeric value (1 for negative, 2 for neutral, and 3 for positive).

### 4. Collect Reviews
- Sending a request to retrieve reviews from a specific URL (Goodreads book reviews in this case).
- Parsing the HTML content of the page using BeautifulSoup.
- Extracting and storing the reviews in a Python list.

### 5. Load Reviews into DataFrame and Score
- Creating a Pandas DataFrame to organize and analyze the collected reviews.
- Demonstrating how to calculate the sentiment score for an individual review.
- Applying sentiment scoring to all reviews and storing the results in the DataFrame.
- Calculating and displaying the mean sentiment score for the collected reviews, rounded to two decimal places.

