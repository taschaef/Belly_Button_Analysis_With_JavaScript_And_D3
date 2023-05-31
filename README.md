# belly-button-challenge
This site is live at:  https://taschaef.github.io/belly-button-challenge/

# Background
In this assignment, I was asked to build an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare

## First Steps 
1. I created a new repository for this project called belly-button-challenge.
2. I cloned the new repository to my computer.
3. Inside my local git repository, I copied the files from in the StarterCode folder contained within the Module 14 Challenge zip file. i.e. index.html, samples.json, and the static folder. In addition, I copied in the samples.json file because it was part of my project and therefore I thought it should be included in my repository. 

# Instructions
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

  * Use sample_values as the values for the bar chart.

  * Use otu_ids as the labels for the bar chart.

  * Use otu_labels as the hovertext for the chart.

<img width="356" alt="image" src="https://github.com/taschaef/belly-button-challenge/assets/124079708/b7b32e0a-2a67-41e0-a309-6d749e1fcac1">

3. Create a bubble chart that displays each sample.

  * Use otu_ids for the x values.

  * Use sample_values for the y values.

  * Use sample_values for the marker size.

  * Use otu_ids for the marker colors.

  * Use otu_labels for the text values.

<img width="381" alt="image" src="https://github.com/taschaef/belly-button-challenge/assets/124079708/4ca90aab-2831-49d6-8259-c251ba339b5b">

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

<img width="149" alt="image" src="https://github.com/taschaef/belly-button-challenge/assets/124079708/a6d71be8-55ae-4cc3-b74a-8e271db067db">

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

# Resources 
1. Stack Overflow 
2. AskBCS
3. Plotly Documentation https://plotly.com/javascript/
4. W3 Schools - JavaScript & HTML Dom Reference https://www.w3schools.com/jsrEF/default.asp
 



