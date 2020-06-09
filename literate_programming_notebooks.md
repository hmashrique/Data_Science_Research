
# Literate programming in notebooks :

## Discussion Points
 - Exploring the idea of notebook exploration through literate programming.
 -  Data scientists find it difficult to keep track of their work in notebooks.
 - #### " We wondered if literate programming helps data scientists retain the story of their in-progress exploration "
 - this paper presents study on " How data scientists explore ideas, work with notebooks and why they develop a narrative structure in a literate programming tool."
 - Interview consisted of open ended questions.
 - Questions involved **sharing with other people** , **the use of markdown cells and code comments** , **the size of code cells and notebooks**, and **version control**.   
 - The authors annotated the scripts from the interview by open coding from a sample of 6 scripts. From then, they used 
 the initial annotation, they used it on other scripts and updated the annotations as required. For example,
 " Codes continued to evolve,primarily in sub-topics, e.g., Annotating became Annotating with Markdown and Annotating with Code Comments. "

 **3 Use Cases found**
  - Preliminary “scratch pad” work. 
       - used for scratch work 
       - testing code syntax 
       - trying ideas
       - debug piece of code
  - Work that ends up extracted out of the notebook for use in a production pipeline.
    - finished code had to be extracted out of the notebook and placed in a plain-text code file for future use in production.
  - Work intended to be shared in different ways.
    - Almost all our participants (20 of 21) shared the results of the analysis in a notebook

 **Iteration Behavior**
  - Participants demonstrated different usage patterns.   
  - Another repeated theme about notebook organization was
adding new cells directly to where in the notebook the
original analysis took place .
 >“ if I have to iterate a part of it then obviously I tried to
do it close to the place where I inserted it previously, so
either in the cell above or below "
 - 6 participants used "expand then reduce" method while working with notebooks.

 **Narrative pattern of Notebooks**

- Linear pattern (keeps record of everything including mistakes, ideas,dead ends- *used my few* )
- Non Linear pattern (Keeping only the important parts as a curated document- *mostly used*)

  **Version Control**
  - 11 of 21 participants used Git as version control but found is unusable because utilities were not designed to treat metadata differently from source code.

  > " diffing is so hard...I develop until I'm happy and then I'm
going to put it in a file and then I'm going to version
control the file not the notebook."

**Problems faced during exploration && Future problems to solve**
 - d 





