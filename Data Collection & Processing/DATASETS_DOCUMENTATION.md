# Scraped Datasets Documentation

## Overview
This document provides a comprehensive overview of all scraped datasets in the Data Collection & Processing folder. The datasets primarily focus on Indigenous economic topics, particularly the #Indigenomics movement, collected from various social media platforms and search engines.

---

## 1. Twitter Datasets

### 1.1 Personal Twitter Archive (`/Twitter Datasets/data/`)
**Format**: JavaScript files (`.js`)  
**Source**: Official Twitter data export  
**Account**: @Hesquiaht (Carol Anne Hilton, MBA)  
**Account ID**: 249829356  

#### Key Data Files:
- **account.js**: User profile information including email, username, creation date, display name
- **ad-engagements.js**: (~3.7MB) Advertising engagement data
- **ad-impressions.js**: (~318KB) Advertisement impression metrics
- **tweet-headers.js**: (~3.2MB) Tweet metadata
- **deleted-tweets.js**: Archive of deleted tweets with full metadata
- **Various activity files**: Including follower data, blocked accounts, muted accounts, etc.

#### Data Structure Example (account.js):
```javascript
{
  "account": {
    "email": "cawaaknis@me.com",
    "createdVia": "web",
    "username": "Hesquiaht",
    "accountId": "249829356",
    "createdAt": "2011-02-09T21:36:49.000Z",
    "accountDisplayName": "Carol Anne Hilton, MBA"
  }
}
```

### 1.2 #Indigenomics Historical Data (2022-2025)
**Format**: CSV files  
**Coverage**: Complete yearly archives for 2022, 2023, 2024, and partial 2025  

#### 2022 Archive (`/#Indigenomics 2022 - Complete Year/`)
- **Files**: 40 paginated CSV files
- **Naming Convention**: `twitter-2022-p[1-40]-40-#indigenomics-scraping-singlefile.csv`
- **File Size Range**: 9-12KB per file

#### 2023 & 2024 Archives
- Similar structure to 2022 with complete year coverage
- Multiple paginated files containing scraped tweet data

### 1.3 Google Search Twitter Scrapes
**Format**: CSV  
**Method**: Google search results for Twitter content  

#### Files:
- **twitter-#indigenomics-scraping-googlesearch-pkg.csv** (8KB)
- **twitter-Bill-Gallagher-Resource-Rulers-scraping-googlesearch-pkg.csv** (8.5KB)

#### Data Structure:
| Column | Description |
|--------|-------------|
| Search Term | Query used (e.g., "site:twitter.com/ #Indigenomics") |
| Date | Post date or "Unknown" |
| Title | Tweet/Profile title |
| Country | Location code (mostly "ca" for Canada) |
| Description | Tweet preview or profile description |
| URL | Direct Twitter URL |

#### Sample Entry:
```
Search Term: site:twitter.com/ #Indigenomics
Date: Feb 6, 2025
Title: Pacific Economic Development Canada on X: "Amplifying stories of..."
Country: ca
Description: Amplifying stories of Indigenous economic reconciliation at #Indigenomics IMPACT...
URL: https://twitter.com/PacifiCanEN/status/1887611032174051693
```

---

## 2. LinkedIn Datasets

### 2.1 March 27, 2025 Data Request
**Location**: `/LinkedIn Datasets/March 27 2025 LinkedIn Data Requests/`  
**Files**: 
- comments_linkedin_data_req_March_27.csv
- shares_linkedin_data_req_March_27.csv

**Note**: These files appear to contain metadata/documentation rather than actual LinkedIn data

### 2.2 Scraped LinkedIn Data
**Location**: `/LinkedIn Datasets/Scraped Data - With URL Extract/` and `/Scraped Data - No URL Extract/`  
**Purpose**: LinkedIn profile and post data related to Indigenous economic topics

---

## 3. Instagram Datasets

**Location**: `/Instagram Datasets/`  
**Format**: CSV files  
**Method**: Google search scraping of Instagram content  

### Files and Topics:
| File | Size | Topic Focus |
|------|------|-------------|
| instagram-#economicreconciliation-scraping-googlesearch-pkg.csv | 9KB | Economic reconciliation content |
| instagram-#indigenomics-scraping-googlesearch-pkg.csv | 9KB | Indigenomics movement |
| instagram-#indigenousbusiness-scraping-googlesearch-pkg.csv | 9.2KB | Indigenous business profiles |
| instagram-#indigenouseconomy-scraping-googlesearch-pkg.csv | 8.7KB | Indigenous economy posts |
| instagram-#indigenousentrepreneur-scraping-googlesearch-pkg.csv | 8.8KB | Indigenous entrepreneurs |
| instagram-#indigenousentrepreneurship-scraping-googlesearch-pkg.csv | 8.7KB | Entrepreneurship content |
| instagram-#indigenousprosperity-scraping-googlesearch-pkg.csv | 10.7KB | Prosperity-focused content |
| instagram-1tag-indigenomics-scraping-googlesearch-pkg.csv | 9KB | Single tag search results |

### Data Structure:
Similar to Twitter Google Search format with columns for:
- Search Term, Date, Title, Country, Description, URL

### Sample Instagram Entry:
```
Search Term: site:instagram.com #Indigenomics
Title: Indigenomics (@indigenomics) · Instagram photos and Reels
Country: ca
Description: Home of the #Indigenomics movement | Global #Indigenous #Technology House...
URL: https://www.instagram.com/indigenomics/
```

---

## 4. Google Search Datasets

**Location**: `/Google Datasets/`  
**Format**: CSV files  
**Purpose**: Direct Google search results for Indigenous economic hashtags  

### Main Files:

#### 4.1 Hashtag-Specific Searches
- **google-#economicreconciliation-scraping-googlesearch-pkg.csv** (12KB)
- **google-#indigenomics-scraping-googlesearch-pkg.csv** (3.5KB)
- **google-#indigenousbusiness-scraping-googlesearch-pkg.csv** (10.4KB)
- **google-#indigenouseconomy-scraping-googlesearch-pkg.csv** (9.5KB)
- **google-#indigenousentrepreneur-scraping-googlesearch-pkg.csv** (8.9KB)
- **google-#indigenousentrepreneurship-scraping-googlesearch-pkg.csv** (8.7KB)
- **google-#indigenousprosperity-scraping-googlesearch-pkg.csv** (9KB)

#### 4.2 Comprehensive Search Files
- **google-scraping-googlesearch-pkg-V0.csv** (136KB) - Version 0, larger dataset
- **google-V1-scraping-serpapi.csv** (15.7KB) - Version 1 using SerpAPI
- **google_hashtag_search_results.csv** (7.9KB) - General hashtag results

### Data Focus:
Primarily captures Google Books results, Google Play store listings, and various web resources related to Indigenous economics, with special focus on:
- "Indigenomics: Taking a Seat at the Economic Table" book by Carol Anne Hilton
- Indigenous economic development resources
- Conference materials and publications

---

## Key Insights

### Primary Subject
The datasets center around **Carol Anne Hilton** (@Hesquiaht), author of "Indigenomics: Taking a Seat at the Economic Table" and founder of the Indigenomics Institute.

### Temporal Coverage
- **Historical Data**: 2022-2025
- **Most Recent Data**: March 2025
- **Peak Activity**: November 2023-2024 (Indigenomics conferences and events)

### Geographic Focus
- Primary location: **Canada** (country code: "ca")
- Key venues: Bay Street (Toronto), Vancouver, Dakota Dunes Resort

### Major Themes
1. **#Indigenomics** - The primary movement and hashtag
2. **Economic Reconciliation** - Indigenous participation in economy
3. **Indigenous Business** - Business profiles and success stories
4. **Indigenous Entrepreneurship** - Startup and innovation focus
5. **Indigenous Prosperity** - Wealth building and economic growth

### Event Documentation
Multiple references to key events:
- Indigenomics IMPACT (April 8-9, 2025)
- Indigenomics NOW Forum (24-hour global digital forum)
- Indigenomics on Bay Street conferences
- Power Play Galas

### Data Collection Methods
1. **Direct Platform Exports**: Twitter official data archive
2. **Google Search Scraping**: Using site-specific searches (site:twitter.com, site:instagram.com)
3. **SerpAPI**: Programmatic search result collection
4. **Pagination**: Systematic collection across multiple pages

---

## Usage Notes

1. **Privacy Consideration**: Personal information is included (emails, account IDs)
2. **Format Variety**: Mix of JavaScript objects and CSV files
3. **Temporal Snapshots**: Data represents specific points in time
4. **Search Bias**: Google search results may be influenced by search algorithms and personalization
5. **Incomplete Data**: LinkedIn datasets appear to have documentation but limited actual data

---

## File Size Summary

- **Largest File**: tweet-headers.js (~3.2MB)
- **Total Twitter Archive**: ~20MB
- **Instagram Datasets**: ~75KB total
- **Google Datasets**: ~230KB total
- **Typical CSV File**: 8-12KB

---

*Documentation compiled: September 2025*