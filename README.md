# Is Average Rating of Recipes Correlated to Calories?! 

## Introduction
In society where people are becoming progressively more conscious about healthy eating and diet culture, we wonder how this would affect their perception of whether a meal was good or bad. Many health-conscious people hyper-focus on calorie counting and restrictive eating. Thus, we ask the question: Does the number of calories in a recipe affect the average rating of the food? By proposing this question, we investigate whether people’s perception of higher calorie recipes is worse rated or if they are simply more delicious.

We were given two datasets containing recipes and ratings respectively. For the recipes dataset, it contained the information of 83782 recipes with calories varying from 0 to 45,609 on food.com. The 10 columns are as follows:

The second dataset with information on user ratings of different recipes consisted of 731,927 total reviews. This dataset contains the following 5 columns:

The columns that are relevant to our questions were `'nutrition'` (from the recipes dataset) and `'rating'` (from the rating dataset.) The `'nutrition'` column consisted of calories (#), total fat (PDV), sugar (PDV), sodium (PDV), protein (PDV), saturated fat (PDV), carbohydrates (PDV). As our question focuses on the effect of calories on average rating, we extracted each value from the nutrition list and saved it as individual columns. From there, we took ​​`'calories'` for further analysis. As for the `'rating'` column, it included information about how each user rated a certain recipe (from 1 to 5). Our question looked more at how each recipe with individual calories differed in rating, so we found it relevant to take the average rating for each recipe. Therefore, we grouped by recipes, found the mean rating for each recipe and assigned a new column named `'avg_rating'`. 

## Clearning and EDA

## Assessment of Missingness

## Hypothesis Testing
