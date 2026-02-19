# DIG Framework


## Step 1 - Description

#### chatGPT will explain or describe what's in the file as quickly and effectively as possible

prompt 1: List all of the columns in the attached dataset and show me one sample of the data from each column in a table

**this will force chatGPT to actually look at every single column in our dataset and gives us a quick overview of the data we're working with**

prompt 2: take five more random samples of the data for each column to make sure you understand the format and type of information in each column

**one sample may be an outlier and therefore misleading. multiple samples help us spot inconsistencies**

	prompt 3: run a quality data on each column. Specifically look for:
	 1. Missing, null, or empty values (give me counts and percentages)
	 2. Unexpected formats or data types
	 3. Outliers or suspicious values

(ask for assumptions?)

**We want chatGPT to tell us if there's anything weird about the data before we proceed with the analysis**

Make a small description of possible problems for data analysis that could come from the anomalies detected

prompt 4: if there's a strange value, select it on table and ask: "what is this value, what does it mean"

**check for follow up questions**

## Step 2 - Introspection

#### Instruct ChatGPT to brainstorm questions it could answer with our data

#### This shows wheter ChatGPT truly gets our data and often surfaces insights we hadn't considered

prompt 1: tell me 10 interesting questions we could answer with this dataset and explain why each would be valuable

**Good questions mean ChatGPT understands our data. Bad questions means there's a misunderstanding that needs fixing before we proceed**

prompt 2: For questions 1, 2, and 3, tell me exactly which columns you'll need to use and whether the current data is sufficient to answer it

**forces ChatGPT to show its wirk and lets us know whether or not we can actually perform these analysis**

prompt 3: What questions do you think someone would want to ask about this data but we can't answer due to missing information

**this surfaces gaps in our dataset and helps us manage expectations about what insights we can uncover**

prompt 4: after creating dummy data (or finding it) that could be used, I can attach it and then: "I just received this dataset from a colleague. Your task is to explore and explain the relationship between this new dataset with the original one and how they might be used to join data together"

pronpt 5: merge the datasets using user id as the primary key

**ask for some of the analysis chatGPT  suggested and keep digging into your dataset**


## Step 3 - Goal Setting

#### To come up with dozens of insights that prove to be useless to a manager, customer, or audience, is frustrating. Set goals

prompt: my goal is {{insert your goal}}

My goal is to understand what content netflix should investin next. Given this goal, which aspects of the data should we focus on

**this helps the AI priotitize what's important and ignore what's not. Remember attention mechanism

ok, I want to create a briefing for my board of directors where we explore track evolving trends. I want it to be detailed and where applicable to have some visualizations.

bonus prompt: What are the key questions someone reading my analysis would ask, and how should we proactively address them


