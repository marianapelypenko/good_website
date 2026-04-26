---
# Do not edit the text between these lines!
layout: default
---

# Analysis for Continuous Improvement (EX 09)

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="good_website/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Summary of the analysis

This project analyzes survey data from COMP110 to explore whether pre-lecture videos are associated with higher student understanding. I combined multiple datasets, selected relevant columns, and converted the data into a format suitable for analysis.

Using Python and seaborn, I created several visualizations, including a scatterplot to examine the relationship between pre-lecture video ratings and understanding, a boxplot to compare distributions of understanding across different ratings, and a bar chart to show how students rated the usefulness of pre-lecture videos.

Additionally, I implemented a helper function to filter the dataset and focus on students who rated pre-lecture videos highly, allowing for a more targeted analysis. These steps helped identify patterns in the data and provided insight into how students perceive pre-lecture videos and their potential impact on learning.

<img src="/static/imgs/scatter1.png" alt="Scatterplot of pre-lecture videos vs understanding" width="500"/>

<img src="/static/imgs/boxplot.png" alt="Boxplot of understanding by video rating" width="500"/>

<img src="/static/imgs/bar.png" alt="Distribution of pre-lecture video ratings" width="500"/>


## Conclusion of the analysis

This project explores how pre-lecture videos might improve student understanding in COMP110 using survey data collected from students. The goal of the analysis is to evaluate whether students who believe pre-lecture videos are helpful also report higher levels of understanding in the course.

To investigate this, I combined and processed survey datasets, selected relevant variables, and created multiple visualizations using Python and the seaborn library. These included a scatterplot, a boxplot, and a bar chart to examine patterns in student responses.

The results suggest that while many students view pre-lecture videos positively, the relationship between these videos and understanding is not strongly consistent across all students. This indicates that pre-lecture videos may benefit some learners, but are not the only factor influencing success in the course.