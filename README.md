# Matplotlib Plots
Matplotlib Exercise - The Power of Plots
<br>
<i>(matplotlib-challenge)</i>

## Background
While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Observations
• Measurements taken from Capomulin, Ramicare, Ketapril and Naftisol show that they are the most promising drugs of the trial.
• Ceftamin had the largest IQR, which suggest variability.
• There is a positive correlation between tumor volume and mouse weight.

## Summary Statistics Table
![Screen Shot 2021-04-20 at 12 04 41 AM](https://user-images.githubusercontent.com/22499952/115336437-40774e80-a16d-11eb-9274-b51c73f0765d.png)

## Bar plot
<i>Using Panda's DataFrame.plot()</i>
![Screen Shot 2021-04-20 at 12 04 49 AM](https://user-images.githubusercontent.com/22499952/115336463-4c631080-a16d-11eb-878b-def74d553abf.png)

<i>Using Matplotlib's pyplot</i>
![Screen Shot 2021-04-20 at 12 04 56 AM](https://user-images.githubusercontent.com/22499952/115336511-600e7700-a16d-11eb-8c7f-1fd199d970ba.png)

## Pie Chart
<i>Using Panda's DataFrame.plot()</i>
![Screen Shot 2021-04-20 at 12 05 05 AM](https://user-images.githubusercontent.com/22499952/115336644-93510600-a16d-11eb-9774-e29c4111d842.png)

<i>Using Matplotlib's pyplot</i>
![Screen Shot 2021-04-20 at 12 05 12 AM](https://user-images.githubusercontent.com/22499952/115336659-98ae5080-a16d-11eb-92e9-c28f593c6537.png)

## Calculate the final tumor volume of each mouse
<i>Calculate the quartiles and IQR and detemrine if there are any potential outliers</i>
![Screen Shot 2021-04-20 at 12 05 29 AM](https://user-images.githubusercontent.com/22499952/115336748-c72c2b80-a16d-11eb-9536-cbb3dad72e6d.png)

## Generate a box and whisker plot for all four treatment regimens
![Screen Shot 2021-04-20 at 12 05 22 AM](https://user-images.githubusercontent.com/22499952/115336756-cb584900-a16d-11eb-97d2-5df5202ad963.png)

## Generate a line plot of tumor volume vs. time point
![Screen Shot 2021-04-20 at 12 05 35 AM](https://user-images.githubusercontent.com/22499952/115336857-f773ca00-a16d-11eb-9361-911430c7279e.png)

## Generate a scatter plot of tumor volume vs. mouse weight
![Screen Shot 2021-04-20 at 12 05 40 AM](https://user-images.githubusercontent.com/22499952/115336957-2427e180-a16e-11eb-8602-a8e5abac6a56.png)

## Plot the linear regression model on top of the previous scatter plot
![Screen Shot 2021-04-20 at 12 05 46 AM](https://user-images.githubusercontent.com/22499952/115336918-14100200-a16e-11eb-8f4a-df295a88f74b.png)
