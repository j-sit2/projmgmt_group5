# Predicting House Prices

## 1. Introduction (1 mark)
This project aims to develop a machine-learning model to predict house prices based on various features such as location, size, number of rooms, and amenities. Seneca Company will use the model to assist with pricing decisions and help clients make informed purchasing decisions.

*April 17, 2023*

*Current Version: 2.3*

*Sponsor: Seneca Company*

*Project Manager: Annhanjef Czs*

## 2. Overview (1 mark)
Develop a machine-learning model to predict house prices based on relevant features, deploy the model to assist Seneca Company's pricing decisions and enable their clients to make informed purchasing decisions.

### 2.1 Objectives
The objective of this project is to develop a machine-learning model that accurately predicts house prices based on factors such as location, size, number of rooms, and amenities. This will involve collecting and preprocessing data, selecting an appropriate machine-learning algorithm, training and developing the model, evaluating and refining it, optimizing model hyperparameters, and assessing performance using relevant metrics. We will deliver a well-trained machine-learning model, performance evaluation metrics, a final project report, and all project documents. Seneca Company will use this model to help clients make informed purchasing decisions and assist with pricing decisions.

### 2.2 WBS
![WBS](/WBS.png "WBS")

## 3. Milestones (1 mark)
Provide a list of significant points or events during the execution of the project.

1. Gathering data: Collecting relevant data on house prices, location, size, number of rooms, and amenities from various sources 

2. Explore and prepare the data: The goal of exploring and preparing the data is to try and gain insights from the data prior to modeling. Identifying relevant features for the model, using pipeline, normalization, and cleaning methods to ensure data accuracy and completeness. 

3. Model selection: Select the appropriate machine-learning algorithm, such as linear regression, decision trees, random forest, etc, to develop the model.

4. Model training: Using a portion of the data to train the model and tweaking the parameters to optimize its performance.

5. Model evaluation: Evaluate the performance of the model using various metrics, such as mean squared error, R-squared, or F1-score, to assess its accuracy and generalizability.

6. Hyperparameter tuning: Adjusting the model's hyperparameters, such as learning rate or regularization strength, to further optimize its performance.

7. Model deployment: Deploying the trained model in a production environment, such as making predictions on new dataset.

## 4. Deliverables (2 marks)
Provide a list of what the project must deliver to achieve its objective. At the end of this section, add a Gantt chart with all major deliverables set against their expected timelines.

1. A comprehensive dataset of relevant features, including house prices, location, size, number of rooms, and amenities.

2. A cleaned, normalized, and pre-processed dataset for model training.

3. A well-trained machine-learning model can accurately predict house prices based on the selected features.

4. Performance evaluation metrics, such as mean squared error, R-squared, or F1-score, to assess the model's accuracy and generalizability.

5. A final report summarizing the project findings, including insights gained from data exploration and analysis, the selected machine-learning algorithm, the optimized model's hyperparameters, and the model's performance evaluation results.
#### ADD YOUR GANTT CHART HERE

<img width="1107" alt="Screen Shot 2023-04-17 at 11 58 30 PM" src="https://user-images.githubusercontent.com/123212794/232667721-90440cbe-fef9-4b54-b744-986e818fb364.png">

## 5. Risks, Assumptions, and Constraints (2 marks)

### 5.1 Risks
- Some homes may undergo sudden price changes
- Financial advice can change depending on how up to date the dataset is
- Some parties may consider us liable for giving financial advice
- Overall scope of the predictive model might be too large with too many requirements

### 5.2 Assumptions
- The necessary data exists and it will not be updated everyday
- The development team possesses all required skills 
- The equipment used is in acceptable condition and is powerful enough to run these models

### 5.3 Constraints
- The development team will consist of only 3 people
- Only 1 consolidated data source will be used to ensure consistency between model version results 

| | High Impact | Low Impact |
| ----------- | ----------- | ----------- |
| High Likelihood | Some parties may consider us liable for giving financial advice | Overall scope of the predictive model might be too large with too many requirements |
| Low Likelihood | Some homes may undergo sudden price changes | Financial advice can change depending on how up to date the dataset is |

## 6. Organization/Stakeholders (1 mark)
| Project Role | Responsibilities | Assigned to |
| ----------- | ----------- | ----------- |
| Project Manager | Oversee and manage the project| Annhanjef Czs|
| Project Sponsor | Cover website costs | Seneca Company|
| Development Team | Develops and trains the machine learning model using appropriate algorithms and techniques, evaluates and fine-tunes the model, deploys the model for use by Seneva Company | Annie Cao, Hang Zhou, Jeff Sit|
| Users | Utilize the model for purchasing decisions  | Seneca Company clients |

### 6.1 Stakeholder Matrix diagram
| Stakeholder | Interest | Influence | Strategy |
| ----------- | ----------- | ----------- | ----------- |
| Seneca Company| High | High |Manage closely; Engage stakeholders; Provide necessary resources|
| Project Manager | High | High | Communicate effectively; Manage project risks and issues; Keep project on track |
| Development Team| High | High | Provide regular updates; Deliver high-quality model; Address concerns proactively|
| Users| High | Low | Gather user feedback to enhance model accuracy and relevance |

## 7. Preliminary Budget (2 marks)
### 7.1 Personnel cost per sprint
| Name | Role | Daily rate | Allocation | Days per week | Sprint burn rate |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Annhanjef Czs | Project Manager | $320 | 80% | 4 | $1024 |
| Annie Cao | Developer | $260 | 100% | 5 | $1300 |
| Hang Zhou | Developer | $260 | 100% | 5 | $1300 | 
| Jeff Sit | Developer | $260 | 90% | 5 | $1170 | 

### 7.2 Total personnel cost
| Company name | # of sprints | Total cost per sprint | Total personnel cost |
| ----------- | ----------- | ----------- | ----------- |
| Seneca Company | 12 | $4794 | $57528 |

### 7.3 Fixed costs
| Item name | Quantity | Cost per item | Total cost |
| ----------- | ----------- | ----------- | ----------- |
| Office space rent | 1 | $2800 per month | $16800 |
| Web hosting costs | 1 | $18 per month | $108 |
| Ecommerce hosting platform | 1 | $80 per month | $480 |

### 7.4 Contingency
1. Total personnel cost = $57258
2. Total Fixed costs = $17388
3. Sum of the above = $57258 + $17388 = $74646
4. Contingency of 15% of sum = $74646 * 0.15 = $11197

### 7.5 Total cost
1. Sum of personnel costs and fixed costs = $74646
2. Contingency amount of sum = $11197
3. Account for contingency in total cost = $74646 + $11197 = $85843
