# Welcome

## Machine Learning

- Grew out of work in AI
- New capability for computers

Examples:

- Database mining
  Large datasets from growth of automation/web.
  E.g., Web click data, medical records, biology, engineering

- Applications can't program by hand.
  E.g., Autonomous helicopter, handwriting recognition, most of Natural Language Processing (NLP), Computer Vision.

- Self-customizing programs
  E.g., Amazon, Netflix product

- Understanding human learning (brain, real AI).

## What is Machine Learning?

### Machine Learning definition

- Arthur Samuel (1959). Machine Learning: Field of study that gives computers the ability to learn without being explicitly programmed.

- Tom Mitchell (1998). Well-posed Learning Problem: A computer program is said to _learn_ from experience E with respect to some taskT and some performance measure P, if its performance on T, as measured by P, improves with experience E.

#### Problem 1

Suppose your email program watches which emails you do or do not mark as spam, and based on that learns how to better filter spam. What is the taskTin this setting?

[ ] Classifying emails as spam or not spam.
[ ] Watching you label emails as spam or not spam.
[ ] The number(or fraction)of emails correctly classified as spam/not spam.
[ ] None of the above-this is not a machine learning problem.

### Machine learning algorithms

- Supervised learning
- Unsupervised learning

Others: Reinforcement learning, recommender systems.

Also talk about: Practical advice for applying learning algorithms.

#### What is Machine Learning

Two definitions of Machine Learning are offered. Arthur Samuel described it as: "the field of study that gives computers the ability to learn without being explicitly programmed." This is an older, informal definition.

Tom Mitchell provides a more modern definition: "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."

Example: playing checkers.

E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.

In general, any machine learning problem can be assigned to one of two broad classifications:

Supervised learning and Unsupervised learning.

#### Problem 2

You're runningacompany,and you want to develop learning algorithms to address each
of two problems.

Problem1:You havealarge inventory of identical items.You want to predict how many
of these items will sell over the next3months.

Problem2:You'd like software to examine individual customer accounts,and for each
account decide if it has been hacked/compromised.

Should you treat these as classification or as regression problems?

[ ] Treat both as classification problems.
[ ] Treat problem 1 as a classification problem, problem 2 as a regression problem.
[ ] Treat problem 1 as a regression problem, problem 2 as a classification problem.
[ ] Treat both as regression problems.

### Supervised Learning

In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.

Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

Example 1:

Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.

We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

Example 2:

(a) Regression - Given a picture of a person, we have to predict their age on the basis of the given picture

(b) Classification - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.

#### Problem 3

Of the following examples, which would you address using an **unsupervised** learning algorithm? (Check all that apply.)

[ ] Given email labeled as spam/not spam, learn a spam filter.
[ ] Given a set of news articles found on the web, group them into set of article about the same story.
[ ] Given a database of customer data, automatically discover market segments and group customers into different market segments.
[ ] Given a dataset of patients diagnosed as either having diabetes or not, learn to classify new patients as having diabetes or not.

### Unsupervised Learning

Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.

With unsupervised learning there is no feedback based on the prediction results.

**Example:**

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a [cocktail party](https://en.wikipedia.org/wiki/Cocktail_party_effect)).
