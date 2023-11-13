---
title: How to Extract URLs from Sitemaps
summary: In this article, I'll share my knowledge on how to extract URLs from sitemaps, a crucial step in optimizing your website's SEO.
date: 2023-10-27

authors:
  - admin

tags:
  - SEO
---

Welcome 👋

## Overview

(Last Update: 03/07/2023)

Hello, I'm Mario Lambertucci, a seasoned SEO expert with over 10 years of experience in website management.

In this article, I'll share my knowledge on how to extract URLs from sitemaps, a crucial step in optimizing your website's SEO. This guide is intended for website owners, SEO professionals, and anyone interested in understanding the inner workings of a website.

After trying out various methods over the years, I've found these 5 to be the most effective. Let's dive deeper into each one:

**1. Google Sheets:** This method is simple and quick, making it ideal for beginners or those who need to extract URLs quickly. However, it requires access to Google Sheets and may not be suitable for very large sitemaps due to Google Sheets' cell limit.
**2. Screaming Frog:** This SEO software is a powerful tool that can handle large sitemaps and sitemap index files. However, it requires a download and installation, and there may be a learning curve for those unfamiliar with the software.
**3. Python (Google Colab):** This method is excellent for those who are comfortable with coding. It's flexible and can handle large sitemaps, but it may be intimidating for those without coding experience.
**4. Terminal:** This method is quick and doesn't require any additional software, but it requires some familiarity with command line interfaces.
**5. Sitemap Extractor Tool:** This online tool is user-friendly and doesn't require any downloads or coding knowledge. However, it may not be suitable for very large sitemaps.

Remember, the best method depends on your specific needs and comfort level with these tools.

## 1) Google Sheets

I found a simple sitemap extractor script that will extract the list of URLs from the Sitemap in Google Sheets in less than 5 seconds, pretty impressive, isn’t it? Give it a try.

Here the Google Sheet that act as a sitemap url extractor:

1. Make a copy of it

2. Add the sitemap URL in the cell B2 (example: https://www.google.com/sheets/sitemaps.xml)

3. The list of URLs will appear automatically in column D

Done! You have just converted your sitemap to a URL list.

## 2) Screaming Frog

For this second method you need to install the SEO software Screaming Frog to convert any sitemap xml to a url list. This method works pretty well also for sitemap index file that are the ones that contain list of sub-sitemaps.

Here the steps:

1. Open Screaming Frog SEO Spider Tool

2. Mode>Select List

3. Upload > Download Sitemap > Add Sitemap xml URL

Done!

## 3) Python

1. Open Google Colab

2. Enter the sitemap.xml URL
3. 
4. Click on the play button on the left

5. Navigate to the folder and you will find the url.txt file that can be easily downloaded 


## 4) Terminal

1. Open your terminal
   
2. Enter this command (remember to replace the sitemap URL)-> curl -s https://www.google.com/sheets/sitemaps.xml

Done!

## 5) Sitemap URL Extractor tool

This option is really handy and allows you to convert sitemap.xml to url list in seconds thanks to the clean and user friendly UI.

1. Open the sitemap URL extractor

2. Add the XML sitemap URL/sitemaps.xml

3. Export the data



I hope you find it useful.

If you are aware of other options, just let me know and I will add them to the list.

If you want to optimize or analyzing your Sitemap XML File, you can refer to my article Maximizing Your Website's SEO Potential: A Comprehensive Guide to Analyzing Your Sitemap XML File.
