# **_dataLawUS_**

#### **_[GitHub link](https://github.com/andrewblais/dataLawUS)_**

A Python Jupyter Notebook project whose structure was created by Angela Yu and which I completed for Professional Portfolio Project: Assignment 19: [Angela Yu 100 Days of Code](https://www.udemy.com/course/100-days-of-code/) -- "Data Science: Analyse Deaths involving Police in the United States".

Lots of Pandas/NumPy and plotting challenges curated by Angela Yu.

This project required a lot of attention to detail regarding data transformation and DataFrame/Series manipulation with many different Pandas functions.

_[MIT License](https://github.com/andrewblais/dataLawUS/blob/main/LICENSE): Copyright (c) 2024- Andrew Blais_

This is the FINAL project in Angela Yu's 100 Day's course.

-   [Angela's course](https://www.udemy.com/course/100-days-of-code/)

### **_Libraries Utilized:_**

-   [Python](https://www.python.org/)

-   [Matplotlib](https://matplotlib.org/)

-   [NumPy](https://numpy.org/)

-   [pandas](https://pandas.pydata.org/)

-   [Plotly](https://plotly.com/python/)

-   [seaborn](https://seaborn.pydata.org/)

---

### **_Project structure:_**

```
dataLawUS/
    .gitignore
    LICENSE
    main.ipynb
    main_updated_data_in_progress.ipynb
    README.md
    requirements.txt
    data/
        Deaths_by_Police_US.csv
        Deaths_by_Police_US_updated_2024.csv
        Median_Household_Income_2015.csv
        Pct_Over_25_Completed_High_School.csv
        Pct_People_Below_Poverty_Level.csv
        Share_of_Race_By_City.csv
    pdf/
        main.html
        main.pdf
    plots/
        01_states_poverty_seaborn.png
        02_states_poverty_matplotlib.png
        03_hs_pov_dual_plot.png
        04_hs_pov_scatter_hue.png
        05_hs_pov_scatter_kde_rug.png
        06_hs_pov_kde_rug.png
        07_hs_pov_regplot_lowess.png
        08_hs_pov_lmplot_scatter_markers.png
        09_hs_pov_lmplot_lowess.png
        10_hs_pov_lmplot_logx.png
        11_racial_pop_analysis.png
        12_police_killings_by_race.png
        13_age_vs_manner.png
        14_armed_unarmed.png
        15_weapon_type.png
        16_guns_vs_unarmed.png
        17_over_under_25.png
        18_hist_kde_age.png
        19_race_kde.png
        20_race_donut_chart.png
        21_mental_illness_pie.png
        22_cities_10.png
        23_cities_10_by_race.png
        24_choropleth_us_states.png
        25_killings_by_date.png
```

---

### **_Future Updates_**

-   Finish updating project with latest W.Post dataset (see `main_updated_data_in_progress.ipynb`)

-   Clarify/Re-Analyze statistics regarding population and race: consider bringing in another dataset which includes population number, not just share per city/region.

-   Expand scope of analysis and plots to other areas not included in the original project instructions/challenges.

-   More...

---

### **_Documentation:_**

Descriptive comments/Markdown clarification throughout `main.py`.

#### **_Requirements:_**

```requirements
matplotlib>=3.8.4
numpy>=1.26.4
pandas>=2.2.2
plotly>=5.22.0
seaborn>=0.13.2
```

---

## **_Created in completing the FINAL ASSIGNMENT for Angela Yu Course 100 Days of Code: The Complete Python Pro Bootcamp._**

### **Day 100, Professional Portfolio Project [Data Science]**

#### **_Assignment 19: "Analyse Deaths involving Police in the United States"_**

Extract insights from combining US census data and the Washington Post's database on deaths by police in the United States.

### **Assignment instructions:**

Today you will do some deep analysis around an incredibly sensitive and politically charged topic. Since Jan. 1, 2015, [The Washington Post](https://www.washingtonpost.com/) has been compiling a database of every fatal shooting in the US by a police officer in the line of duty. You will analyse this dataset together with US census data on poverty rate, high school graduation rate, median household income, and racial demographics. This way we better understand social trends and what is going on with the fatal use of force by the police in the United States.

---

### **_My Submission:_**

My project is viewable here: https://github.com/andrewblais/dataLawUS

---

### **Questions for this assignment**

#### _Reflection Time:_

**_Write down how you approached the project._**

I kept the previous day's data science project open in a separate tab for reference, as well as gathering all of the lessons from the course which related to today's assignment. It's good to have a cache of reference material with which I'm familiar.

I changed slightly some of the Markdown formatting in the `.ipynb` file, resizing and making bold a few headings and adding dividers for clarity, etc...

Once I had all the project's directories and files ready, I searched online for updated versions of the datasets, but had some trouble with this. In the end I realized the Washington Post link in the description actually had the updated .csv for `df_fatalities` -- I'll utilize this in a future refactor.

**_What was hard?_**

The hardest part for me was some of the advanced plotting challenges. Although I understood what was happening in the multi-subplot pie chart I made for the `Rate of Death by Race` question, it required a lot of effort and research to complete.

**_What was easy?_**

This project really helped solidify my knowledge of some of the basic and intermediate challenges faced when transforming/curating DataFrames with Pandas. I'm very glad to have worked so hard through these questions and practiced so much.

My favorite parts and possibly the easiest -- which allow for a nice break from some of the tougher work -- was curating lists of CSS colors for the plots, as well as making the Markdown look as good as possible. I really enjoy the simplicity and logic of Markdown.

**_How might you improve for the next project?_**

Read ahead sooner, and plan some of the interactions between elements in DataFrames a bit more comprehensively.

Get a higher-level understanding of the data analysis, don't just work on the coding aspect -- the purpose of this kind of work ultimately is not to code, but to understand the data and social issues behind it.

**_What was your biggest learning from today?_**

Pandas, pandas, pandas....and to a large extend Plotly, Seaborn and Matplotlib. Also NumPy. To clarify, I felt like I really brushed up and expanded my knowledge of these libraries.

**_What would you do differently if you were to tackle this project again?_**

I would read more carefully through the entire project's challenges to get a clear idea of what lies ahead, rather than just diving in head first.

It will require a second pass to complete the challenges to a standard I feel that I'm capable of.

Thank you so much for this wonderful course, Angela! I worked really hard and feel like I've learned so much, and bolstered my confidence as well. Kudos to the team at The App Brewery!
