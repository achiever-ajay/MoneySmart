# MoneySmart
MoneySmart
# MoneySmart Take Home Coding Assignment - Senior Data Engineer

# Q1 : Write an SQL statement to find the total number of user sessions each page has each day.
# (A user session is defined as continuous activity on a site where each activity is within 10 mins of each other.)

# Answer: 
SELECT SamplePageviews.[Page_ID], SamplePageviews.[Visit_Date], Count(SamplePageviews.ID) AS CountOfID
FROM SamplePageviews
GROUP BY SamplePageviews.[Page_ID], SamplePageviews.[Visit_Date];
-----------------------------------------------------------------------------------------------------------------------

# Q2 : Sales Queries
1. Which month has the highest sales? Is there any seasonality effect?
# Answer:
Nov 2017 is top performing Month
November , September , and March are peak periods over the years.

2. Which product is the recent best seller?
Hint: There is no `right` answer for this question, please feel free to make your own interpretation and
give suggestion
# Answer:
QlikCloud : Best Seller "Top Product" URL: https://ap.qlikcloud.com/view/5c65edef76850f90b62633a3

3. Is there any group of products which are often bought together?
Hint: You can define you own metric, however, please explain the rationale behind
# Answer:
QlikCloud : Bucket Analysis "Scatter Plot" URL: https://ap.qlikcloud.com/view/5c65edef76850f90b62633a3

4. Is there any other insight you can get to help to improve sales number?
Hint: It is okay to not having any significant insight, but you have to state the hypothesis and verify
# Answer:
QlikCloud : Insights "Scatter Plot" URL: https://ap.qlikcloud.com/view/5c65edef76850f90b62633a3

5. Based on the data we have, what kind of BI dashboards you would build in order to help the sales
team monitoring the performance?
# Answer:
QlikCloud URL: Dashboard https://ap.qlikcloud.com/view/5c65edef76850f90b62633a3
##
