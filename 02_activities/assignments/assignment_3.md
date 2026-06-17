# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?


Original Data:
Software Used

The original dashboard was created using a dashboard-based data visualization tool that supports multiple charts and interactive design features (Microscoft Business Intelligence Tool).

Intended Audience

The intended audience includes transportation planners, policymakers, researchers, and members of the public interested in road safety.

Message

The dashboard summarizes traffic fatalities from 2022–2026 by showing overall yearly trends, involvement type, and age-group distributions. The goal is to identify populations most affected by fatal collisions.

Design Considerations

Four chart types were used to communicate different aspects of the data. Bar charts compare yearly totals and age groups, the line chart highlights trends over time, and the donut chart shows proportions of fatalities by involvement category. Consistent colours, titles, and labels improve readability.

Reproducibility

The dashboard can be recreated using the same dataset and settings. However, some formatting choices may require manual adjustments, making reproducibility more difficult than code-based approaches.

Accessibility

Accessibility was improved through clear titles, axis labels, legends, and direct numerical labels on the bar charts. Information is communicated through position and size rather than colour alone.

Impacted Communities

The findings may be relevant to pedestrians, cyclists, drivers, transportation agencies, and local governments involved in road safety planning.

Feature Selection

Year, involvement type, and age group were selected because they clearly summarize fatality trends. More detailed variables were excluded to maintain simplicity.

Underwater Labour

The project required data collection, cleaning, category grouping, calculation of summary statistics, and refinement of the dashboard layout.

Visualization 2: Matplotlib Dashboard Recreation

Software Used

This dashboard was created using Python and the matplotlib library.


Design Considerations

The original 2×2 dashboard layout was preserved to facilitate comparison. Similar chart types were used because they effectively display trends, proportions, and comparisons. Titles, labels, legends, and value annotations were included to improve interpretation.

Reproducibility

Matplotlib provides strong reproducibility because all steps are documented in code. Anyone with the script can generate the same visualization, making the results easier to verify and modify.

Accessibility

The dashboard uses readable labels, consistent formatting, and direct value annotations. Multiple visual cues, such as position and bar length, reduce reliance on colour alone.

Impacted Communities

The visualization may support discussions among transportation agencies, researchers, community groups, and residents concerned with road safety.

Feature Selection

Only variables directly related to fatality trends were included. Less relevant details were omitted to keep the dashboard focused and easy to understand.

Underwater Labour

The recreation process involved coding, testing, selecting chart types, arranging subplots, and ensuring the final dashboard accurately reflected the original visualization.


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
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
