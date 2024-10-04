# NewsApp---Fetch-Latest-News-Articles-Using-NewsAPI

PROJECT DISCRIPTUON

# NewsApp

NewsApp is a simple Java-based application that allows users to fetch and display the latest news articles from the web using the [NewsAPI](https://newsapi.org/). Users can search for news articles based on specific keywords, such as "football" or "Cristiano Ronaldo," and the application will return related news headlines.

This project demonstrates how to work with REST APIs in Java, handle HTTP connections, and parse JSON responses. The app can be easily extended to include more advanced features, such as filtering by language, country, or news source.

## Features
- Fetch news articles by entering any keyword (e.g., "Sports,Business,Technology").
- Simple command-line interface for searching news articles.
- Parses and displays article titles from the JSON response.
- Handles network errors and API response codes gracefully.

- TECHNOLOGIES USED
- 
- ## Technologies Used
- Java
- NewsAPI (for fetching news articles)
- HTTPURLConnection (for making API requests)
- JSON (for handling API responses)

## Prerequisites
- Java JDK (version 8 or later)
- Internet connection
- NewsAPI key (you can sign up for free at [https://newsapi.org/register](https://newsapi.org/register))

- ## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/NewsApp.git
    ```

2. Navigate to the project directory:
    ```bash
    cd NewsApp
    ```

3. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

4. Replace the `apikey` in the `NewsApp.java` file with your own NewsAPI key. You can get a key by signing up on the [NewsAPI website](https://newsapi.org/register).

5. Compile and run the project:
    ```bash
    javac NewsApp.java
    java NewsApp
    ```

6. The application will prompt you to enter a keyword (e.g., "football", "Cristiano Ronaldo"). Based on your input, the app will fetch the latest news articles and display the titles.
   

- ## Usage

1. Run the application:
    ```bash
    java NewsApp
    ```

2. Enter a keyword related to the news you want to search for, such as:
    - **"Football"** to get football-related news.
    - **"Cristiano Ronaldo"** to get news about Cristiano Ronaldo.
    - **"Technology"** to get technology-related news.

3. The application will fetch news articles and display their titles based on your input.


- License: This project is licensed under the MIT License.

Contact : For any questions, feedback, or support inquiries, please contact sriramsubramaniyan555@gmail.com. We'd love to hear from you!

