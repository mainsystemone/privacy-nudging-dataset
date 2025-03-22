# Dataset Description: Privacy Personalization and User Behavior on Gegli Social Network

## Overview
This dataset supports the analysis conducted in the study evaluating the impact of a gamified nudging method on user privacy personalization and engagement within the Gegli social network platform.

## Contents
The dataset includes user interaction data extracted from the Gegli social network and grouped into two categories:
- **Group 1**: Users who personalized their privacy settings using the gamified nudge.
- **Group 2**: Users who did not personalize their privacy settings.

Each CSV file contains the following:
- `user_id`: Anonymized unique identifier for each user.
- `user_group`: Indicates Group 1 or Group 2 membership.
- A feature column such as `page_views`, `sent_messages`, `received_likes`, etc.

### Included CSV Files:
1. `page_views.csv`
2. `sent_messages.csv`
3. `received_messages.csv`
4. `sent_likes.csv`
5. `received_likes.csv`
6. `sent_friend_requests.csv`
7. `received_friend_requests.csv`

## Method of Collection
Data was extracted directly from the backend of the Gegli platform using SQL queries with proper filtering for users who had more than 60 interactions and were active for over eleven months. The exported data was anonymized and preprocessed in compliance with data protection regulations.

## Usage Notes
These files were used for statistical comparison using the Mann-Whitney U test after normality checks with the Shapiro-Wilk test. Researchers can replicate or extend the analysis using the included CSV files.

## Contact
For academic use or dataset access inquiries, please contact the corresponding author.

