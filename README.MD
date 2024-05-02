# World News Explorer MVP

## Team
- Sara Khalid: Front-end and back-end developer
- Shimaa Sayed: Front-end and back-end developer

## Architecture

[Imgur](https://imgur.com/vwF2out)

### User Interface
The user interface serves as the entry point for users to interact with the system. It is built using HTML, CSS, and JavaScript, offering a user-friendly interface for browsing and searching news articles.

### Web Client
The web client manages user interactions and communicates with the web server via API routes. Developed using Node.js and Express.js, it provides API endpoints for consuming data.

### Data Source
Responsible for fetching news data from various sources, including NewsAPI and RSS feeds from reputable news sources.

### Database
MongoDB is used as the database, providing persistent storage for fetched news data.

### Data Processing
This module processes and transforms fetched news data into a format consumable by the web client, utilizing various data processing techniques.

### Data Storage
Stores processed news data in the database, offering interfaces for storing and retrieving news data.

### API Routes
Provides endpoints for the web client to interact with the system, handling user requests seamlessly.

### User Authentication
Manages user authentication and authorization, ensuring secure access to the system.

### Search Functionality
Enables users to search for news articles based on topics or keywords, utilizing various search algorithms.

### Categorization Functionality
Categorizes news articles based on content, offering browsing options for users by category.

### Data Synchronization
Regularly synchronizes new data in the database with the latest data from the data source.

### Error Handling
Handles errors and exceptions to maintain system stability and reliability.

## APIs and Methods

To facilitate communication between the web client and server, the following API routes are implemented:

- `GET /news`: Retrieve a list of news articles.
- `GET /news/:id`: Fetch a specific news article by its ID.
- `POST /search`: Accept a search query and return relevant news articles.
- `GET /categories`: Retrieve a list of news categories.
- `GET /categories/:category`: Fetch news articles belonging to a specific category.

## Third-Party APIs

World News Explorer utilizes the following 3rd-party APIs:
- NewsAPI: Provides access to breaking news headlines, articles, and blogs.
- RSS Feeds: Consumed from reputable news sources like BBC, CNN, and Al Jazeera.

## User Stories

To meet the needs of target users, the following user stories are addressed:

1. View a list of news articles from various sources on the homepage.
2. Search for news articles on specific topics or keywords.
3. Filter news articles by category.
4. View the full content of a news article.
5. Personalized news experience based on user preferences.

## Data Model

[Imgur](https://imgur.com/1XKxvzZ)

The data model illustrates the basic structure of data storage in World News Explorer MVP, including user preferences and interactions with categorized news articles.

## Mockups

[Imgur](https://imgur.com/Z2j7fHo)
[Imgur](https://imgur.com/tL4cF0G)
[Imgur](https://imgur.com/33zvIOU)
