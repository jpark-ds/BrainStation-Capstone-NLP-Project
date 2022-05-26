# Capstone Project 
***

## Introduction

App stores, such as Google’s Play Store, Apple’s App Store, or Shopify’s App Store are distribution platforms<sup>1</sup> that enable users to download and install software applications (i.e., apps) on their devices and used for a wide range of purposes. An important aspect to these app stores is that it enables users to then provide ratings on these apps in the form of stars, typically on a scale of 1 to 5 stars (i.e., 5 stars being the highest), and feedback in the form of a text review. These apps can accumulate daily reviews that accumulate up to 4,000 reviews per day for very popular apps<sup>1,2</sup>.  

Previous studies<sup>2-4</sup> have shown that user reviews can contain pertinent information on bug reports, feature requests, and sentiment of user experiences. This high-quality feedback is important not only for the user community but also for app developers, project managers, and other stakeholders<sup>1-4</sup>. However, reviews also contained low-quality feedback that were insults or spam and did not provide useful constructive critiques.

With the integral role of app stores to our digital world, volume of user reviews accumulating, and the established communication channel these app stores serve between users and different stakeholders, gathering and understanding high-quality app reviews are a critical step in enhancing the overall user experience and business for an app developer.

Researchers<sup>2-4</sup> have conducted sentiment analysis and topic modeling on the Google Play Store and Apple App Store reviews. Only one study<sup>5</sup> to date was identified to have conducted sentiment analysis on Shopify’s App Store for classifying unhappy versus happy reviews on a down sampled and smaller dataset. However, there were no clear actionable insights that can be achieved on increasing happy reviews for the user community. In addition, the nature of the review topics that Shopify’s App store contains have not been fully investigated in the literature. The Shopify App store is a unique distribution platform that focuses on supporting users/merchants on their internet commerce infrastructure<sup>[†]</sup>. The software applications in the store represent a unique distribution of apps that are focused on that e-commerce infrastructure. Whether topics overlap with previous studies across distribution platforms remain unclear.

Taken altogether, the goals of this capstone project are to identify the words predictive of sentiment and identify the different topics that these reviews contain so that I can automate the process of gathering and directing high-quality feedback to relevant stakeholders for optimizing the overall user experience.

[†]: https://investors.shopify.com/resources/default.aspx


## Jupyter Notebooks Outline
Brief descriptions about each Jupyter Notebook uploaded into this repository are provided below. The data and saved files for successfully running the notebooks are not included due to file size limitations.

| Jupyter Notebook      | Description |
| ----------- | ----------- |
| 01 - Data-Cleaning-and-Exploration-Part-1      | Initial data wrangling of reviews, review ratings, and exploratory data analysis.       |
| 02 - Text-Pre-processing-and-Language-Detection-Part-2   | Applying text pre-processing steps to review texts in preparation for downstream analysis along with implementation of a pre-trained hierarchical classifier for separating English-only reviews.        |
| 03 - Vectorization-and-Sentiment-Analysis-Part-3   | Transform reviews into a Document-Term Matrix and fit a logistic regression model to identify words predictive of postive and negative reviews.       |
| Topic-Modeling-and-Model-Exploration-Part-4   | Transform reviews into several different data formats as inputs to gensim's Latent Dirichlet Allocation for uncovering hidden themes or topics within the reviews.        |


# References
1. Pagano, D. & Maalej, W. User feedback in the appstore: An empirical study. in 2013 21st IEEE International Requirements Engineering Conference, RE 2013 - Proceedings 125–134 (IEEE Computer Society, 2013). doi:10.1109/RE.2013.6636712.
2. Guzman, E. & Maalej, W. How do users like this feature? A fine grained sentiment analysis of App reviews. in 2014 IEEE 22nd International Requirements Engineering Conference, RE 2014 - Proceedings 153–162 (Institute of Electrical and Electronics Engineers Inc., 2014). doi:10.1109/RE.2014.6912257.
3. Maalej, W., Kurtanović, Z., Nabil, H. & Stanik, C. On the automatic classification of app reviews. Requirements Engineering 21, 311–331 (2016).
4. Triantafyllou, I., Drivas, I. C. & Giannakopoulos, G. How to utilize my app reviews? A novel topics extraction machine learning schema for strategic business purposes. Entropy 22, 1–21 (2020).
5. Rustam, F. et al. Classification of Shopify App User Reviews Using Novel Multi Text Features. IEEE Access vol. 8 30234–30244 (2020).