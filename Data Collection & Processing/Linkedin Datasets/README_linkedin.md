
# 📌 LinkedIn Datasets


This README file provides an overview of the datasets collected from LinkedIn for the #Indigenomics project. The folder contains three types of datasets for LinkedIn:

## 📁 1.1C March 27 2025 LinkedIn Data Requests: 
This folder contains a copy of the data we got from the March 7th request of Carol Anne's LinkedIn accounts. All the files here include both the links and the text.

### 📍 [20,475KB CSV] `shares_linkedin_data_req_March_27.csv`
1. `Date` - Provides the date and time in the following format using military time: **"YYYY-MM-DD HH:MM:SS"**.
2. `ShareLink` - Links to Carol Anne's post.
3. `ShareCommentary` - The text CA wrote on her post.
4. `SharedUrl` - Any links Carol Anne added to her post. Most entries won't have one.
5. `MediaUrl` - Provides the URL to any media (images, videos) that were generated for her post. Most entries will be empty.
6. `Visibility` - Specifies whether her post is visible within CA's `MEMBER_NETWORK`. Most entries will be empty.
7. `Extracted_Text` - This file contains data from scraping the `ShareLink` URL. 


### 📍 [1KB CSV] `comments_linkedin_data_req_March_27.csv`

This file contains data from posts that CA has commented on with:
1. `Date` - Provides the date and time in the following format using military time: **"YYYY-MM-DD HH:MM:SS"**.
2. `Link` - A link to the post Carol Anne commented on.
3. `Message` - Provides the comment CA left on the original post.
4. `Extracted_Text` - Extracts the text from the original post author.

## 📁 1.2C Scraped Data - No URL Extract: 
This folder contains a copy of the data we got from scraping LinkedIn and pull from multiple hashtags across different public accounts. All the files in here include the links. Most posts in this folder have only 25 observations and do not include the text.

## 📁 1.3C Scraped Data - With URL Extract: 
This folder contains a copy of the data we got from scraping LinkedIn. All the files here include both the links and the text, but the samples are not large.

