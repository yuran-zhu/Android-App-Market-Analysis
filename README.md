# Android-App-Market-Analysis

## I. Introduction

As science and technology have been advanced swiftly, app markets are full of opportunities as well as challenges. While many public datasets provide Apple App Store data, there are not many counterpart datasets and visualization available for Google Play Store apps anywhere on the web. For the app-making business, we aim to provide the developers with some actionable insights in the Android market through the visualization of Google Play Store apps data.

## II. Related Work
This problem originated from some articles about the Apple Store policy conflicts that we read. Then a question occurs to us: what if the developers want to switch from IOS to Android and they need to know about the app developing situation in the Android market? While the Android market is as important as the IOS market in many countries, there is not so much public dataset and analysis for it. Before we walk further into this problem, we want to question, wrangle, and explore the datasets we found on Kaggle using the visualizing and storytelling skills we discussed in class.

## III. Data

The data is scraped from the Google Play Store and is available at Kaggle. The portfolio contains two datasets and we plan to analyze both of them for developing a comprehensive data exploration. Therefore, the data we use is spread across two tables and we'll join them together in further analysis.

One dataset (`googleplaystore.csv`) includes app information, having values for category, rating, size, download counts. etc. The other dataset (`googleplaystore_user_reviews.csv`) contains data for app reviews, each row refers to a single review and corresponding analysis for an App.

## IV. Problems to Explore

With the datasets, we expect to answer the following questions that are interesting to both app developers and users.
- What categories of apps are most available/popular and receive higher ratings?
- Do paid apps perform better than free apps? For paid apps, do those with higher ratings commonly have a price in a reasonable range? What categories tend to set higher prices?
- Do users prefer apps with lighter size? That is to say, for each category, are top-rated apps tend to have less size? Can we find a reasonable range of an app size?
- Among current apps, which categories receive the most positive reviews? What factors make an app positively/negatively evaluated?

