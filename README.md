# Lead-Scoring-Model

### Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

<img src = 'https://media.istockphoto.com/id/1088363648/photo/marketing-leads-and-sales-concept.jpg?s=1024x1024&w=is&k=20&c=eLOzJmJcjFiCLA1cqCXWdv3pQc4p3eeomwq6wPli-gk='>

There are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating, etc. ) in order to get a higher lead conversion.

X Education wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score h have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

### Solution:
For this case study we're going to use several classification model to predict whether the lead is going to quantify as a hot lead. The steps involved for this case study are mentioned below:

1. Import data
2. Clean and prepare the acquired data for further analysis 
3. Exploratory data analysis for figuring out most helpful attributes for conversion
4. Scaling features
5. Prepare the data for model building
6. Build a logistic regression model 
7. Test the model on train set 
8. Evaluate model by different measures and metrics 
9. Test the model on test set
10. Measure the accuracy of the model and other metrics of evolution

### Notebooks:
1) <a href = "https://github.com/Pallavi-nishankar/Lead-Scoring-Model/blob/main/Lead%20Scoring%20case%20study%20.ipynb"> Exploratory Data Analysis + Feature Engineering + Outlier Analysis Notebook
2) <a href = "https://github.com/Pallavi-nishankar/Lead-Scoring-Model/blob/main/Lead%20Scoring%20case%20study%20.ipynb"> Lead Scoring Model Diagnosis Notebook
3) <a href = "https://github.com/Pallavi-nishankar/Lead-Scoring-Model/blob/main/Lead%20Scoring%20case%20study%20.ipynb"> Final Lead Scoring Model Notebook
