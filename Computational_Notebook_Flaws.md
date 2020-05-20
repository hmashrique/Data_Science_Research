
**Whats wrong with Computational Notebooks (Austin's Paper)**

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

### version control
- “because all the outputs are saved within the notebook, there’s a lot of state that’s bundled in the file. 
  This makes it difficult to find out the acutal changes made in the notebook.
  
### Collaboration, sharing 
- To collaborate, all the users need to have the same environment setup and access to database.
- There are issues with extensions used in different users because of versions.
- reusing notebooks also causes issues because of dependency issues with the notebook.


