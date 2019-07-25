# PLS0001

Welcome! As part of our recruitment process we invite candidates to
complete the task below and send us a pull request when done.

We look forward to reviewing your submission.

### Situation

Every two months we are given a text file from our accounting department
detailing all the loans given out on our networks.

This needs to be a validated against our internal systems by the tuple
of (Network, Product, Month).


### Task

Given the below CSV (also `./input.csv`) from our accounting department
calculate the aggregate loans by the tuple of (Network, Product, Month)
with amounts and counts.

The output should be saved into a CSV file named **Output.csv**.


|MSISDN     |Network    |Date         |Product         |Amount |
|-----------|-----------|-------------|----------------|-------|
|27729554427324|'Network 1'|'12-Mar-2016'|'Loan Product 1'|1000.00|
|27722342551343|'Network 2'|'16-Mar-2016'|'Loan Product 1'|1122.00|
|27725544272422|'Network 3'|'17-Mar-2016'|'Loan Product 2'|2084.00|
|27725326345543|'Network 1'|'18-Mar-2016'|'Loan Product 2'|3098.00|
|27729234533453|'Network 2'|'01-Apr-2016'|'Loan Product 1'|5671.00|
|27723453455453|'Network 3'|'12-Apr-2016'|'Loan Product 3'|1928.00|
|27725678534423|'Network 2'|'15-Apr-2016'|'Loan Product 3'|1747.00|
|27729554427286|'Network 1'|'16-Apr-2016'|'Loan Product 2'|1801.00|


### Solution considerations
1. The expectation is a file called **Output.csv** with a line
   for each tuple aggregating the amount and count of loans by tuple.

2. A **readme.txt** detailing the project, usage and assumptions you’ve made
   as well as the choices around your language, plugins and 3rd party libraries.

   It should also include performance, scaling and quality considerations.

3. Follow proper coding conventions, object orientated design.
4. Implement this as you would in a production environment.


### Submission guidelines

Use any of the following methods in submitting the solution

**Git Repository (preferred)**

1. Create a public git repository that will contain your solution.

2. Create a git branch with the name *PLS0001* and commit all your work in it.

3. Include all source code and instructions in the git branch so that we are able to
   build, package, and run your application.

4. Create a pull request for merging *PLS0001* to *master* branch.
   Then send us the pull request.


**File Storage**

1. Save your solution with any file storage service providers such as
Google Drive, AWS S3, Dropbox, e.t.c

2. Send us the link to the solution. Ensure the solution can be accessed publicly.

**Jupyter Notebook**

1. Create a Jupyter notebook with your solution and send us the link to the notebook.
Ensure this notebook is publicly accessible.


### Implementation notes
1. We want to encourage creativity in this technical assignment,
   however we also want to understand your coding style and skills.

   To that end we will not review submissions that utilise
   SQL, aggregate libraries, or similar functions built into languages.

2. Language functions include any method such as a ‘groupBy’.

3. Aggregate libraries include:
    - Python: Pandas
    - Java: jAgg
    - .NET: LINQ