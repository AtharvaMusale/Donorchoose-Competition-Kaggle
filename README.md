# Donorchoose-Competition-Kaggle

# REASON TO CHOOSE THIS PROJECT
Donors Choose is the organization which is founded by the school teacher in Bronx. DonorsChoose.org empowers public school teachers from across the country to request much-needed materials and experiences for their students. At any given time, there are thousands of classroom requests that can be brought to life with a gift of any amount. DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website. Next year, DonorsChoose.org expects to receive close to 500,000 project proposals.

As a result, there are three main problems they need to solve:

How to scale current manual processes and resources to screen 500, 000 projects so that they can be posted as quickly and as efficiently as possible
How to increase the consistency of project vetting across different volunteers to improve the experience for teachers
How to focus volunteer time on the applications that need the most assistance
# GOAL FOR THE PROJECT
The goal of the project is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.
With an algorithm to pre-screen applications, DonorsChoose.org can auto-approve some applications quickly so that volunteers can spend their time on more nuanced and detailed project ​vetting processes, including doing more to help teachers develop projects that qualify for specific funding opportunities.
# DATA
The data I am using is from the kaggle website. The link to the dataset is: https://www.kaggle.com/c/donorschoose-application-screening/data
# EVALUATION METRIC
Since this problem is a classification based problem, we need to find the best metirc for this problem.
There are few metrics which we can think of like Accuracy Score (Prone to errors if data is imbalanced), Multiclass Log Loss (Good Evaluation Metric) and AUROC. The competition has mentione dthat they are using AUROC as there evaluation metric. So we will try to use the AUROC as a business metric. AUROC is the area under ROC curve. ROc is the plot between TPR vs FPR.


There are few metrics which we can think of like Accuracy Score (Prone to errors if data is imbalanced), Multiclass Log Loss (Good Evaluation Metric) and AUROC. The competition has mentione dthat they are using AUROC as there evaluation metric. So we will try to use the AUROC as a business metric. AUROC is the area under ROC curve. ROc is the plot between TPR vs FPR.

# MODLES USED:
* Naive Bayes
* Logistic Regression
* Decision Tree
* GBDT
* LSTM
