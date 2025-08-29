### **Web Scraping Project with BeautifulSoup and PRAW**

This repository provides a Python-based analysis comparing two different web scraping techniques. The project aims to collect data from both a traditional website and a modern API to showcase the strengths of each method.

### **Project Goals**

The main objectives of this project are to:

*   **Demonstrate Dual-Method Scraping:** Use **Beautiful Soup** for static, HTML-based scraping and **PRAW** (Python Reddit API Wrapper) for structured, API-based data retrieval.
    
*   **Collect Diverse Data:** Extract patient feedback stories from the **Care Opinion** website and posts from relevant subreddits on **Reddit**.
    
*   **Highlight Strengths & Weaknesses:** Compare the two approaches, showing how Beautiful Soup is effective for standard websites while PRAW is the superior, more efficient choice for sites with a dedicated API.
    

### **Web Scraping Tasks**

*   **Task 1: Care Opinion** 🏥This section uses **Beautiful Soup** to navigate the Care Opinion website, extracting titles, dates, and full text from patient stories. The scraper is designed to handle pagination and saves the collected data to care\_opinion.csv.
    
*   **Task 2: Reddit** 🤖This part leverages the Reddit API via **PRAW** to perform a targeted search for posts containing a specific keyword across multiple subreddits. The script efficiently collects structured data, including post titles, content, authors, and comment counts, which is then saved to reddit\_topic\_posts.csv.
    

### **Results**

The project successfully demonstrates that:

*   **Beautiful Soup** is a powerful and flexible tool for traditional web scraping tasks.
    
*   **PRAW** is the most reliable and ethical way to collect data from Reddit.
    
*   The choice of scraping tool depends on the website's structure and whether an official API is available.
    

### **Author**

*   \[Abdallah El-Hakawati\]
