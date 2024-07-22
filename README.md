# Google Search Analyzer

Google Search Analyzer is a powerful web-based tool designed to extract and analyze content from the top Google search results. It identifies the most common words, bigrams (two-word combinations), and trigrams (three-word combinations) from the search results. This tool is ideal for SEO experts, content creators, and researchers who need to gather insights from web content quickly and efficiently.

Live Demo Available Here: https://google-keyword-synergy-checker.glitch.me/

## Features

- **Search Engine Integration:** Uses Google search to find relevant web pages based on user queries.
- **Content Scraping:** Fetches and processes the content of the top 10 search results using `axios` and `cheerio`.
- **Natural Language Processing:** Analyzes the text to count the occurrences of words, bigrams, and trigrams using the `natural` library.
- **Exclusion List:** Filters out common words and phrases to focus on more meaningful content.
- **User-Friendly Interface:** Simple and interactive web interface to input search queries and display results.

## How It Works

1. **User Input:** The user enters a search query and specifies the minimum number of sites for keyword appearance.
2. **Google Search:** The tool performs a Google search using the `google-it` library, fetching the top 10 URLs.
3. **Content Extraction:** Each URL is processed to retrieve the page content while excluding scripts and styles.
4. **Text Analysis:** The content is tokenized and analyzed to count words, bigrams, and trigrams, excluding common terms.
5. **Result Display:** The results are displayed on the same page, showing the most frequent words, bigrams, and trigrams along with their counts.
