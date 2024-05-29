# Investigating-Netflix-Movies 

## Project Overview
Netflix believes that the average duration of movies has been declining.This data analysis project aims to do initial research and delve into the Netflix data to determine whether movie lengths are actually getting shorter and explain some of the contributing factors, if any. Additional Questions: 
    * What was the most frequent movie duration in the 1990s?
    * A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s.

## The Data
Netflix! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.
The primary dataset used for this analysis is the "netflix_data.csv" file, containing detailed information. The following table detailing the column names and descriptions. This data does contain null values and some outliers, but handling these is out of scope for the project.

### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

## Prerequisites 
Before you begin, ensure you have met the following requirements: 
  * Python 3.6 or higher [Download Here](https://www.python.org/downloads/)
  * Pandas
  * Matplotlib

## Steps to complete 
  * Filter the data for movies released in the 1990s
  * Find the most frequent movie duration
  * Count the number of short action movies from the 1990s
  * Answer the question "Are movies getting shorter"

## Results/ Findings 
  * The most frequent movie duration in the 1990s: 100
  * The number of short action movies released in the 1990s: 8
  * Are movies getting shorter: No
