
# Sentiment Analysis Corpus

## Project Overview
This project involves sentiment analysis on user-generated content such as posts and tweets. The goal is to analyze and classify text into different sentiment categories using natural language processing techniques.

## Dataset
The dataset contains the following columns:
- **Type**: The source of the content (e.g., Post, Tweet).
- **Display_name**: Name or identifier of the user or entity posting.
- **Date**: The date the content was created.
- **Contents**: The original text of the content.
- **Categories**: The category of the content (e.g., Accommodation, Experience).
- **translated_content**: Translated version of the content.
- **cleaned_data**: Processed version of the content for analysis.
- **neg**: Negative sentiment score (range: 0 to 1).
- **neu**: Neutral sentiment score (range: 0 to 1).
- **pos**: Positive sentiment score (range: 0 to 1).
- **compound**: Combined sentiment score (range: -1 to 1).
- **sentiment**: Final sentiment label (e.g., positive, negative).

## Key Features
- Text preprocessing including cleaning and translation.
- Sentiment scoring using polarity metrics.
- Classification of sentiment into positive, negative, or neutral categories.

## Usage
1. Clone this repository to your local machine.
2. Ensure you have the required dependencies installed (e.g., Python, pandas, nltk).
3. Use the provided scripts to load and analyze the dataset.

```bash
git clone https://github.com/dj-mrtnz1113/Social_Media_Reviews_Sentiment.git
cd filename
```

## Example Analysis
Sample content from the dataset:
- "The host was unresponsive to messages and calls." - **Sentiment: Negative**
- "Camp Avenue was an unforgettable experience; I loved every bit of it." - **Sentiment: Positive**

## Future Work
- Expand the dataset to include more categories and content types.
- Enhance the sentiment analysis model for better accuracy.
- Integrate the analysis with visualization tools.

## License
This project is licensed under the [MIT License](LICENSE).

---

### Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue.

---

### Contact
For any inquiries, please reach out to [your-email@example.com].
