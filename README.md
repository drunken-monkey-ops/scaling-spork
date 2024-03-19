# scaling-spork

### Overview

This README file provides a comprehensive summary of the Group-16 report on the investigation of authors in the Reddit dataset. The report delves into the behaviors and contributions of users on the Reddit platform, focusing on the unique features of Reddit, such as upvoting, downvoting, controversiality scores, and distinguished comments. The report also includes computational experiments, results, discussions, and conclusions.

### Background

Reddit is a popular online community where users engage in discussions across various topics through posts and comments. The platform is organized into user-created boards called subreddits, which are specialized forums that enable users to engage in discussions about topics that interest them. The Webis-TLDR-17 Corpus dataset, used in this investigation, contains around 4 million content-summary pairs from the Reddit dataset, providing a valuable resource for researchers and practitioners interested in natural language processing and summarization tasks.

### Data Format

The Webis-TLDR-17 Corpus dataset is stored in a JSON (JavaScript Object Notation) file format. JSON is a lightweight, versatile, and programming language-independent format that facilitates data exchange and representation. The schema of the JSON object in the dataset includes fields like author, body text, content, summary, subreddit, and more.

### Computational Experiments

The report details the computational experiments conducted, including the setup of a distributed system with Apache Spark and HDFS, scalability analysis (vertical and horizontal), and strong and weak scaling experiments. Performance measurements for different core counts in both strong and weak scaling scenarios are presented, showcasing the system's efficiency and scalability.

### Results

The investigation yielded insightful results, such as top authors based on content length, average content length by author, and subreddits where authors frequently post. Tables and graphs illustrate the findings, providing a comprehensive overview of author behaviors and contributions on Reddit.

### Discussion and Conclusion

Discussions cover the results obtained from the dataset analysis, focusing on author behaviors, content length, and subreddit contributions. The experiments' setup, challenges faced, and recommendations for improving the distributed system architecture are also discussed. The conclusion summarizes the successful deployment of the distributed architecture, highlighting the achievements in vertical and horizontal scaling and the comparative analysis of weak and strong scaling.
