# Matplotlib Challenge - The Power of Plots

## Pymaceuticals
While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've since joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, CA. Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. In their most recent efforts, they've since begun screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As their Chief Data Analyst, you've been given access to the complete data from their most recent animal study. In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. Your objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

To do this you are tasked with:

* Creating a scatter plot that shows how the tumor volume changes over time for each treatment.
* Creating a scatter plot that shows how the number of [metastatic](https://en.wikipedia.org/wiki/Metastasis) (cancer spreading) sites changes over time for each treatment.
* Creating a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
* Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.
* Include 3 observations about the results of the study. Use the visualizations you generated from the study data as the basis for your observations.

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must use the Matplotlib library.
* You must include a written description of three observable trends based on the data.
* You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, X and Y Axis Limits, etc.
* Your scatter plots must include [error bars](https://en.wikipedia.org/wiki/Error_bar). This will allow the company to account for variability between mice. You may want to look into [`pandas.DataFrame.sem`](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sem.html) for ideas on how to calculate this.
* Remember when making your plots to consider aesthetics!
  * Your legends should not be overlaid on top of any data.
  * Your bar graph should indicate tumor growth as red and tumor reduction as green.
    It should also include a label with the percentage change for each bar. You may want to consult this [tutorial

-----
## Observations Based on Data
1. Capomulin was significantly the most successful at treating tumors for mice. As seen in the plot titled "Tumor Response to Treatment," it is seen that it was the only drug that reduced the total tumor volume during the time frame of treatment. It also had the highest survival rate compared to the other treatments as seen in "Survival During Treatment." While spread of metastatic sites still increased for this drug, it was much less in comparison to the other treatments as seen in "Metastatic Spread During Treatment." Capomulin is an effective method of treatment and is recommended to advance to the next round of studies.
2. Ketapril was the least effective at treating tumor volume. As seen in plot "Tumor Response to Treatment," it had slightly greater average growth over the time span than the placebo group. Ketapril had a slower average increase in metastatic sites than the Placebo group during time frame of treatment, but overall the number of metatastic sites were similar by the end of treatment as seen in "Metastatic Spread During Treatment." Ketapril's surival rates are comparable to the placebo at the end of the time frame of treatment as seen in "Survival During Treatment." Ketapril is not an effective method of treatment and is not recommended to advance to the next round of studies.
3. Infubinol performed consistently better than placebo in terms of slightly decreased average rate of tumor volume growth as seen in plot "Tumor Response to Treatment." It also showed slower rates of metastatic spread in comparison to placebo as seen in "Metastatic Spread During Treatment." However, survival rate for Infubinol is inconsistant throughout the duration of the time frame for treatment in comparison to placebo, sometimes going above or below the rate of survival of placebo as seen in "Survival During Treatment." By the end of the trial, Infubinol had the lowest survival rate of all treatments. More testing need to be conducted for Infubinol for its effectiveness, but overall due to the inconsistent rates of survival over the duration of treatment, Infubinol is not recommended to advance to the next round of studies.
