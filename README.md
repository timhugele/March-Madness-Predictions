# March-Madness-Predictions

#### Team Members

|Name     |  Github   | 
|---------|-----------------|
|[Tim Hugele](https://github.com/timhugele)


### Data Source
* The data for this project was obtained from a [Kaggle](https://www.kaggle.com/c/mens-machine-learning-competition-2019/discussion/89645) user. The source of the data from is from [Kaggle](https://www.kaggle.com/c/mens-machine-learning-competition-2019).

### Jupyter notebooks
* Tim: [NCAA_Tourney_Predictions.ipynb](https://github.com/timhugele/March-Madness-Predictions)

### Project Presentation
* [Google Slides](https://docs.google.com/presentation/d/157XFpjJwZ1Xch8e_5fUwqxTeegJCJygJdkIOSwKmgb8/edit?usp=sharing)


### Problem Summary
* Using the data from Kaggle I was attempting to create the best performing March Madness Bracket possible. My target audience would be anyone attempting to omptimize their March Madness bracket making strategy, and perhaps win money betting on it.

### Metrics

* The main metric that I used for this project is logloss. The initial reason for doing so was that it was the metric officially being used in the Kaggle competition. I also used it because it was a pretty clear indicator of the predicting power of the model. It is a metric on a 0-1 scale, with a lower score being superior.
* However, I also ended up judging my model's success on how many of the 67 (including the 4-play in games) I correctly predicted. In the future, I would also like to create a metric that weights later round games heavier than early round games.

### Key Takeaways
* Higher seeds usually win, but once you get deeper into the tournament the top seeds often times get knocked off. Only once in the tournament's history have all four number one seeds reached the final four.
* Offensive and Defensive Efficiency track pretty well with the seedings, and are ultimately not sufficient to bet on alone.

### Initial Results
* Betting on Adjusted Offensive Efficiency and Adjusted Defensive Efficiency is a better predictor than predicting on the betting odds, but ultimately mostly stuck to picking the higher seed to win.

### Next Steps
* I would like to test a greater number of features than the four (Team 1 and Team 2 Offensive and Defensive Adjusted Efficiency) that I used during the first steps of the project.
* I would like to engineer some new features as well. Some ideas for engineered features are TrueSkill rankings, school's distance from game location, average team height, amongst others.
