# CCF Research Project
This is the repository for code related to my undergraduate research thesis at John Carroll University.  It represents about three months of work during the summer of 2016.  As my first brush with data science, machine learning, and computer science in general, the code is near and dear, a bit naive, and rough around the edges.  However, the results are a legitimate improvement to the state of the art in blood test classification and a testament to the open and accessible nature of the data science community at large.

### The project
After meeting with Dr. Edmunds Reineks at the Pathology and Laboratory Medicine Institute at the Cleveland Clinic, we decided to apply machine learning to their blood testing data.  Classification of contaminated blood tests is done rather archaically, with rule-based methods the norm in major laboratories worldwide.  We received a small dataset to begin work with, and while the data progressively got larger, the core ideas behind the project remained simple: 
* Limit ourselves to the standard metabolic panel (Blood Urea Nitrogen, Calcium, Carbon Dioxide, Chloride, Creatinine, Glucose, Potassium, Sodium),
* Survey a variety of classifiers (both linear and nonlinear), and
* Use lightweight, agile tools that could be learned and automated quickly by a variety of professionals.

### The tools
* R for initial data cleaning and algorithm prototyping
* Hadoop when we decided to go 'Big Data'
* AWS and Python's scikit-learn for Kernel Density Estimation to get us to 'Big Data'
* Spark ML when we decided to go with the all-in-one library for user simplicity

### The results
We are currently writing two papers associated with this research project; one for a clinical audience and one for the data miners.  I'll update with major findings and a link to the papers themselves.