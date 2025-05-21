# NewsAPI Search Tool

A simple web application that allows users to search for news articles using the NewsAPI service. This tool is designed to demonstrate the basic usage of NewsAPI with a focus on searching for articles related to technology, venture capital, and funding topics.

## Features

- Search for news articles by keywords or article title
- Fuzzy matching for title searches to find the closest matching articles
- Suggested search terms for tech and VC-related topics
- Displays one article at a time (respecting the NewsAPI free tier limitations)
- Shows article details including:
  - Title/Headline
  - Source/Media Name
  - Publication Date/Year
  - Estimated Country of Origin
  - Article Content
  - Original URL

## How to Use

1. Get your API key from [NewsAPI](https://newsapi.org/) by signing up for a free account
2. Use the tool to search the articles 

## Language Support

Currently, the tool only supports English-language news articles. Support for additional languages is planned for future updates.

## Free Tier Limitations

This tool is designed to work with the NewsAPI free tier, which has the following limitations:

- 100 requests per day
- Limited to recent articles (no historical data)
- No commercial use allowed

The application is configured to display only one article per search to make the most of your daily request limit.

## Important Notes

- The country of origin is estimated based on the domain of the source website and may not always be accurate
- If the API limit has been reached, the application will display an error message
- This tool is for demonstration purposes only and is not intended for production use
- When searching by title, the application will retrieve multiple articles and use fuzzy matching to find the closest match to your query


## License

This project is available under the MIT License. See the LICENSE file for more details.

## Acknowledgements

This tool uses the [NewsAPI](https://newsapi.org/) service to fetch news articles.
