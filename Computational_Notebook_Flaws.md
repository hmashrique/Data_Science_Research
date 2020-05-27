
# Whats wrong with Computational Notebooks (Austin's Paper) 

[Paper Link](http://web.eecs.utk.edu/~azh/pubs/Chattopadhyay2020CHI_NotebookPainpoints.pdf)

## Points on Paper for probable future works:

### Writing Code
- lack of code assistance in the notebooks.(Writing Code)
- Not possible "to explore the API's and functions" from within the notebook.(Writing Code)
- Users need to go back and forth using an IDE and notebooks for assistance.(Wriring Code)

### Managing Dependencies
- No way to manage dependency(packages,libraries) within the notebook. 
- No support for finding, removing, updating, or identifying deprecated packages.Users need to use command line to see 
  which are installed or not.
  
### Executing Notebooks
- Raises issue when a notebook kernel stops while executing.
- Inconsistent state can be hard to detect because there’s “no transparency in terms of understanding how the process is 
  being executed on the kernel" 
- Sometimes it’s easiest to just restart and run the whole notebook again

### Handling Big data is an issue
- notebooks cant handle big data loads, causing sudden crashes.
- Unable to track/show progress on model generations.

### version control
- “because all the outputs are saved within the notebook, there’s a lot of state that’s bundled in the file. 
  This makes it difficult to find out the acutal changes made in the notebook.
  
### Collaboration, sharing 
- To collaborate, all the users need to have the same environment setup and access to database.
- There are issues with extensions used in different users because of versions.
- reusing notebooks also causes issues because of dependency issues with the notebook.

## Design opportunities
 ### Code refarctoring
  - coding assistance such as auto complete, API support within the notebook env
 ### Production Deployment 
  - mitigating dependencies while deploying in the production servers
 ### History 
  - managing notebook execution order to easily understand the flow of the code cell executions
 ### Working with Big datasets.
 
 
# Teaching data science to non CS people.... by pratitioners 

[Paper Link](https://seankross.com/chi-2019/kross-guo-chi-2019.pdf)

### Methodolgy
- interview of 20 data scientists(practitioners).
- semi-structured.
- focused on material taught in their courses.
- student experiences and challenges faced.

### Interview about
- course content
- language used
- tecnological challenges faced
- overall settings 
- where do students struggle.

Collected data arranged into common themes by inductive analysis.

### Interview points
Practitioners vary from different diverse fields.(not from CS)
- no student feeback or their point of view.
- students took the courses for job needs rather than learning .
- most of them wanted to learn specific tools for their job requirement.

- "instructors emphasized workflows that centered on
the integration of code, data, and communication rather than
on the more algorithmic foundations of computing."

- instructors didnt teach basic programming concepts like
for loop , array , linked list, recursion or basic data structures.

-focused mainly on tabular dataframes and manipulating them with function calls (sorting, filtering , rearranging, addding columns)

-focused more time on data management skills .

- taught explanatory texts alongside running code for better understanding of data (using Jupyter)

- also taught github to organize projects/create portfolio 

### MAIN CHALLENGES FACED:
- Environment setup
- Uncertainty of not knowing everything
- finding appropriate dataset.

"How can we design better tools for teaching
data science?"


**********************************************************************************************


## Learning barriers for end user programming :
[paper link](https://faculty.washington.edu/ajko/papers/Ko2004LearningBarriers.pdf)

### TASK:
- 5 task given to non professional programmers, mostly included working with forms, fixing forms, make a clock, design an interface in VB 3.

### Points
- among the barriers, most of them were user barriers where users didnt know how to use the system and made false assumptions.
- some had problem understanding the error messages .

- the problems corresponds to form design in VB application.. will be different for other systems as they have different interface.














