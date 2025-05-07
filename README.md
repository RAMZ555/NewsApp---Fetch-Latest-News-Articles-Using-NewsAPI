# NewsApp---Fetch-Latest-News-Articles-Using-NewsAPI

PROJECT DISCRIPTUON

# NewsApp
News Fetcher is a robust Java application that fetches, caches, and displays news articles from NewsAPI with advanced features including search history tracking, result caching, and comprehensive error handling. The application demonstrates professional Java development practices while providing a user-friendly command-line interface.

# Key Features
Enhanced Functionality
Keyword-based news searching with intelligent caching (30-minute cache duration)

Search history logging with timestamped records

Comprehensive error handling for API failures and network issues

Detailed article display including titles, sources, descriptions, and publication dates

Pagination support (10 results per query)

# Technical Improvements
Production-ready architecture with proper package structure

Memory-efficient caching mechanism

Custom JSON parser without external dependencies

Proper resource management with try-with-resources

Thread-safe implementation where needed

# Technologies Used
Core Technologies
Java 8+ (Standard Edition)

NewsAPI (RESTful news data service)

HTTPURLConnection (For API requests)

Manual JSON parsing (No external libraries)

# Advanced Features
LocalDateTime for precise timestamping

File I/O for persistent search history

URL encoding for safe API requests

Regular expressions for JSON parsing

# Installation and Setup
Prerequisites
Java JDK (version 8 or later)

Internet connection

NewsAPI key (free tier available)

# Installation Steps
Clone the repository:

# bash
git clone https://github.com/your-username/NewsFetcher.git

Total articles: 10
# Project Structure
NewsFetcher/
├── src/
│   ├── com/
│   │   ├── newsapp/
│   │   │   ├── NewsFetcher.java       (Main application class)
│   │   │   ├── NewsCache.java         (Caching mechanism)
│   │   │   ├── NewsArticle.java       (Article data model)
├── search_history.log                 (Auto-generated search log)
# Configuration
Replace the API key in NewsFetcher.java:

java
private static final String API_KEY = "your_api_key_here";
# Performance Considerations
Caching reduces API calls and improves response time

Lightweight JSON parsing minimizes memory usage

Efficient file I/O for search history logging

# License
This project is licensed under the MIT License.

# Contact
For inquiries or support, please contact:

Sriram Subramaniyan

Email: sriramsubramaniyan555@gmail.com

