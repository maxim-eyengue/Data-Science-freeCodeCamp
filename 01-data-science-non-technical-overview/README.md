# [Learn Data Science Tutorial - Full Course for Beginners](https://www.youtube.com/watch?v=ua-CiDNNj30&list=PLWKjhJtqVAblQe2CCWqV4Zy3LY01Z8aF1&index=1&t=1416s)

From Barton Poulson

# Introduction to data science

People usually see data as a too techy discipline with maths and labs but it is much more a creative discipline: you use tools from coding, stats & maths to work creatively with data in order to find a way to solve problems, and get insights from data. For that, you try to listen to almost all your data as **everything signifies**.

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
Please, **Do no harm** with your projects.

### Privacy
You shouldn't share confidential information from people (name, addresses, health, social security numbers, etc.) except if they give you permission for that. A lot of data used for data science was not created for sharing. Think of web scraping of pdfs... Make sure you have the right to,if you want to share data.

### Anonymity
It is not hard to identify people in data. Before, **HIPAA**, the Health Insurance Portability ad Accountabiity Act, it was very easy to identify people from medical records.  Propietary data may have identifiers. We should still maintain privacy and confidentiality of the data.

### Copyright
Scraping data (from webpages, pdfs, images, audio, etc.) is common and useful but it is not always okay to use data just because it is on the Internet.

### Data security
We should be concened about hackers trying to steal the data especially if it is not anonymous. The data should be safe.

### Potential Bias
If the rules & data used are biased (gender, race, ...), algorithms might replicate those biases.

### Overconfidence
Analyses are limited simplifications and there is a need of humans to help interpret them. Humility is in honor when doing data science work.


## Methods
Tech is simply the means to do data science, the goal being insights.
- Sourcing: How to get the data.
- Coding: Computer programming to obtain, manipulate and analyse the data.
- Maths: math behind the DS methods.
- Stats: statistical methods to summarize and anlayze the data.
- ML: Methods for finding clusters, predicting categories and scores.
DS >>> Tech


### Sourcing
You have some options to get raw data:
- Existing data: in-house data from a company, open source data from governments or organizations, third-party data bought from a specific vendor.
- Data APIs: an Application Programming Interface allows applications to communicate directly with each other. It helps to import web data directly from the program we are using to treat data.
- Scrape Web data: For web data without APIs such as HTML, PDFs, we can use specialized apps or code with programming languages like R or Python.
- Make data: it helps to get exactly what we need maybe by interviews, surveys, or experiments.
No matter the method, we need to remember **GIGO**: *Garbage in, garbage out*. Bad data won't provide real insights. As a consequence, we need to pay attention to metrics Business metrics, KPIs (key performance indicators), SMART goals and classification accuracy. 

### Coding
It is any technology allowing to manipulate data in the way you need to perform the procedure you need to get the insights you want out of the data. There are threes categories:
- apps: specialized for working with data. There are Spreadsheets fundamental data tool, Tableau for data visualization, SPSS statistical package, JASP free open source vesion of SPSS.
- data: special formats for web data such ashtml, xml, json, etc.
- code: programming languages such as R, Python for general purpose, SQL for databases, C, C++ & Java used more in the back-end of data science, bash and regex.

Note that tools are just means, use them wisely. A few tools are enough, you should just focus on your goal, choosing the tools to match it.

### Maths
It is important because:
- you need to know which procedures to use and why
- you need to know what to do when things don't work right
- some math is easier by hand than computer
Math is to data science what chemistry is to cooking, kinesiology to dancing, or rammar to writing. You can be a wonderful cook without  know chemistry ut knowing some will definitely help.
The Maths you need:
- Elementary Algebra
- Linear (matrix) Algebra
- Systems of linear equations
- Calculus
- Big O: how fast it works
- Probability Theory
- Baye's theorem

### Satistics
It is an attempt to find patterns in an overwhelming mass, order in chaos.
- We can explore data: exploratory graphics (it is easy to see things), exploratory stats (numerical exploration of the data), descriptive stats (stats in college)
- Inference: take information from sample and infere something about a population. One commmon version is hypothesis testing, and another one is estimation (confidence intervals)...
- we have to be concerned by details and arranging things by ourselves: feature selection, problems, validation to make sure the model is correct, choice of estimators (coefficients of the model), and how well the model fits the data.
Beware the trolls: you don't have to listen to people who think only their way is right. Remember George Box said: **all models are wrong, but some are useful**. The question is to know f you have done something that is useful.
Wave your DIY (Do It Yourself) flag.


### Machine Learning
Intersection between coding & stats. It can be used to categorize and predict information from data:
- work in a **data space** to reduce te dimensionality, and then use clustering or K-Means methods, and find anomalies or unusual cases in the data space.
- work with **categories** with algorithms such as logistic regression, kNN, Naive Bayes, Decision Trees, SVM or artifical neural nets, to find patterns in the data to get similar cases next to each other.
- **predictions**: linear regression, poisson regression for modeling count or frequency data, ensemble models putting together predictions from many simpler models.


## Communicating

### Interpretability
You want to tell a data driven story. When doing the analysis, we are trying to solve for **value**: $Analysis \times Max(Story) = Max(Value)$. Analysis is goal-driven. The explanation or story given about the project should match those goals. Answer clients questions clearly and unambiguously.
Remember the client isn't you, and think of:
- Egocentism: They don't see, know or undertstand thing sthe same way you do. 
- False consensus: ideas that everybody knows something.
- Anchoring: initial impressions matter a lot. Watch out.
- Clarity at each step.
Think of the **answers**: staet the question, answer it, qualify as needed and go in order but don't spend too much time on discssing the process technically. 
The process is to remember that *analysis* means simplifying. According to Einstein: **everythig should be made as simple as possible but not simpler**. hink of the minimum viable analysis:
- more charts, less text
- simplify charts
- avoid tables (they are hard to read)
- less text (again).
In 1973, graduate school admissions revealed that the male admission rate was hgher than the female one: $44\%$ against $35\%$. It seems to a lawsuit. However after breaking the application down by programs, it was found that there are some programs were women were accepted in a higher rate and some they were not. In Statistics, this is known as **Simpson's Paradox**. The paradox is that bias might be negligible at department level but still there might be some bias there in favor of women. The roblem is women applied to more slective programs. There are many other questions that can still be answered and things we can look for as admission criteria, promoional strategies, prior education and funding levels. 
In sum, stories give value to data analysis and should be telled in a clear way, minimally sufficient.


### Actionable insights
Those are information that can be used productively to accomplish something. William James idea: **My thinking is first and last and always for the sake of my doing** applies to analysis. When doing an analysis, point the way (analysis guide action). You should be able to tell the clients what are the next steps (what they need to do now), justifyng those recommendations with data. You should be specific and make sure they are able to do them sep by step. 
The problem here is the difference between **correlation** and **causation**. Data ives correlation (this is associated with that), but the client wants causation (this causes that). There are few ways to get that:
- Experimental studies: randomized controlled trials
- Quasi-experiments: methods that use non-randomized data for causal inference
- Theory & experience: research vbased theory and domain-specific experience
There are also social factors affecting the data.
![Data & Social](./images/ds_social.png)
We should make sure our recommendation follow: the client's mission (what he does), identity (who he is), its business context (competitive environment) ut also the social context (outsde and inside the company).

### Presentation graphics
Trying to paint a picture for the benefits of the client:
- Exploratory graphics: speed and responsiveness, for our insights.
- Presentation graphics: clarity & narrative flow. Avoid too much colors, 3D, interaction and animation as the client should not be distracted.

### Reproducible research
Data science projects tend to be incremental, cumulative and adaptive. So, **show your work**. You may need to revise your research later, or borrow something from previous studies, hand off to someone else, and also about accountability to show you did things in a responsive way. 
There is a platform called the [open data science conference](https://odsc.com/) devoted to open data science using open data and making methods transparent. The [open science framework](https://osf.io/) is a way of sharing data and research with anotations of how to get to the results. The [asssociation for psychological science](https://www.psychologicalscience.org/) strongly encourages people to share their data as much as possible and their methods to conduct studies.
It is important to archive your data: both the totally raw and the processed, all code to process and analyze data, making sure to comment liberally and explain yourself (why you did the way you did, include choices and consequences, backtracking).
This helps to future roof you work. Some useful principles:
- Store data in non-proprietary formats, like csv
- Place files in accessible location like GitHub.
- Code: using dependency management: packrat for R, virtualenv for Python.
Putting the narrative in a notebook can help to explain yourself. R Markdown can be used for R code (docs can be uploaded as RPubs to be accessible online) and Jupyter Notebook for Python.


## Conclusion

Remember it is important to give people next steps. You can start doing some coding, visulalization or learn some stats & maths or even ML. But try to keep wha you do in context. You can also get invlved in a=one community of data science like O'Reilly Strata, Predictive Analysis World, Tapestry Conference, Extract by import.io. To start working a great choice is [kaggle](https://www.kaggle.com/). Once done, you might want to do some service: [DataKind](https://www.datakind.org/) is the premiere organization for data science as humanitarian service. Only remember that: data science is democratic. DATA SCIENCE NEED YOU!

---

# Data Sourcing
No data no data science. This course is about different methods to obtain data for analyses.

## Measurement

### Metrics
Data science is action oriented. The goal should be explicit and clear for the client and can help the analysts save time. It helps define success:
- commerce: sales, new customers
- edu: scores on test, graduation rate
- government: housing, jobs
- research: ability to serve the people we are trying to understand.
There are different metrics or ways of mesuring:
- Business metrics: sales revenue, leads generated or new customers, customer value, churn rate (loosing and gaining customers)
- KPIs: a key performance indicator should be non-financial (measure the overall productivity), timely, ceo focus (senior management ddecide on them), simple, team-based, with significant impact (affecting more than one important outcome) and limited dark side (fewer possibility for reinforcing wrong behaviours).
- SMART goals: Specific Measurable, Assignable, Realistic and Time-bounded.
- Multiple goals: optimizing goals.
Many metrics can be used to know how well the goals are reached. When there are many there is a need to optimize them. 

### Accuracy
We can get many different ways of measuring the accuracy from a classification table.

![Classification Table](images/classification_table.png)

Some are:
- sensitivity: or recall or true positive rate. If there is a fire, does the alarm ring? You want to always have an alarm when there is a fire.
$sensitivity = tp / (tp + fn)$
- specificity: if there isn't a fire, does the alarm stay quiet? You want the alarm to stay quiet when there is no fire.
$ specificity = tn / (tn + fp)$
- positive predictive value: or ppv or precision. If the alarm rings, is there a fire?
$ppv = tp / (tp + fp)$
- negative predictive value: if the aaram doesn't ring, is there no fire?
$npv = tn / (tn + fn)$
The idea is to maximise an acccuracy as much as we can. We want to maximize true positives and true negatives and avoid te false ones. 

### Social context of measurements
People are people and that can affect measurements:
- When making recommendations, it is important to respect the business model of the client organisation (it's tied to their identity). 
- Some laws and policies or common practices may limit the way goal can be met.
- There is compettion both between organizations as within.
- People generally exploit and game the system.
You should consider that to make the most out of your analysis.


## Getting data

### Use existing data
There are any different types:
- **In-house data**: proprietary data (from the organisation or client company) can be fast and easy with hopefully appropriate format and good documentation, with good quality. There might be some restrictions.
- **Open data**: public (government, corporate or scientific) data that is prepared and freely available. Some example are : [US data](https://data.gov/), [Utah data](https://www.utah.gov/index.html), [EU data](https://data.europa.eu/en), [UN data](https://data.unicef.org/), [WHO data](https://www.who.int/data), [Pew Research Center data](https://www.pewresearch.org/datasets/), the [New York Times APIs](https://developer.nytimes.com/), [Google available data](https://datacommons.org/data/agriculture), [AWS Pubic datasets](https://aws.amazon.com/opendata).
Note that those datasets can be very valuable, well-formated and documented, and also various. However, sometimes they require sharing analyses which is a concern when doing proprietary research. There might be biased samples because of Internet needs, or issue with privacy and confidentiality. The data meaning might also be unclear.
- **Third-party data**: purchased data (DaaS: Data as a service, or Data brokers) can give enormous data on many different topics, even processing data for us. Here are some data brokers: [Acxiom](https://www.acxiom.com/) primarily for marketing data, [Nielsen](https://www.nielsen.com/) primarily for media consumption and [datasift](https://www.datasift.com.tr/). Using data brokers can save time and effort, giving individual level data, and specific information. However, it can be expensive, still require a double-check, and people don't like using this option.

Always pay attention to the quality, the meaning and the usability of the data.


### Use APIs
Application Programming Interfaces allow programs to talk to each other. It allows your program to get web data. The most common version is called **REST API** standing for Representational State Transfered . It allows to access data on web page via *HTTP* (HyperTest Transfer Protocol). The data is downloaded in *JSON* (Javascript Object Notation) format, and can be sent directly to other programs using any programming language (as they are language agnostic).
There are **social APIs** for: Facebook, Tweitter, Google Chat, FourSquare, Souncloud; **visual APIs**: Google Maps, YouTube, AccuWeather, Pinterst, Flickr.
We can program APIs in **R**, **Python**, **Bash**, etc.

### Scraping data
Scraping data is pulling information from web pages. We use this technique when there is no immediate way to get the data we can see. From that we can scrape html text, or tables, pdfs, and media. Always pay attention to copyright and privacy. There many ways to do web scraping:
- use apps: import.io, ScraperWiki, Tabula, Google Sheets, Excel.
- code your scraper with: R, Python, Bash, Java or PHP.
You are gonnae be looking for information in web pages. If looking for **HTML Text**, you will pull structured text from web pages, using HTML tags like <*body*> <*h1*> or <*p*>. For **HTML tables**, you will use HTML table tags like like <*table*> <*tr*> or <*td*> but you need the table number that you mind find after trials and errors. You  can also scrape data from **pdfs** (native: text pdf, or scanned: image pdf) by looking for text elements, dealing with raster/vector images and also with tabular data using special programs like Tabula or ScraperWiki. Finally we can scrape **media** like images, video or audio. To read the data, we might need a program looking pixel by pixel in each image.


### Making data
Can't find the data you need? DIY
Depending on your role to get the data (passive or active), the type of data you want (quantitative or qualitative) and how you want to et it (online or in person), there are some options:
- **interviews**: a conversation used for the most basic problem. When you are working with a new topic, a new audience, or you need to find ways to improve. You don't want to constratint responses. Interviews can be structured with predetermined questions or unstructured. They require time and training, and answers eed to be analysed.
- **surveys**:  if you want to know something, just ask. Here you need to know enough the topic and the audience to anticipate the answers. You can have a *closed ended* surveys with forced choices, *open ended* ones, *in person* or *online*. Common applications for online surveys are **SurveyMonkey**, **Qualtrics**, **Google Forms** and **Typeform**. Note that when surveys are easy to set up, questions can be ambiguous, and response scales confusing.
- **card sorting**: important in web research. To do so, you write topics on crads, physcally or digially and ask people to sort those crads so that you can compute dissimilarity data (distance betwee topics). There are *generative* card sorting tasks where each respondent create their own sets, used to design wesites, and *evaluative* where ther is a fixed number of categories, used to check if the navigation is intuitive. You end up with a **dendogram**: hierarchical visulaization.
![Dendrogram](images/dendrogram.png)
For digital card sorting, you can use Optimal Worksop, UserZoom or UXSuite.
- **Experiments**: *laboratory* where you design the situation, *A/B testing* an automated online testing of two or more variations. Lab experiments helps to determine better **cause and effects**. Here reasearchers can play an active role with manipulation. Experiments are focused research, hypothesis driven with random assignment to minimize of confounds and artifacts.
A/B testing : you create a multiple versions, randomly assign version to visitors, compare response rates (time on page, mouse tracking, click-throughs, shopping cart value, abandonment), and implement the best variation.  A/B testing can be performed continuously. There are some softwares to do it: **Optimizely**, **VWO**, etc.

## Conclusion
See what you already have, exploring some open data sources. Cnsidere making new data if they don't give you what you need.

---

# Coding in data science

We are gonna take a look at tools in Data Science and their place.
Note that data science is much more than the tools involved. We will need at least a few tools.

For getting started, we need spreadsheets, Tableau for data visualisation, the format used in web data (not a tool but very informative). Essentials tools include R for data, the general purpose programming language Python, and the database language SQL. Beyond that, there are the general purpose programming languages C, C++, Java used for high level production code, bash, and regex.
Don't forget the Pareto principle. It states that for many outcomes, roughly 80% of consequences come from 20% of causes.
![Pareto Principle with data tools](images/pareto_law.png)
You don't have to know everything but you should focus on the tools that are going to be most productive for you.

## Applications
We will talk about programs crceated to manipulate data.

### Spreadsheets
They are easy to use and everywhere: a lot of companies use data in spreadsheets format. `.csv` is  sort of universal format for data transfer. Note that Excel is above Hadoop and Spark in the ranking of major big data fancy tools.
Spreadsheets are goof for data browsing, sorting and rearranging data, finding and replacing, formatting (conditional formatting), for transposing data (switching rows and columns), for tracking changes (even though you might be using GitHub for that), for making pivot tables (to explore data intuitively), for arranging the output for consumptions.
With spreadshhets, we need to make sure the data is **tidy** so it works well when transfering it. For that:
column = variable, row = case, one sheet per file, and one level of measurement (indicidual, organisation, state) per file.

### Tableau
It is a visualization program. When we have data the most important thing to do is to look into that data. Tableau Public is the free version that publishes dashboards online.

### SPSS
Statistical Package for the Social Sciences is pretty big desktop program used in academic or medical research, business consulting and management. It is powerful but quite expensive.
SPSS looks like Excel but with much more options, and has a lot of sample datasets. It generates an output file that can be downloaded. Syntax files offer the possibility to copy code and save it as a text file, so to replicate analyses.

### [JASP](https://jasp-stats.org/)
It is the free version of SPSS. It is also open source, intuitive, making analyses replicable and it includes Bayesian approaches. The layout is similar to SPSS.
You can add the skewness or the kurtosis (measure of the presence of extrem values) in your data summary table. Note that you can also share the information online through [OSF (Open Science Framework)](https://osf.io/). 

### Other software
There is so much more:
- SAS: very powerful analytical program. The SAS University Edition is free for students. JMP is a visualization program from SASA.
- STATA, Minilab, Matlab, Mathematica (language)
- WolframAlpha: analyses, regressio models, visualizations
- For data mining: RapidMiner, KNIME, Orange.
- For Machine Learning: BigML.
- SOFA (Stats Open For All) Statistics, Past 3, StatCrunch for basic stats and learning.
- XLSTAT and addin to get a lot of stats functions within Excel.

Note you don't even have to try all of them. You should just use what works for you. Think of functionality, ease of use, the existence of a community (to solve problems you'll face), the cost, all this to reach you goals.


## Web data

### HTML
**HTML** (Hyper Text Markup Language) is used to build the content of web pages from text and tags that define the document's structure. Some tags are: <*body*>...</*body*> for the text body, <*p*>...</*p*> for paragraphs, <*h1*>...</*h1*> for header 1, <*td*>...</*td*> for table dataor the cell in a table. **CSS** (Cascading Style Sheets) helps to define the appearance of the document.

### XML
**XML** (eXtensible Markup Language) is semi-structured data, tags defining data so the computer knows what it is. Note that unlke HTML, the tags are free to be defined anyway we want. We will often see xml files in web data, Microsoft Office (.docx, .xlsx --> x for eXtensible), iTunes library information, data files. Tags also use opening and closing brackets: <*genre*>...</*genre*>. A right click on a web page followed by a left click on view page source helps to visualize the xml or html code of a web page. We can use APIs to access xml data and also convert xml data easily to different formats (xml to csv and vice versa, html to xml).

### JSON
Like XML, **JSON** (JavaScript Object Notation) is semi-structured data. When XML gives meaning to text and allows for comments and metadata in tags, JSON is specifically designed for data interchange, with a structure that corresponds with data structures: strings, dictionaries, etc.

It is really easy to convert between the formats.


## Languages

### R programming
![Data Science Languages Ranking](images/ds_languages.png)
R is the language of data. It is free & open source, specially developed for vector operations, with a great community, and more than 7000 packages to add capabilities. For interfaces, you can use R's IDE or use the terminal directly, or Rstudio.com, or even Jupyter. R is command line: you type lines of codes to get the commands outputs. It is nice for replicability.
The beauty of R is in the packages available to extend its capabilities:
- [CRAN](https://cran.rstudio.com/) (Comprehensive R Archive Network): organize packages in task views and for each one, we have datasets, manual in pdf formats and also vignettes illusrating examples.
- Crantastic: an interface that links to CRAN but that shows the popuarity and updates of packages. Unfortyunately, it was removed from the Internet.


### Python Programming
It is a general purpose programeasy to use that can do it all. Python is built-in on Mac or Linux, and has a great community with thousands of packages. The only problem is there is some compatibility versions between Python versions. Python has its own IDLE, but you can run it from the terminal or from a jupyter notebook (IPython: for Interactive Python or Python in Jupyter). There are also Continuum Analytics now [Anaconda](https://www.anaconda.com/download) & Enthought Canopy now [Enthought Deployment Manager](https://assets.enthought.com/downloads/) that offers Python distributions. Python is also command line: we are typing line to code. Data Science loves Jupyter and Jupyter loves data science: text output and markdown, inline graphics, ease to organize & present in notebooks. The main Python repository is **PyPI** (Python Package Index). Familiar packages are Numpy & Scipy for scientific computing, Matplotlb & Seaboorn for data visualization, Pandas for statistical analyses and scikit-learn for ML.


### SQL (Structured Query Language)
It is the language of databases (where the data is), that can be used i different applications. It is designed for relational databases, which are ways of storing structured data, and helps manipulate data s we can export them intoanalyical applications.
**RDBMS** are relational daabase management systems  where we usually manipulate data with SQL. Some freee an open source versions are Oracle Database, Microsoft SQL Server, MySQL, PostgreSQL. Databases minimize redundancy by using connected tables. There are some graphical user interfaces (GUI) like: SQL Developer, SQL Server Management Studio, [Toad](https://toadworld.com/products/), etc. and also any command line interface or any interactive devolpement environment or programming tool.
Some basic SQL commands are: 
```sql
Select -- to choose the case to include
From -- to specify the table
Where -- for conditions
Order by -- order to put them together
```
You don't have to be a ninja. Handful commands will be enough.


### C, C++, Java
There are most often seen in the bedrock: the absolute foundamental layer that makes the rest of data science possible.
**C** and **C++** are from 1960s and 1980s. They are widely used, and very fast and stable, which makes them suitable for production level code and sever use. They can be used in R.
**Java** is based on C/C++, and can be run anywhere (WORA: write once run everywhere). Its portability makes it the most popular language overall against all tech siuations. When something has to be fast and should not break, it is generally used, and typically by engineers (for the back end of data science).


### Bash
It is accessible on the command line interface: which is only a method of interacting. Shells are languages that help the user interact with the operating system. On Macs & Linux, the most common is **Bash**: Bourne Again Shell. On Windows, there is **PowerShell**. There are other versions: Bourne Shell, C Shell, Z Shell, fish, etc.
Good to know:
- $ indicates the prompt (type your command here).
- We type one line at a time.
- we can run scripts to execute more than one line.
In Bash, there are utilities (specific programs accomplishing specific tools). There are tw categories of utilities:
- **Built-ins**: *cat*: catenate to put information together, *awk* for text processing, *grep* for global search with a regular expression and print, *sed* for stream editor, to transform text. Some others are *head* & *tail*, to display the first or last lines of a document, *sort* & *uniq* to sort and count unique answer in a document, *wc* for the words count, and *printf* to format the outputin the console.
- **Installables**: *jq* for pulling in json data from the web, *json2csv* for file conversion, *Rio* to run R commands as part of bash, *BigMLer* to access BigML server through the command line. 

Utilities are fast easy and very practical.


### Regex
To be able to find the things you are looking for, regular expressions is a great method. Regular expressions are a form of pattern matching in text. We can write specific or very general patterns to search data and export it elsewhere for analyses. To search for text, in all text files in ".txt" format, that start with "l" and then continues with one character following, and then with "ve", we can write:
```bash
grep ^l.ve *.txt
```
In terms of the actual notes involved in regular expressions, there are certain elements:
- **literals**: that mean exactly what they are, i.e: "l"
- **metacharacters**: sort of chracters secifying things need to be there, i.e: "."
- **escape sequences**: to look for a period as opposed to a placeholder, i.e: "\n"
- **search expression**: the expression created, i.e: "^l.ve"
- **target string**: the thing we are searching through, i.e: *.txt for files when using grep.
![Quick Search](images/regex_elts.png)
[Regex Golf](http://alf.nu/RegexGolf) is a nice platform to play with regular expressions.


## Conclusion

You can start working with some tools but remember t=data tools are different from data science. Data Science is much more!!! Tools are just means and you do not need to know all of them. Focus on what is most suitable to you and your goals of extracting meaning from data. Here are some recommendations:
[Tools Recommendations](images/coding_tools.png)

---

# Mathematics in sata science

---