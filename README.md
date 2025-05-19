# 🏹 #Indigenomics Technical Documentation

## 📖 Overview  

Welcome to the **#Indigenomics** repository. This project collects, processes, and analyzes data from various social media platforms to extract insights and trends from prototyping to project delivery stages. Project documentation is reserved for **Notion**.

---

## 🚀 Features  

This repository optimizes workflows for technical documentation, progress tracking, and iterative feedback, focusing on:  

1. **Data Storage & Processing** - Aggregates data from multiple social media sources. 
2. **Sentiment Analysis** - Applies natural language processing (NLP) techniques to assess sentiment.  
3. **Trend Identification** - Detects emerging patterns and trending topics.  
4. **Visualization** - Presents insights through interactive dashboards.  

---

## 🛠️ Usage & Contribution  

- **Fork** the repository and create a feature branch.  
- Follow the repository's **coding style** and commit message guidelines.  
- **Submit a pull request** for review.  

---

## 1️⃣ Data Collection & Processing  

-    Stores all data scraped with [Nitter.net](https://nitter.net). 
-    Details provided in folder ReadMe file

### 📌 1B. Google Search Datasets

-    Not ready for training; 
-    Consists of sample CSVs (n=25) and do not provide full text access.
-    **Standard Naming Convention:** `google-#economicreconciliation-scraping-googlesearch-pkg.csv`
-    **Exceptions:** Primarily consists of earlier version documents and thus are of a lower quality.
  
`google-V1-scraping-serpapi.csv` 25 observations and records the **Search Term** (six hashtag searched), the **URL** where the text can be accessed, search result **Title**, search result **Description**, and the **Country** (set to Canada).
    
`google-scraping-googlesearch-pkg-V0.csv` 1002 observations and records the **Search Term** (six hashtag searched), the **URL** where the text can be accessed, and the **Country** (set to Canada).
    
`google_hashtag_search_results.csv` 25 observations and records the **Search Term** (six hashtag searched), the **URL** where the text can be accessed, search result **Title**, **Country** (set to Canada), and the **Description**.

### 📌 1C. LinkedIn Datasets

This folder contains three types of datasets for LinkedIn:

#### 📁 1.1 March 27 2025 LinkedIn Data Requests: 
This folder contains a copy of the data we got from Carol Anne's accounts. All the files here include both the links and the text.

#### 📁 1.2 Scraped Data:
No URL Extract: This folder contains a copy of the data we got from scraping LinkedIn and pull from multiple hashtags across different public accounts. All the files in here include the links. Most posts in this folder have only 25 observations and do not include the text.

#### 📁 1.3 Scraped Data:
With URL Extract: This folder contains a copy of the data we got from scraping LinkedIn. All the files here include both the links and the text, but the samples are not large.

### 📌 1D. Instagram Datasets

### 📌 1E. Twitter Datasets

This folder contains datasets collected from Twitter/X. The data is sourced from publicly available tweets using a combination of these technologies: 

| 🛠️ Technology | 🔍 Purpose |
|--------------|-----------|
| **Data Request** | Provides access to larger samples; limited to Carol Anne's account data. |
| **Nitter.net** | An alternative front-end to Twitter that allows for scraping without authentication (small sample, hashtag). |
| **Package:** `googlesearch` | Scrapes publicly available Twitter URLS from google (small sample, hashtag). |

#### 📁 1.1 Twitter Data Request:
This folder contains a copy of the data we got from the Twitter data request for Carol Anne's account which exceptionally contains not only its own README file (`README Twitter Data Request.txt`), but also uniquely stored using the `.js` format. The data was collected on March 27, 2025 and includes all tweets, retweets, and replies from Carol Anne's account that Twitter is able to disclose. 

#### 📁 1.2 \#Indigenomics 2022 - Complete Year: 
This folder contains all posts found using `#Indigenomics` from January 1, 2022, to December 31, 2022. The data was collected using Nitter.net.

#### 📁 1.3 \#Indigenomics 2023 - Complete Year: 
This folder contains all posts found using `#Indigenomics` from January 1, 2023, to December 31, 2023. The data was collected using Nitter.net.

#### 📁 1.4 \#Indigenomics 2024 - Complete Year: 
This folder contains all posts found using `#Indigenomics` from January 1, 2024, to December 31, 2024. The data was collected using Nitter.net.

#### 📁 1.5 \#Indigenomics 2025 - Complete Year: 
This folder contains all posts found using `#Indigenomics` from January 1, 2025, to December 31, 2025. The data was collected using Nitter.net.

---

## 2️⃣ Data Storage  

| 🛠️ Technology | 🔍 Purpose |
|--------------|-----------|
| **#Indigenomics GitHub Repo** | Short-term storage & feedback workflow |
| **[To be added]** | Long-term database |

---

## 3️⃣ Sentiment Analysis  

🚧 **[To be added]**  

---

## 4️⃣ Trend Identification  

🚧 **[To be added]**  

---

## 5️⃣ Visualization  

🚧 **[To be added]**  

---

## 🔒 Security & Compliance  

🚨 **This repository is private and protected by NDA.**  

---

✉️ **For questions or contributions, reach out via GitHub Issues.**  
# Hashtag
