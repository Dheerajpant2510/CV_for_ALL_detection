# CV_for_ALL_detection
Acute Lymphoblastic Leukemia detection using Computer Vision
# Omdena Liverpool Chapter
## Detecting Pediatric Acute Lymphoblastic Leukemia using Computer Vision

### The Background

In ALL there is an accumulation in the bone marrow of immature lymphocyte precursor cells, called blast cells. Eventually the production of normal blood cells is affected by this, resulting in a reduction in the numbers of red cells, normal white cells and platelets in the blood.

ALL is the only form of leukaemia that is more common in children than adults. It is the single most common form of paediatric cancer, accounting for about one-third of all cases in children. About 85% of cases of childhood leukaemia are ALL and it occurs in about 400 children in the UK each year. ALL occurs mostly between the ages of about two and four years. Males are affected more often than females at all ages.

### The Issue

The task of identifying immature leukemic blasts from normal cells under the microscope is challenging due to morphological similarity, this can make the diagnosis time consuming and costly.  

### The Goal

The goal of the project is to build a model which will make early identification of paediatric ALL quick and cost effective – this will allow early treatment to be sought and potentially save the lives of those who are afflicted.  

### The Learning Outcomes / Process

* Data collecting / organisation 
* Data cleaning / augmentation / engineering
* Exploratory Analysis  
*  Building a Computer Vision model
* Develop and deploy an app. 


## Contribution Guidelines
- Have a Look at the [project structure](#project-structure) and [folder overview](#folder-overview) below to understand where to store/upload your contribution
- If you're creating a task, Go to the task folder and create a new folder with the below naming convention and add a README.md with task details and goals to help other contributors understand
    - Task Folder Naming Convention : _task-n-taskname.(n is the task number)_  ex: task-1-data-analysis, task-2-model-deployment etc.
    - Create a README.md with a table containing information table about all contributions for the task.
- If you're contributing for a task, please make sure to store in relavant location and update the README.md information table with your contribution details.
- Make sure your File names(jupyter notebooks, python files, data sheet file names etc) has proper naming to help others in easily identifing them.
- Please restrict yourself from creating unnessesary folders other than in 'tasks' folder (as above mentioned naming convention) to avoid confusion. 

## Project Structure

    ├── LICENSE
    ├── README.md          <- The top-level README for developers/collaborators using this project.
    ├── original           <- Original Source Code of the challenge hosted by omdena. Can be used as a reference code for the current project goal.
    │ 
    │
    ├── reports            <- Folder containing the final reports/results of this project
    │   └── README.md      <- Details about final reports and analysis
    │ 
    │   
    ├── src                <- Source code folder for this project
        │
        ├── data           <- Datasets used and collected for this project
        │   
        ├── docs           <- Folder for Task documentations, Meeting Presentations and task Workflow Documents and Diagrams.
        │
        ├── references     <- Data dictionaries, manuals, and all other explanatory references used 
        │
        ├── tasks          <- Master folder for all individual task folders
        │
        ├── visualizations <- Code and Visualization dashboards generated for the project
        │
        └── results        <- Folder to store Final analysis and modelling results and code.
--------

## Folder Overview

- Original          - Folder Containing old/completed Omdena challenge code.
- Reports           - Folder to store all Final Reports of this project
- Data              - Folder to Store all the data collected and used for this project 
- Docs              - Folder for Task documentations, Meeting Presentations and task Workflow Documents and Diagrams.
- References        - Folder to store any referneced code/research papers and other useful documents used for this project
- Tasks             - Master folder for all tasks
  - All Task Folder names should follow specific naming convention
  - All Task folder names should be in chronologial order (from 1 to n)
  - All Task folders should have a README.md file with task Details and task goals along with an info table containing all code/notebook files with their links and information
  - Update the [task-table](./src/tasks/README.md#task-table) whenever a task is created and explain the purpose and goals of the task to others.
- Visualization     - Folder to store dashboards, analysis and visualization reports
- Results           - Folder to store final analysis modelling results for the project.


