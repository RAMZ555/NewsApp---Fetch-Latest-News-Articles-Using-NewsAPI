# 📰 NewsApp — Fetch Latest News Articles Using NewsAPI

**NewsApp** is a robust Java application that fetches, caches, and displays real-time news articles using the NewsAPI. It includes intelligent caching, search history logging, pagination, and clean error handling — all in a professional console-based design.

---

## 🚀 Key Features

- 🔍 **Keyword-based news search**
- ⏳ **Intelligent caching** (30-minute cache duration per query)
- 🧾 **Search history logging** with timestamps
- 🔁 **Pagination** (10 articles per page)
- 🌐 **Open article in browser**
- ⚠️ **Comprehensive error handling** (API failure, network issues)
- 📄 **Displays full article details**: title, source, description, date

---

## 🔧 Technical Highlights

- ✅ Clean OOP design with proper package structure
- ✅ Custom JSON parsing (no external libraries)
- ✅ Memory-efficient caching mechanism
- ✅ Safe resource handling via `try-with-resources`
- ✅ Thread-safe architecture (internally guarded)
- ✅ CLI-friendly UI with easy navigation

---

## 🧪 Technologies Used

| Layer           | Technology              |
|----------------|--------------------------|
| Language        | Java 8+ (Standard Edition) |
| API             | [NewsAPI](https://newsapi.org/) (REST API) |
| Networking      | `HttpURLConnection` |
| JSON Handling   | Manual parsing via regex |
| Time Handling   | `LocalDateTime` |
| File I/O        | History saved using `FileWriter`, `BufferedReader` |

---

## 📦 Project Structure

NewsFetcher/
├── src/
│ └── com/newsapp/
│ ├── NewsFetcher.java # Main application
│ ├── NewsCache.java # Caching logic
│ ├── NewsArticle.java # Article data model
├── search_history.log # Auto-generated
├── README.md

yaml
Copy
Edit

---

## 📁 How to Set Up

### ✅ Prerequisites

- Java JDK 8 or later
- Internet connection
- NewsAPI key (free at [https://newsapi.org](https://newsapi.org))

  ## 🖥 Sample Output

=== News Fetcher Application ===
1. Search news by keyword
2. View search history
3. Exit
Enter your choice: 1

Enter a keyword to search news (e.g., Sports, Business, Technology): technology
Enter category (optional): technology
Enter country code (e.g., us, in) (optional): us

=== News Results (Page 1) ===

[1] Apple Announces New M3 MacBook Pro Models
Source: The Verge
Published: Jul 08, 2025 08:15 AM
Description: Apple introduced its new M3-powered MacBooks at a press event today...
URL: https://www.theverge.com/apple-m3-macbook

[2] Google AI Upgrade Surpasses GPT-4
Source: TechCrunch
Published: Jul 07, 2025 11:45 PM
Description: Google’s Gemini AI shows dramatic improvements over GPT-4...
URL: https://techcrunch.com/google-gemini-ai

...

Total articles: 10

Enter article number to open in browser (0 to skip): 2
✅ Opening in browser...

Do you want to see next page? (y/n): y

## 🧾 Sample History Output

=== Search History ===
2025-07-08 10:41:30 | technology | Results: 10
2025-07-08 10:45:12 | sports     | Results: 8

### 📥 Installation

```bash
git clone https://github.com/your-username/NewsApp.git
cd NewsApp
javac -d bin src/com/newsapp/*.java
java -cp bin com.newsapp.NewsFetcher
⚙️ Configuration
In NewsFetcher.java, replace the placeholder with your actual NewsAPI key:

java :

private static final String API_KEY = "your_api_key_here";
⚡ Performance Notes
🧠 Caching reduces API calls and boosts responsiveness

💾 Lightweight parsing = minimal memory use

🧾 Efficient file writing for logging search history

📜 License
This project is licensed under the MIT License.
Feel free to fork, modify, and share!

👨‍💻 Author
Sriram Subramaniyan
📧 sriramsubramaniyan555@gmail.com

⭐ If you like this project, consider giving it a ⭐ on GitHub!

---

## ✅ Next Steps:

- Replace `your-username` with your actual GitHub username in the links
- Place this in `README.md`
- Push your code to GitHub.
