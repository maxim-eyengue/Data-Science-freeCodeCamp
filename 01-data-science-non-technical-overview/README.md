# [Learn Data Science Tutorial - Full Course for Beginners](https://www.youtube.com/watch?v=ua-CiDNNj30&list=PLWKjhJtqVAblQe2CCWqV4Zy3LY01Z8aF1&index=1&t=1416s)

From Barton Poulson

# Introduction to data science

People usually see data as a too techy discipline with maths and labs but it is much more a creative discipline: you use tools from coding, stats & maths to work creatively with data in order to finfd a way to solve problems, and get insights from data. For that, you try to listen to almost all your data as **everything signifies**.

This course gives a map of data science and how we can use it.

## Definition of data science
It is coding, maths & statistics in applied settings or the analysis of diverse data or inclusive analysis. 

### The data science Venn diagram
According to Drew Conway, data science is a combination of coding (computer programming, hacking), stats & maths (quantitative habilities) and domain expertise (intimate familiarity with a particular fiels).
![The ingredients of data science](images/ds_ingredients.png)

- Coding: 
It helps gather and prepare data coming from different sources. Note that it can rquire real creativity. There is statistical coding (R & Python), database manipulation (SQL), the command line interface (bash), and also search (regex: regular expression).

- Math:
Probability, algebra, regression, etc. helps to choose the procedures to manage data and diagnose problems encoutered when manipulating them.

- Domain Expertise:
goals, methods used, and constratints of the field in order to implement them well.

Note that the combination of these three can lead to other inner-circles: ML, Traditional research and the danger zone.
![Some other fields](images/ds_inner_circles.png)

- ML: coding and math without any domain expertise. It doesn't involve applications.
- Traditional research: math or stats and domain knowledge witouth programming. The data here is already structured and ready for analysis. We just need to choose method and interpret results.
- Danger zone: coding & domain knowledge without maths can be used for drawing maos and counting words.


### The data science pathway
The steps are the following :
- planning: define the project goals to know how to us the resources and when the goal has been reaches, organize those resources and coordinate people, schedule the project.

- data prep: get the data and clean it, explore the data to find out more about it, refine the data (adding variables, including or excluding cases)

- statistical modeling: create and validate the model, evaluate it, and refine (adding or throwing variable)

- follow-up: present the model to clients, deploy the model to a websie for example, revisit the model as data migh change with time, and archive the assets and document everything so that the analysis can be reproduced.

### Roles in data science
Data science is a colaborative thing where people work together to achieve a goal.

- Engineers: such as developers or database admin, who focus on back end hardware, and the software running them. They provide the foundation for the rest of the work.

- Big data specialists: focus on computer science and maths, creating data products using machine learning.

- Researchers: focus on domain specific research such as physics, genetics, precision medicine, healthcare. They are very good statistician.

- Analysts: focus on daily tasks such as web analytics or pulling data from sql. This is good for business in general.

- Business people: frame relevant questions that can be answered with data. They manage projects and must be able to "speak data".

- Entrepreneur: creating data startups, they need data & business skills using creative throughout.

- **Full-stack "unicorn"**: can do everything at an expert level.


### Teams in data science
The unicorn is a mythical creature with magical abilities. In data science it is a mythical data scientist with universal abilities. No unicorns (*not yet*), just people. Hence, there is a need to build teams to deliver data science projects. To build a good team, we take people wit different skills so that togeher they can form a kind of unicorn: a **unicorn by team**.

## Contrasts

### Big data
Big data and Data science both have a venn diagram. They are similar but not the same. Big data combine **volume** (big quantity of the data), **velocity** (the high speed with which this data is generated) and **variety** (data in different formats).

- Big data without data science: big data without all v's. Think of machine learning without domain expertise, or world counts. Note that we need coding and quantitative skills.

- Data science without big data: Data with just one v. For example, genetics data may not count as big  data as the data can be taken once even though in huge quantity. Streaming sensor data allows to get data very quickly and we can just visualize it without storing that. Facial recognition may not count as big data too.

Big data can be combined with data science to get **big data science**. T handle this, ther is a need to get the full skillset of data science.


### Coding
It is just giving task intructions to computers. It is like a recipe provided to a machine so that its ouputs a result in function of an input. To accomplish simple tasks like counting words, adding the data part is enough but to make valid inferences and generalizations, there is a need of statistics and by extension of data science. Note hat top data science tools include thngs that are not programming langauges such as Excel.

![Top data science tools](images/ds_tools.png)


### Statistics
When it comes to Data Science, we cannot think of Statistics as a NOMA (Non Overlappin Magisteria). Indeed, Statistics is a part of data science. However, most data scientists are not trained as statisticians. In practice, ML & Big data are not shared generally with Statistics. They have separate domains. Finally data scientsts generally very often work in commercial settings to develop products that make money. Both fields analyze data but people in each tend to have different backgrounds and function with different goals & contexts.


### Business Intelligence
BI is data in real life. It is very very applied stuff. Its purpose is to get data on interanl operations, market and competitors and make justifiable decisions. Data science is involveld with this but BI does not include coding and its statistics are vecimple (count, percentages, ratios). The focus here is on doain expertise and on really useful direct utility. One of the main associations is **dashboards** (collections of charts and tables that go together to give a very quick overview of what is going on in the business).
Data science can be useful to set up the framework for a BI system or for dashboards. It can help past easy questions and easy data to get the questions that are most useful even if they require data hard to wrangle. DS can learn design from good BI. 


## Ethical Issues