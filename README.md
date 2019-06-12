# ACT Scores
### Analysis of ACT scores from California high schools

![act](act.jpg)
<br>
<br>
What factors affect students' success on standardized test scores? What relationship do ACT scores have with poverty rates, graduation rates, dropout rates, and more? Can schoolwide performance be predicted based on these factors, and how could we improve student scores in the future?
<br>
<br>
This project aims to analyze ACT test scores from hundreds of California high schools. The first notebook uses data visualization tools to explore the relationship between the variables. The second notebook attempts to model the average ACT scores based on several factors from each school. 

[EDA (Data visualization, relationship analysis)](act_scores.ipynb)
<br>
[Modeling & Prediction](act_scores_ml_model.ipynb) - Linear regression ; Decision Trees: Random Forest


---

Preview of Results:
<br>
### Linear Regression Predictions
![](actualvpredicted.png)
<br>
<br>
### Random Forest Preview
![](small_tree.png)

##### Results from the Random Forest Regressor showed we can predict schools' average ACT score with about 94% accuracy!

<br>
##### Conclusion:
Student test scores are the complex result of many environmental and individual factors: achievement levels (high-achieving students in schools with rigorous and stimulating curriculums likely to score higher), cultural / racial / ethnic background, socioeconomic status (thus higher poverty rates would be negatively correlated with lower scores), and psychological state (student motivation, focus, ability to handle pressure, time management, etc). Improving student scores would come down to investigating each of these elements in further detail. For instance, improving school curriculum and fostering healthy educational environment for students could positively influence scores. 
