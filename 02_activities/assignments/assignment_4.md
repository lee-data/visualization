# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
     	## **EXCEL VISUALIZATIONS**
 	1) What software did you use to create your data visualization?
*My answer:* I used Microsoft Excel to create these data visualizations. 

 	2) Who is your intended audience?
 	*My answer:* My intended audiences are transit planners at TTC and the interested public viewers – who can be either technical and non-technical audiences.

 	3) What information or message are you trying to convey with your visualization?
 	*My answer*: I’m trying to show the audience the frequency (counts) of different features related to delay minutes.

 	4) What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
 	*My answer:*
## **Substantive Principles:** 
•	Clarity: Focused on showing streetcar delay distribution by feature names (e.g., line 505, incident Operations, etc), and ranked by frequency when possible for improved intuitiveness.
•	Data Prioritization: Ranked features by frequency and reduced to only top features when appropriate (e.g., Top 10 Incident Types) to improve comprehension.

## ** Perceptual Principles:** 
•	Readable Labels: Made the axes labels diagonal when appropriate to prevent overlapping texts (e.g., Line Name Distribution); Added annotation to explain data labels better (e.g.,  Line Types Distribution). 

•	Order of features display: Ranked features by frequency and reduced to only top features when appropriate (e.g., Top 10 Incident Types) to improve comprehension.; Ranked Time Type by order for improved comprehension (e.g., Off Peak, Morning Peak, Midday, Evening Peak). 
•	Color Consistency: Used a single purple tone to reduce cognitive overload. 
## **Aesthetic Principles:** 
•	Minimal Design: Clean layout with no clutter (e.g., no gridlines, no ticks), single consistent purple tone throughout across the visualization.
•	Professional Look: Balanced spacing, modern fonts, and visually distinct color that’s aesthetically pleasing. 

 	5) How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
*My answer:* 
	I chose Excel to improve accessibility for wider audiences (especially non-technical audiences) and also uploaded my Excel file (with cleaned data, and visualization in it) for reproducibility. I also uploaded the note with link to download raw data from TTC.  
 	
 	6) How did you ensure that your data visualization is accessible?
*My answer:* 
I chose a visually distinct and intense color (purple) against a white background, with black texts at medium font size, to improve accessibility.
 	
 	7) Who are the individuals and communities who might be impacted by your visualization?
 	*My answer:* 
The individuals and communities that might be impacted by my visualization include the transit planners at TTC, and people who use public transportation in Toronto (residents and visitors). 

 	8) How did you choose which features of your chosen dataset to include or exclude from your visualization?
 	*My answer:* 
I did separate plots, one for each of the categories, as part of my EDA (exploratory data analysis) to see the overall features distribution in the dataset. 

 	9) What ‘underwater labour’ contributed to your final data visualization product?
 	*My answer:* 
There was significant amount of effort on data pre-processing including data cleaning and feature engineering, before I could proceed to Excel visualization. (Please refer to the codes in my Python Visualization folder.)
---

 	## **PYTHON VISUALIZATIONS**
 	1) What software did you use to create your data visualization?
*My answer:* I used Python – Jupyter Notebook to create these data visualizations. 

 	2) Who is your intended audience?
 	*My answer:* My intended audiences are transit planners at TTC and the interested public viewers, who may need to have some knowledge in basic statistics. 

 	3) What information or message are you trying to convey with your visualization?
 	*My answer*: I’m trying to show the audience different angles: 
 	
 	A – The distribution of different Delay Types: 
 	- As histogram - to show that the ‘bucket’ selections for different Delay Types look normally distributed, and centered around Delay Type 2. 
 	- As a pie chart – to visualize the dominance of Delay Type 2 (normal delay, between 6-15 minutes) when compared to the entire dataset. 
 	
 	B – The dominance of different features within each Delay Type: 
 	- The Heatmaps for each category (e.g., Line, Location, Vehicle): to show which particular features dominate each Delay Type. 
 	- The Bar Plot for key categories against Delay Type 2 (the majority class): to show the frequency of the dominant categories within the majority delay type. 

 	4) What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
 	*My answer:*

## **Substantive Principles:**
o	The heatmaps help to identify trend and highlight intensity of trend (e.g., "Operations" with Delay Type 2).
o	The bar charts show how top features frequent within the majority delay type (normal delay, between 6-15 minutes).   

## **Perceptual Principles:**
•	Readability: Clear axis labels, legend, and ordered bars make data easy to interpret.
•	Color Usage: 
o	Heatmaps apply color intensity to highlight intensity of trend, across the different delay types, making it intuitive to interpret. 
o	The Heatmaps and Bar Plots have intense colors against white background, black color texts (labels, titles), with clear data values for each feature block, and no gridlines, for improved perceptual quality. 

## **Aesthetic Principles:**
•	Minimalistic design with clean layouts (ie. No gridline) avoids distractions.
•	Balanced spacing and modern colors ensure both visual appeal and professionalism.

 	5) How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
*My answer:* 
	I uploaded my Python code, and shared the link to download raw data from TTC, for reproducibility.  

 	6) How did you ensure that your data visualization is accessible?
*My answer:* 
I chose a Viridis color palette for all plots, against a white background, with black texts at medium font size, for accessibility.
 	
 	7) Who are the individuals and communities who might be impacted by your visualization?
 	*My answer:* 
The individuals and communities that might be impacted by my visualization include the transit planners at TTC, and people who use public transportation in Toronto (residents and visitors). 

 	8) How did you choose which features of your chosen dataset to include or exclude from your visualization?
 	*My answer:* 
I did separate plots, one for each of the categories, as part of my EDA (exploratory data analysis) to see the features dominance across the dataset as well as within the majority delay type (normal delay, between 6-15 minutes). 

 	9) What ‘underwater labour’ contributed to your final data visualization product?
 	*My answer:* 
There was significant amount of effort on data pre-processing including data cleaning and feature engineering. Please refer to the codes in my Python Visualization folder.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
