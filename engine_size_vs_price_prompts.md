# Engine Size vs. Price Notebook — Session Prompts

These are the prompts I used with my AI assistant (GitHub Copilot) to build `engine_size_vs_price.ipynb`. Sharing them for posterity, same spirit as `toms-project-setup-prompts.md`.

## Prompt 1

> would like a jupyter notebook that walks through analyzing cars.csv, not totally on your own, would like linear regression of engine size versus price, use sklearn, so need to update uv proj, we're learning about r-squared, so a cell to show that, or show it on the plot if easy enough, ive created a branch already, and no need for tests, just build the notebook and i will run the steps manually

## Clarifying Questions (from Copilot) and My Answers

**Notebook scope** — Should the notebook include a bit of general EDA (data preview, summary stats, scatter plot) before the regression, or jump straight to the engine size vs price regression?
> My answer: Straight to regression.

**Train/test split** — Use a train/test split (more realistic ML practice) or fit on the full dataset (simpler, keeps focus on r-squared concept)?
> My answer: Train/test split.

**Notebook filename** — What should the notebook file be named?
> My answer: `engine_size_vs_price.ipynb`.

**Dependencies** — Which packages should be added to pyproject.toml via uv?
> My answer: also seaborn, but i use jupyter notebooks in vs code, so prob don't need that stuff as vs code plugins will handle the jupyter stuff

## Prompt 2

> Start implementation

## Prompt 3

> you rock, can i get a engine_size_vs_price_prompts.md file with my prompts, including your questions and my responses, for posterity of this session, including this prompt, thanks

## Prompt 4

> does it make any difference about what is on x or y axis?

## Prompt 5

> update my prompt md file for this session too
