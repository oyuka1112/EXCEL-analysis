# Excel analysis
## Overview of the project
The Purpose is to analyze the excel data of over 4000 crodfunding projects. The dataset has 4115 rows and 21 columns (kickstarter sheet).To analyze: used filtering and sorting, created pivot tables, used handful formulas, used VLOOKUP, and created useful graphs to better explain the dataset.

## Analysis and Challenges
- Analysis: 
   - In the Theater Outcomes on Launch Date sheet:
      - Created pivot table from the original dataset
      - Used filters on "Parent category" and "Years" columns
      - "Parent Category" is filtered on theater
      - Created line chart that illustrates if the theater crowdfunding was successful, failed, or canceled by what month it was launched. 
    - In the Outcomes Based on Goals sheet:
      - Used COUNTIFS() function to get the number of "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome," the "goal" amount using the goal ranges in Step 3, and the Subcategory "plays"
      - Calculated the percentage rate of successful, failed, and canceled projects
      - Created the line chart that illustrates the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis
- Challenges: 
  - :thought_balloon: First challenge is that I needed to look at how to change a title for the pivot table's chart. I looked at the Excel documentation and found out how to change it.
  - :thought_balloon: Second challenge is that I needed to get emoji for the README file, so I looked at [the Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).
  - :thought_balloon: Any other possible challenges that could come up, I will definetily search [Google](https://google.com), [Excel documentation](https://support.microsoft.com/en-us/excel), and [Github README documentation](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
## Results
![](https://user-images.githubusercontent.com/64121596/138591613-3f48635d-9a22-475b-9a12-3d95b51e0cce.png)
- The first conclusion from the Theater Outcomes Based on Launch Date is that there is very few number of canceled theater crowdfunding events than the successful one. Usually it's successful rather than canceled or failed. 
- The second conclusion is that if theater crowdfunding launches during summer (especiually May), it's more likely to be successful.

![](https://user-images.githubusercontent.com/64121596/138591581-a5891930-c549-499f-979e-4cd9f0818d44.png)
The crowdfunding from the "plays" subcategory, nothing was canceled. It was either successful or failed.

### Limitations
1. The outlier could affect our analysis: the goal 100,000,000
2. Currency difference
3. Crowdfundings were made in different countries, so it might not well represent every situations.
### Possible tables and/or graphs
1. The graph that shows the difference between pledged and goal, whether it was successful, failed, or canceled
2. The graph that shows the duration of the campaigns, whether it was successful, failed, or canceled
3. The table that shows by countries
4. The table that shows by categories

