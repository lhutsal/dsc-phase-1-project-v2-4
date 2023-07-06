# Phase 1 Project Description

## Overview
This is a data analysis to determine what movies are currently successful at the box office and what attributes could be used to create movies in the future that are successful.<br>
Link to Notebook: https://github.com/lhutsal/dsc-phase-1-project-v2-4/blob/master/student.ipynb
<br>
Link to Presentation: https://github.com/lhutsal/dsc-phase-1-project-v2-4/blob/master/presentation.pdf

## Business Understanding
Microsoft is looking to create a new movie studio. I am tasked with finding out what is currently doing well at the box office and translating that analysis into actionable steps for the head of the new studio to decide what types of films to create.

## Data Understanding and Analysis
### Sources of data
1. Box Office Mojo
2. The Numbers
3. Internet Movie Database (IMDB)

### Description of data
The data is by movie and I found it most effective to create a combined unique field of movie name and year realeased in order to avoid any duplicate movie names that were released in different years.

Box Office Mojo contains Domestic and Foreign Box Office Revenue, however I found some issues with the data and ended up using the Box Office Revenue data from The Numbers.

The Numbers contains Worldwide Box Office Revenue, which was a key field that was used.

The IMDB data contains genre, runtime, ratings and number of votes. I had originally thought to use ratings and number of votes, but realized that it's an outcome of the finished movie and not an actionable input. The genre data was also very informative as certain genres produced significantly more revenue than others.
  
### Three visualizations (the same visualizations presented in the slides and notebook)
![runtime2](https://github.com/lhutsal/dsc-phase-1-project-v2-4/assets/129410801/90637dcd-398f-4c03-a6ba-32dee45b49dc)
![genre](https://github.com/lhutsal/dsc-phase-1-project-v2-4/assets/129410801/86d43841-b3c0-4599-9cff-494160f01d0d)
![prod_budget](https://github.com/lhutsal/dsc-phase-1-project-v2-4/assets/129410801/779320ac-f021-4d09-8b1f-564bda3acc25)

## Conclusion
After reviewing and analyzing the data, the follow key attributes were identified for making a successful film:
1. Genre: Action, Adventure or Comedy
2. Runtime: Target 120 minutes, no less than 87 minutes and no more than 169 minutes
3. Production Budget: Target $300MM-$400MM, with an expected 4x ROI
