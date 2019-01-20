# ADA2018-Project

Report submitted: Data_Science_for_Good__Policing_and_Census.pdf

# Abstract

In recent years, the surge in the use of social media has enabled the realities of different
closely-knitted communities to be shared across the social fabric. Events of which
individuals within each community were well aware of for decades have now become common
social knowledge. For instance, the shooting of Michael Brown by a white officer
of the Ferguson Police Department, led eventually to the #BlackLivesMatter movement,
centered around campaigning against violence and systemic racism towards black people
in the US criminal justice system. The issues raised by this group no longer resonate
solely among the African-American community as it’s call for change has been heeded by
a significant fraction of the society. It is now understood that in order to fix the system
individual corrections of elements of the system are not enough. Rather, systemic racism
if existent, must be uprooted by implementing policy changes that address individual
issues as soon as they are detected.

In the hope of completing this task, many initiatives have been proposed to address
these issues, ranging from instructing all officers to wear body cameras recording all incidents
the officers are called to, to mandatory equipment of non-lethal weapons to prevent
fatal shootings from happening. These solutions fail to get a comprehensive picture of
how crime occurs in cities, how heterogeneously it is distributed through urban landscapes
and how the socioeconomic inequalities between offender and victim are determinant. We
will work with data released by the Center for policing equity [1], to propose solutions
helping police departments fighting crime and improving public safety.

# Research questions

• How is crime distributed cities and how heteregeneous is it in terms of the identity
of the offender and the victim?
• How are the crime patterns observed related to the sociodemographic indicators of
the areas where it occured?
• What actions in terms of police deployment policies and social intervention measures
should be followed in order to relieve the pressure of police intervention in different
communities?
• What types of visualization can be used to show the current state of the problem
• How can predictive algorithms be used on the joint census and crime dataset to
reach this task ?

# Dataset
In our project we will use Police department shapefiles, American community survey,
and various police incident data [2]. These data have been collected from 12 different
Police departments in the United States. We have descriptions of all variables in ACS
files (ACS-American community survey). ACS data files contain data about education,
income, race, sex, age, owner occupied housing and poverty status. (census data) For
each PD we also have shapefiles and reports about incidents of different types.
Incident reports are all in .csv format.
ACS data files appear in .csv and .txt format and shapefiles appear in 13 different formats.
Possible ideas to make data handling easier are to divide ACS files according to the Feature they represent, divide shapefiles according to the format and use appropriate Python function for loading into pandas or some other library.

Our task will be to combine these
data files and to visualize police behaviour in corresponding deployment areas.

# A list of internal milestones up until project milestone 2

- Provide an Exploratory Data Analysis Notebook to understand the dataset
- Cross ACS survey data with crime data
- Create visualization methods able to convey an understanding if the current state
of the problem
- Train ML predictors to be able to yield probability of events given police deployment,
crime statistics and socioeconomical indicators

# Questions for TAs
- Is the idea fitting to the social good topic?
- Is it wise to enrich the dataset with external feeds from twitter collected around
hashtags related to the (#BlackLivesMatter,# BlueLivesMatter, ...)
- Should we focus more on provinding reliable analytics or helpful visualizations?


# Contributions:
- Adnan: Contact with the teachers, github README mantaining, initial census analysis, final presentation
- Maxime: Blank
- Jacob: Project Proposal, Data Crawling and Analysis (Notebook), Report, Poster, Slides

# References

[1] Center for policing equity. http://policingequity.org/. [Online; accessed 04-
November-2018].
[2] Center for Policing Equity. Data Science for Good: Center for Policing
Equity. https://www.kaggle.com/center-for-policing-equity/
data-science-for-good/home, 2018. [Online; accessed 04-November-2018].
• Write up blog post to go with the notebook
