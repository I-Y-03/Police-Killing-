# Police-Killing-
Statistical Analysis of Police Killings 

<!-- Output copied to clipboard! -->

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.322 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Sat Feb 05 2022 15:50:19 GMT-0800 (PST)
* Source doc: Untitled document
----->



## **Dataset & Availability**


##### 1. **Police_killings data set 1 (2015)**

We sourced data from github that recorded all the deaths that have occurred by police killings in 2015, USA (468 observations). The dataset includes demographics such as gender, race, income level, whether they were armed or not (if so what type of weapons), how they were killed (i.e., gunshot, hit by vehicle, etc.), city, state and more. The data set originally was sourced by this project called “The counted” by the Guardian which created an interactive database of people killed by police in 2015 and 2016. However, [data.fivethirtyeight](https://fivethirtyeight.com/features/where-police-have-killed-americans-in-2015/) and authors who published on that website decided to take “the Counted” data and combine it with census data so that demographics and economic data are taken into account, and it serves as a starting point for other people who are interested to build on.


##### 2. **Police_killings data set 2 (2015 onwards)**

We also sourced another dataset from github that recorded police killings from 2015 onwards (6800 observations). This dataset does not include varibales talking about demogeaphics such as household income, college eduction, detailed race variables. However, it does have varibales talking about mental health and whether the deceased attempted to flee or not and threat level


##### 3. **Household income dataset of 2018**

Used in later analysis for inner join with dataset 2 after filtering dataset 2 to only deaths from 2018.
