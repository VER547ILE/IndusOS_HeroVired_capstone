IndusOS_HeroVired_capstone

Overview

Established in May 2015, Indus OS is a homebred system apps company, building India’s only content and commerce platform for users to discover and consume digital content &amp; services in the language of their choice. An indigenous platform, Made in India, for Indians, Indus OS, is built on three pillars of innovation, simplification and localization for delivering a robust personalized experience to the Indian consumer. Over the past years, Indus OS has developed core system apps to suit the specific needs of the Indian consumers, by addressing the real problems like – lack of digital awareness, low smartphone adoption, linguistic challenges and unavailability of local content and services. Through its breakthrough innovations (such as Minus One screen, messenger, keyboard, and Appstore) Indus OS brings together app developers, smartphone brands and users on a single India centric platform. Indus OS also has its very own App Store - Indus App Bazaar with over 400,000 applications, which is built on a strong personalized recommendation engine delivering users the option to download apps that would best serve their needs. Indus App Bazaar provides the users with a seamless experience in English and 12 regional languages, including Hindi, Gujarati, Marathi, Tamil, Telegu, Urdu, Malayalam, and Bengali, among others. Currently, Indus has a fast-growing user base of over 200 Million Indians on the back of 10+ smartphone brand partnerships (Samsung, Gionee, Micromax, Itell, Karbonn, etc) in India. Indus OS is available in English &amp; 23 Indian regional languages, spoken by over 95% of the Indian population. With a vision of digitally connecting 1 Billion Indians on an INDIAgenous content &amp; commerce platform, Indus OS is constantly striving to adapt its existing portfolio by introducing new features to enrich the user experience in their native language, aligned with government initiatives, especially geared towards supporting the roadmap of Digital Bharat.

Business Objectives

The company can use the insights from the analysis to improve its marketing efforts for apps. By understanding which factors drive downloads and reviews, the company can target its marketing campaigns more effectively to increase app visibility and drive more downloads.

Problem Statement

Indus App Bazaar is trying to understand the factors that contribute to the success of mobile apps, including the number of downloads, user reviews, and payments. The goal of this data analysis project is to identify the key success factors for mobile apps and provide insights to Indus App Bazaar on how to improve app selection and curation for its users.

Dataset

It contains 4 .csv files. You need to concatenate all the files before performing the tasks.

App Name: Name of the App used 
Size (in Bytes)
App id : Identification number of the app 
Currency: Currency used for purchasing
Price: Amount in the currency mentioned
Rating (All): User Rating counts (for all version)
Rating (Current) : User Rating counts (for current version)
Avg rating (All) : Average User Rating value (for all version)
Avg rating (Current): Average User Rating value (for current version)
Version : Latest version code
Rating (Content): Content Rating
Preference: Primary Preference for app
Supp Devices: Number of supporting devices
Screenshot : Number of screenshots shown for display
Supp Lang: Number of supported languages
Vpp Lic: Vpp Device Based Licensing Enabled

Tools/Software:
Jupyter Notebook for Python, Excel

Tasks:

Task 1 - Combining and Cleaning Datasets

Data cleaning is the process of identifying and correcting or removing inaccurate, incomplete, irrelevant, or improperly formatted data within a dataset. It is important because it can significantly impact the accuracy and reliability of any analyses or models built on the data. Data cleaning helps to ensure that the data is consistent, complete, and error-free, reducing the risk of making incorrect or misleading conclusions based on faulty data.

The datasets provided will be of different formats. Combine the datasets using Excel based on common fields.
Clean the dataset by removing duplicate values, missing values and irrelevant values.
Use data transformation if needed so that the data is consistent 

Submission Format - .xlsx file

Task 2 - Analysis and Visualisation of Data 

Data visualization is the graphical representation of data and information. It helps to communicate complex data and insights in a simple and understandable way. Visualizations can help to identify patterns, trends, and correlations that may not be easily apparent in raw data. They also enable decision-makers to quickly analyze and understand large amounts of data, which can aid in making more informed decisions. Overall, data visualization is a powerful tool for exploring, analyzing, and communicating insights from data.

Use Excel to analyze the dataset provided by Indus for app analytics.
Create summary statistics for key variables, including the number of downloads, ratings, and reviews. Calculate measures such as mean, median, and standard deviation.
Visualize the data using histograms, scatter plots, and bar charts to explore the relationships between app size, price, number of supported devices and languages, and the number of downloads and ratings.
Utilize statistical analysis tools available in Excel, such as correlation analysis and regression analysis, to identify any significant correlations between variables.
Draw conclusions based on the analysis and provide recommendations to Indus on how they can improve their app selection and marketing strategies.


Main features Indus is trying to identify:

Investigate how the size of the app affects the number of downloads, user reviews, and payments. Analyze the relationship between app size and these variables using appropriate statistical methods.
Explore the impact of app pricing on its success. Determine if there is a correlation between app price and the number of downloads or ratings. Analyze different pricing strategies and their effectiveness.
Examine the influence of user ratings and reviews on app success. Identify factors that affect the ratings and reviews and assess their impact on app performance.
Analyze app categories and preferences to identify popular choices among users. Determine if certain app categories have higher downloads or ratings.
Investigate if the number of supporting devices, languages, and screenshots correlates with app success. Use correlation analysis to assess the relationship between these variables and app performance.
Assess the impact of Vpp Device Based Licensing on app success. Analyze if there is a significant difference in downloads or ratings between apps that use Vpp Device Based Licensing and those that don't.


Submission Format - .xlsx file

Files uploaded in the repository:
Dataset folder --> Dataset files  --- AppleStore1.csv , AppleStore2.csv , AppleStore3.csv , AppleStore3.csv , AppleStore4.csv
Code folder --> combined_dataset1.xlsx , Dashboard_Task2.xlsx , Python File for Cleaning Combined Dataset.ipynb
