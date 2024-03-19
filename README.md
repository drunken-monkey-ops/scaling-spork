# scaling-spork

### Background

Reddit is a popular online community where users engage in discussions across various topics through posts and comments. The platform is organized into user-created boards called subreddits, which are specialized forums that enable users to engage in discussions about topics that interest them. The Webis-TLDR-17 Corpus dataset, used in this investigation, contains around 4 million content-summary pairs from the Reddit dataset, providing a valuable resource for researchers and practitioners interested in natural language processing and summarization tasks.

### Computational Experiments

The report details the computational experiments conducted, including the setup of a distributed system with Apache Spark and HDFS, scalability analysis (vertical and horizontal), and strong and weak scaling experiments. Performance measurements for different core counts in both strong and weak scaling scenarios are presented, showcasing the system's efficiency and scalability.

### Results

The investigation yielded insightful results, such as top authors based on content length, average content length by author, and subreddits where authors frequently post. Tables and graphs illustrate the findings, providing a comprehensive overview of author behaviors and contributions on Reddit.

### Discussion and Conclusion

Discussions cover the results obtained from the dataset analysis, focusing on author behaviors, content length, and subreddit contributions. The experiments' setup, challenges faced, and recommendations for improving the distributed system architecture are also discussed. The conclusion summarizes the successful deployment of the distributed architecture, highlighting the achievements in vertical and horizontal scaling and the comparative analysis of weak and strong scaling.


### Architecture

![image](https://github.com/drunken-monkey-ops/scaling-spork/assets/66768769/a02c2aff-d2fc-4dcf-b324-c2763cfa6a2f)

### Experiments results

#### Strong scaling 

![image](https://github.com/drunken-monkey-ops/scaling-spork/assets/66768769/4d7dc66b-34db-43e8-8cfa-921fa3ac4eaa)

#### Weak scaling 

![image](https://github.com/drunken-monkey-ops/scaling-spork/assets/66768769/d7b6aac6-297e-4041-a28d-ce31f055d880)

