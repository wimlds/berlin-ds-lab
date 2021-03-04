# Handbook

This (still growing/changing) document contains all the details about the program.

## Timeline

The mentorship consists of ~10 weeks, roughly following this structure:

* Weeks 1-2: Kick-off, project introduction and ideation
* Weeks 3-4: Exploratory data analysis, data cleaning
* Weeks 5-6: Evaluation setup, baseline model
* Weeks 7-8: Feature construction and improved model
* Weeks 9-10: Client handover and technical handover

You should be available for two 1-hour long calls per week:
* Call 1: team+advisors: present progress, discuss next steps (see details below)
* Call 2: planning/sync with your teammates

There will also be two additional calls aimed at personal growth/team dynamics:
* Week 3-4: retrospective (focused on team collaboration) 
* Week 5-6: individual feedback session with your advisor(s)

[Here is an example of the whole timeline.](https://github.com/wimlds/berlin-ds-lab/blob/master/handbook.md)

## Steps

### Project introduction / ideation

You will get a brief by your (fake) client. Your task is to figure out what the client actually wants and convince them that *your* team is the right one to build the solution for them. 

* What is the problem they actually want solved?
* What positive impact could solving the problem have for them? 
* Who do you need to consider (users, other departments, employees, customers, etc) when defining the product?
* Describe the product/solution you are going to build for them.
* Identify how the solution integrates into the business/organization processes. Who uses it when and how.
* Identify KPIs for measuring your success.

You will present your results to the client and have the chance to ask additional questions about the business problem (reminder: client is fake and will be played by your mentors).

Next, very important step: translation from business problem to data science

* What kind of model are you going to build?
* How do the business KPIs you defined translate to actual data science metrics?


### Exploratory data analysis, data cleaning

* Use whatever tools you like to explore the data. Find out,
    * Do you fully understand what each column means?
    * Over what time range / region do you have data?
    * Missing values / outliers?
    * Make some plots of the data distributions. Check if they are what you would expect.
    * Is there any other data set available somewhere that could make your data stronger? e.g. historic weather data, list of holidays, demographic / census data

* Data cleaning
    * You might decide to use only a subset of the data and, e.g. set aside some columns with sparse data for later use
    * Decide how to fill in missing values
    * Decide how to identify and handle outliers
 
### Evaluation setup, baseline model

* Define your target variable
* Set up your evaluation procedure and metrics 
* Establish a baseline. This is the simplest model you can think of.

### Feature construction and improved model

* Experiment (in an deliberate manner) with:
    * different features
    * different models
    * different data improvement techniques
  

## Client handover and technical handover

You'll handover your work to your client as well as to a technical team that
is going to continue working on the project (as usual, both client as well
as technical teams are fake and played by your mentors). You will base your
portfolio material on these handovers.

### Client handover

Present your results to your "client". Train using language your client can understand and not making it too technical.


### Technical handover

Prepare a handover presentation to your client's in-house data scientists. Train writing clear technical communication, which is still business minded. This can be a well documented github repository, jupyter notebook, or a technical presentation.

Time to polish your code repository and write everything up nicely. We'll give feedback! 

## Weekly calls with advisors

### Technical presentations

* First ~10 minutes: one of you (not the same one every week!) presents your work of the previous week to us
* Rest: open discussion and plan next week
    * We want you to come with your own ideas for next steps, we are just there to give you some guidance on them.
* Presentation format:
    * free-format: slides, R/jupyter notebooks, tableau, write on whiteboard -- whatever works for you
    * but come prepared, showcase the most interesting parts of your work in the previous week

#### Client presentation

* You are presenting to the person who gave you the brief (played by your mentors)
* First week: two people present (individually, i.e. two different presentations)
* Final week: other two people present
* Presentation format:
    * slides
    * Don't make it too technical!
  
## Project management, team work, tools

### Project management
* To keep track of tasks, and update each other on progress

### Team work

* We encourage self-organised pair-programming and peer code-reviews and can advise you on how to get started
* Retrospective to improve team collaboration

### Tools

* Project management: agile tool of your choice, e.g. trello, asana
* Code collaboration: git, team viewer, vs code
* Data exploration / visualisation: whatever you like
* Coding: python, R (decide within your team)
