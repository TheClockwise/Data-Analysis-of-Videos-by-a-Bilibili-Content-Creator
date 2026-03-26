# Data Analysis of Videos by a Bilibili Content Creator

# Project Title
Bilibili Video Data Analysis

## 1. Project Overview
This project analyzes the performance of six videos from a personal Bilibili channel during the first 10 days after publication. The data is organized into a structured format for subsequent analysis.

## 2. Background and Motivation
I am a statistics student and a Bilibili content creator. Through this project, I aim to:
- Understand performance differences across various video types
- Evaluate the correlation between views and other variables
- Apply statistical methods to real-world data to gain practical experience

## 3. Data Source
- Data exported from the Bilibili Creator Dashboard
- Export date: March 23, 2026

## 4. File Structure
- `data/Video_performance_over_time.csv`: Daily metrics (views, engagement counts, etc.)
- `data/Video_information.csv`: Video metadata (duration, category, cover click score, etc.)

## 5. Data Dictionary

| File | Variable | Description |
|------|-------|-------------|
| Video_performance_over_time | bv_number | Unique video identifier |
| | date | Date of statistics |
| | days_since_publish | Number of days after publication (0 = day of publication) |
| | views | Daily new views |
| | new_followers | Daily new followers |
| | unfollows | Daily unfollows |
| | likes | Daily new likes |
| | danmaku | Daily new danmaku (scrolling comments) |
| | comments | Daily new comments |
| | shares | Daily new shares |
| | favorites | Daily new favorites |
| | coins | Daily new coins (Bilibili virtual currency) |
| Video_information | bv_number | Unique video identifier |
| | video_title_short | Short video title |
| | video_title_en | Full video title (English) |
| | video_title_tc | Full video title (Traditional Chinese) |
| | video_title_sc | Full video title (Simplified Chinese) |
| | publish_date | Publication date |
| | duration_sec | Video duration (seconds) |
| | category | Content category (Gaming / Music / Entertainment) |
| | cover_click_score | Cover click-through rating (1–5, out of 5) |
| | bounce_rate | 3-second bounce rate (percentage, tracked for the first 14 days after publication) |
| | avg_playback_progress | Average playback progress (percentage, cumulative to date) |
