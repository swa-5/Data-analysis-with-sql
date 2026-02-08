# Common Pre Test 
## SECTION A : DATA ANALYSIS & SCIENCE

 **1. Imagine you're given a CSV file with 10,000 customer records, but 15% of the "Age"
column values are missing. How would you handle this missing data before analysing
customer demographics?**

*Ans* :- If 15% of the "age" column values are missing, then I will fill those column values either by "NULL" or by "Average value" of the "age" column or I will drop the rows with missing values before analysing.
#
**2. You need to identify which products are frequently purchased together. What kind of
analysis would you perform, and what specific techniques or tools would you use?**

*Ans* :- I will perform "Exploratory analysis", find correlation between the purchased products and use BI tools (like MS Power BI) to visualise and identify which products are frequently purchased together.
#
**3. Explain the difference between a bar chart and a histogram. When would you use
each, and what does this tell you about the nature of the data they represent?**

*Ans* :- A bar chart and a histogram is very similar to each other both uses rectangular bars but a histogram is different from bar chart it uses adjacent rectangular bar on grouped frequency distribution with continuous classes, while bar charts have a gap between the bars and it is used for qualitative data. Bar charts are used for comparing data and histogram is used for know the distribution of the data. Bar charts show which category have highest or lowest value like which product is in high demand whereas histograms show values in the range like how many students are in the marks range 80-90.
#
**4. Write a simple SQL query to find all customers from "New York" who spent more than
$500 in January, ordered by their total spending (highest to lowest).**

*Ans* :- The sql query for the given question will be:                                       
        SELECT * FROM table        
        WHERE (city = 'New York' AND spending > 500) AND month = 'January'               
        ORDER BY spending DESC;
#
**5. You analyse website traffic data and find that page load times increase dramatically
when more than 100 users are active. What are at least three possible reasons for this
correlation, and how would you investigate further?**

*Ans* :- Inefficient servers, bad sql queries are the possible reasons for this correlation.
#
## SECTION G : TECHNICAL MINDSET & PROBLEM SOLVING

**1. Describe your process for learning a completely new technical skill or technology.
How do you approach it, what resources do you use, and how do you know when you've
understood it well enough?**

*Ans* :- To learn a completely new technical skill and technology, first I gather all the information spread on internet and try to understand what about the new technology actually is. After understanding all the buzzwords and have some knowledge about that technology, I go for specific books and courses on online platforms and youtube. I gain all the fundametal knowledge about the technology through video lectures and self study then, I try to solve small problems using that technology and find out where I am doing wrong. Afterwards, I go for real world projects that makes me able to understand how to use that technology to solve real world problems. After compliting some real world projects successfully I feel that I have understood that technology well enough.
#
**2. You're stuck on a technical problem for several hours. What do you do? Outline at
least three specific strategies you would use to make progress.**

*Ans* :- When I am stuck on a technical problem for several hours then, first I take a break for 15-20 mins to refresh my mind and then back to the problem. Sometimes a small semicolon sign and quote sign making trouble, after break it's easy to solve these kind of problems. Second, I go line by line to check the syntax and the third, restructure the solution to make progress.
#
**3. How would you explain a technical concept from your domain (like a database, API, or
machine learning model) to a non-technical family member?**

*Ans* :- To explain a technical concept to a non-technical family member, I use real world analogy. I relate a technical concept to a real world entities and try to explain as simply as I can.
#
**4. What does "debugging" mean beyond just fixing code errors? Describe the mindset
and systematic approach you would take to debug any complex system problem.**

*Ans* :- Debugging means not only fixing the code errors , it is more than that it is used to make program memory efficient and cost and time effective. In this process, we found  out the differences between the actual and expected result by observing the code and check for the errors not occur now but may occur in future. It is used to avoid future errors. To debug any complex system problem. First, checks modules one by one and find out any errors in modules then create test cases on expected results and run the code through all test cases to find out there's no any differences in actual and expected results.
#
**5. Why is documentation important in technical work, even if you're the only one who
will ever see the code or project?**

*Ans* :- Documentation is very important in technical work. It does not only helps other to understand our code but it helps us ourselves also to remind why we use the specific data structure and code at the time of implementation of the program. Because when we come back to our code after a long time, it helps us easily understand program implementation.