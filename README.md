# Machine-Learning-Potential-Customers-Prediction

# ExtraaLearn Project

## Context
The EdTech industry has experienced significant growth in the past decade, with the Online Education market projected to be worth $286.62 billion by 2023, exhibiting a compound annual growth rate (CAGR) of 10.26% from 2018 to 2023. The surge in online education, driven by features such as ease of information sharing, personalized learning experiences, and transparent assessment, has made it a preferred choice over traditional education. The Covid-19 pandemic has further accelerated the growth of the online education sector, attracting new customers and giving rise to numerous companies in the industry.

Amidst this growth, ExtraaLearn, an early-stage startup, focuses on providing programs on cutting-edge technologies to students and professionals, aiding them in upskilling/reskilling. As the company generates a substantial number of leads regularly, one of its challenges is identifying which leads are more likely to convert into paid customers. As a data scientist at ExtraaLearn, your task is to analyze the leads data and build a machine learning model to identify potential conversions, understand the factors influencing the lead conversion process, and create a profile of leads likely to convert.

## Objective
The primary objectives of the ExtraaLearn project are as follows:

1. Analyze and build an ML model to identify leads more likely to convert to paid customers.
2. Identify the key factors influencing the lead conversion process.
3. Create a profile of leads that are likely to convert.

## Data Description
The dataset provided contains various attributes of leads and their interactions with ExtraaLearn. The data dictionary is as follows:

- **ID:** ID of the lead
- **age:** Age of the lead
- **current_occupation:** Current occupation of the lead (Values: 'Professional', 'Unemployed', 'Student')
- **first_interaction:** How the lead first interacted with ExtraaLearn (Values: 'Website', 'Mobile App')
- **profile_completed:** Percentage of profile filled by the lead on the website/mobile app (Values: Low - 0-50%, Medium - 50-75%, High - 75-100%)
- **website_visits:** Number of times a lead visited the website
- **time_spent_on_website:** Total time spent on the website
- **page_views_per_visit:** Average number of pages viewed during website visits
- **last_activity:** Last interaction between the lead and ExtraaLearn

**Interaction Details:**
- **Email Activity:** Seeking details about the program through email, representative sharing information, etc.
- **Phone Activity:** Phone conversation with representative, SMS conversation with representative, etc.
- **Website Activity:** Interaction on live chat with representative, updating profile on the website, etc.
- **print_media_type1:** Flag indicating if the lead saw ExtraaLearn ad in the Newspaper.
- **print_media_type2:** Flag indicating if the lead saw ExtraaLearn ad in the Magazine.
- **digital_media:** Flag indicating if the lead saw ExtraaLearn ad on digital platforms.
- **educational_channels:** Flag indicating if the lead heard about ExtraaLearn through education channels like online forums, discussion threads, educational websites, etc.
- **referral:** Flag indicating if the lead heard about ExtraaLearn through reference.
- **status:** Flag indicating whether the lead converted to a paid customer or not.

