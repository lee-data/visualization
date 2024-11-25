# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      
      ```
      Please see my answer below: 

        # GOOD VISUALITION
        The visualization I choose is the Resource Trade interactive dashboard from https://resourcetrade.earth/.  The dashboard allows users to explore trade flows between over 200 countries and territories, covering more than 1,350 different types of natural resources and products.  
        Please see below my assessment based on its aesthetic, substantive, and perceptual qualities:
        
        ### Aesthetic Quality:
        •	Strengths:
        o	Clean and professional design
        o	Harmonious color palette that enhances visual appeal.
        o	Distinct colors (red for importer, blue for exporter) in combination with sizes (narrow for exporter, wide for importer) increases comprehension. 
        o	Interactive elements, such as hover-over details and clickable regions, provide an engaging user experience.
        o	Users can also zoom in on a particular region, country, market group, type of commodities, and year, in a consistent design and color palette. 
        •	Weaknesses:
        o	Colorblind users may find challenges navigating this website. (*Note: However, the designer has thoughtfully included sizes (narrow for exporter, wide for importer) to help improve accessibility.)
        o	The density of information can be overwhelming for first-time users, and would require a small learning curve to navigate effectively. (*Note: However, this is expected. And it is admirable that the visualization designers can include many complex information in this dashboard and the navigation is straight-forward too.)
        ### Substantive Quality:
        •	Strengths:
        o	It allows users to explore trade flows between over 200 countries and territories, covering more than 1,350 different types of natural resources and products. (Reference: https://resourcetrade.earth/about.) 
        •	Weaknesses:
        o	The dashboard presents data only up to 2024.  
        o	Some data categories are broad, which might obscure specific details about certain commodities or trade relationships. (*Note: However, this is expected, because there are 1,350 types of natural resources and products, across 200 countries.)
        o	The reliance on self-reported data from countries could introduce inconsistencies or inaccuracies.
        ### Perceptual Quality:
        •	Strengths:
        o	The visualization effectively communicates complex trade relationships through intuitive maps and charts, facilitating user understanding.
        o	Interactive features, such as filtering by commodity, country, or year, enable users to tailor the data view to their interests, enhancing clarity.
        •	Weaknesses:
        o	The abundance of features and information may lead to cognitive overload, and can be overwhelming for first-time users. 

      ```
    - How could this data visualization have been improved?  
      ```
      ### Suggestions for Improvement:
        1.	Enhance Accessibility:
        o	To improve accessibility for color-blind audience, we may additionally create an ‘accessibility’ color palettes in the dashboard settings, and allow users to switch between default viewing and accessibility viewing. 
        2.	Simplify User Interface:
        o	The user-interface in my view is easy to navigate, but there are readers who maybe less technical. We may optionally introduce guided tutorials to assist them.  
        3.	Improve Data Granularity:
        o	We may optionally introduce metadata or data quality indicators to inform users about the reliability and sources of the data presented. (*Note: Although the tradeoff for that could be cognitive overload, adding information to an already information-dense dashboard.)
      
      ```

```
      
BAD VISUALIZATION
The visualization I chose is the violin plots from Andrew Wheeler’s blog post, "Bean plots in SPSS". Andrew demonstrated how to create bean plots in SPSS using a synthetic dataset of 1,000 observations across five categories (“cat 0” to “cat 4”). His focus was on the technical creation of bean plots, not their presentation or interpretative clarity, which is why labels, legends, and titles were omitted.
Assessment of the Visualization
1. Aesthetic Quality
•	Strengths: 
o	Consistent colors for each category.
o	Violin plots blend boxplots and density plots, which can offer rich insights.
•	Weaknesses: 
o	The black/white/gray design in the first plot lacks polish and appears cluttered.
o	The colored plot contrasts distributions with colors and uses dots instead of bar rugs, but the dots are visually distracting, making it harder to identify central tendencies.
2. Substantive Quality
•	Strengths: 
o	Provides detailed views of data distributions with individual data points for granularity.
•	Weaknesses: 
o	Violin plots can be unintuitive for non-technical audiences.
o	The use of data points over bar rugs complicates the interpretation of distributions.
o	Missing key statistical summaries (e.g., medians, quartiles) reduces clarity.
3. Perceptual Quality
•	Weaknesses: 
o	No meaningful titles, labels, or annotations to explain the plots’ purpose or statistical properties.
o	Patterns and group comparisons are difficult to discern.

      ```
    - How could this data visualization have been improved?  
      ```
      Suggestions for Improvement
1.	Simplify Design: 
o	Replace data points with bar rugs to reduce visual clutter.
2.	Enhance Clarity: 
o	Add statistical summaries like medians or quartiles, either in the same plot or separately to avoid overcrowding.
3.	Add Context: 
o	Include titles, labels, and legends for color and shading explanations.
o	Use captions to emphasize key takeaways.
4.	Consider Alternatives: 
o	Use simpler visualizations like boxplots, histograms, or dot plots, especially for non-technical audiences, to reduce cognitive load and improve comprehension.

      
      ```



      
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
