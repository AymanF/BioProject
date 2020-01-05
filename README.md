Lou Gendron, Ayman Fattar  M2-SE 

1.	Brain Lower Grade Glioma

Low-grade gliomas are brain tumors that originate from glial cells, which support and nourish neurons in the brain. Glial tumors, or gliomas, are divided into four grades, depending on their cells' appearance under a microscope. Grade 1 and 2 gliomas are considered low-grade and account for about two-thirds of all pediatric tumors.
In addition to their grade, low-grade gliomas are also classified based on their location and by the kind of glial cell from which they arise.
For our study we have chosen to work on:
•	Brain Lower Grade Glioma (TCGA, PanCancer Atlas)
•	Brain Lower Grade Glioma (TCGA, Provisional) 

We can see over the CbioPortal that the 4 most mutated genes are the same for the two cases.

2.	Anaconda and Jupiter Notebook

a.	Anaconda

      Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing. Package versions are managed by the package management system conda.

b.	Jupyter Notebook

The Jupyter Notebook is an open-source web application that allows users to create and share documents that contain live code, equations, visualizations and narrative text. It is mostly used for data cleaning and transformation, numerical simulation, statistical modelling, data visualization, machine learning.


3.	Libraries

For this project we have used two python libraries:
 
a.	Pandas

Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

It offers data structures and operations for manipulating numerical tables and time series. We use it in our project to read our files containing data whether their format is txt or tsv, stock the data in DataFrames to later use it.

Example:

 

Above, we see an example of the usage of Pandas, in a variable, stock the content of our data files. We can specify the separator, if the file is not a csv, in our case “\t” because we are reading tsv files here (Tabulation-separated values).

b.	Matplotlib and pyplot

Matplotlib is a plotting library for Python and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits.
Matplotlib.pyplot is a collection of command style functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels and more.

Example:
 
	In the two first line we choose what column of the data we want to stock in a variable we will use in our plot as the axis, therefore the data that will be displayed.

This is how the first two commands are formed:
		Variable = Data[‘Column’]

	The two next line let us decide of the label that we will be displaying on each axis.
	Finally, we the “scatter” function to determine the type of the plot. We specify both variables that contains the data we want to use.
 

4.	Results and analysis

Code can be found here: https://github.com/AymanF/BioProject
Can be opened with Jupyter Notebook
a.	Comparison of ' Mutation Count vs Fraction of Genome Altered '

On the left, Brain Lower Grade Glioma (TCGA, PanCancer Atlas)
On the right, Brain Lower Grade Glioma (TCGA, Provisional) 
 

 
b.	Comparison of Deletion and Amplification Genes

 

We can see that the 4 genes above are the same for both cases of Brain Cancer. They are present nearly over 20% and expand to more than 70% of the cases. Also, they are all marked as Cancerous Genes.

c.	Comparison of mutated genes in the RNA

 
Above, the comparison of mutated genes in the RNA

We can see that the Provisional Dataset got much more Amplification and Deletion for the analysed genes

As we can see for Amplifications the Atlas Dataset got 55822 against 78670 for the Provisional Dataset. About the Deletions the Atlas Dataset got 37498 against 66232 for the Provisional Dataset

 
d.	Analysis of Tumor Sites for ' Brain Lower Grade Glioma (TCGA, Provisional) '
No data available for ' Brain Lower Grade Glioma (TCGA, PanCancer Atlas) '
 

The pie above show us the different sites where Brain Lower Grade Glioma where found for the Provisional dataset.

We can see in pink that over 50% of the cancer mentioned above are in the Supratentorial, Temporal Lobe. The brown section that nearly 30% are in the Supratentorial, Parietal Lobe. The Supratentorial Occipital Lobe represent 9% of the case of Brain lower Grade Glioma.

Finally, the four other tumors sites represent between 0.2 and 1.4 percent each, located in:

•	Posterior Fossa, Brain Stem
•	Posterior Fossa, Cerebellum
•	Supratentorial, Frontal Lobe
•	Supratentorial, Not Otherwise Specified

e.	Overall survival

We couldn’t achieve this part due to the complexity we found in using the given data to reproduce the plot that was displayed on the CbioPortal.
You can still find, on our Jupyter Notebook platform, what we tried to do to understand the data and try to work something out.

 
5.	Sources

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3983820/
https://www.cbioportal.org/
https://www.stackoverflow.com/
https://www.pandas.pydata.org/
https://www.matplotlib.org/
https://www.mathworks.com/

