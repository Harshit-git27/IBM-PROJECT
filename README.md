Project Decription:-
Why I did this
 What’s going on here?

1. **I made fake employees.**

   * 500 of them.
   * Gave them a random number of years of experience (0–20), ages (22–60), and one of three education levels.
   * Added a random "industry factor" to spice things up a bit (because, let’s be real, industry makes a big difference in salary).

2. **Then I gave them all salaries.**

   * I used a totally made-up formula with some noise thrown in so the data isn’t *too* clean.
   * It’s not perfect, but it’s believable enough for a model to learn something from it.

3. **Now enter the models.**

   * I trained a few regressors: Random Forest, Gradient Boosting, and good old Linear Regression.
   * Then I threw them all together in a Voting Regressor because... teamwork, right?

4. **I tested how well each one did.**

   * Metrics-wise, I used RMSE and R², just to get a sense of how far off they were.
   * As expected, the ensemble model did best overall. Not perfect, but it held its own.

5. **I plotted the actual vs predicted salaries.**

   * Not because it was necessary, but because I wanted to see how messy things looked.
   * The scatter plot isn’t too shabby, actually.

 What I got out of it

* Building fake data is kind of fun.
* Ensemble models are solid when you don’t fully trust any one model on its own.
* Even totally synthetic data can teach you a lot if you treat it like a real dataset.
* Making things visual (like that final scatter plot) always helps spot trends—or mistakes.

If I had more time...

* I’d try it on a real dataset (maybe from Kaggle).
* Add better feature interpretation (SHAP values or feature importance).
* Do proper cross-validation instead of just one train-test split.
* Maybe mess with stacking models instead of just voting.

( I made fake employee data and tried to predict their salaries using different regression models. It's not production code—just a sandbox project for fun and learning. And honestly? Pretty proud of how it turned out. )


