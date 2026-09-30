# Cars Regression Session Prompts

These are the prompts I used with my AI assistant (GitHub Copilot) to create and refine `cars_regression.ipynb`, including the clarifying questions I was asked and my answers.

## Prompt 1

> Using the current branch, I want to create a jupyter notebook where we will conduct linear regression on the cars.csv file. Use sklearn to complete the linear regression and calculate the r^2 value. Then create a graph to visually show engine size vs price using seaborn. Do not run any checks or tests, I will do that.

### Clarifying Questions & Answers

**Notebook filename** — What should the notebook be named?
> cars_regression.ipynb

**Regression scope** — Simple regression (enginesize -> price) matching the plot, or multiple regression with more numeric features?
> Simple: enginesize -> price only

**Train/test split** — Evaluate with an 80/20 train/test split, or fit and score on the full dataset?
> Train/test split (80/20)

**Dependencies** — pyproject.toml has no deps yet. Add jupyter, pandas, scikit-learn, seaborn, matplotlib to pyproject.toml (you run uv sync yourself), or are they handled separately?
> Add to pyproject.toml (I'll run uv sync)

## Prompt 2

> Start implementation

## Prompt 3

> Update the plot to make the test and train data point colors more distinguishable from each other. Add a legend to specify graph components. Remove the r^2 value from the plot title. Add the test and train r^2 values onto the graph.

## Prompt 4

> Add labels to the legend for the black line and the grey around it.

## Prompt 5

> Confidence interval was added to the legend successfully, but the regression line still is not there.

## Prompt 6

> That solution worked. Create a markdown file called cars_regression_narudser_prompts.md and store all my prompts along with questions I was asked and then my answers from this entire session.
