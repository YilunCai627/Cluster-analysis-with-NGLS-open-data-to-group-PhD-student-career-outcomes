# Data Manipulation
## Extract Tables from PDFs using Tabula
Open data from the Next Generation Life Science provided to us in PDFs, which has no easy way to extract by copy-and-paste. [Tabula](https://tabula.technology) is a simple, easy-to-use interface that allows researchers to extract those data into a CSV or Microsoft Excel spreadsheet.
### How to use Tabula?
* Download & Install the version of for your operating system.
* Upload PDF files containing a data table in your web browser.
* Select the table by dragging to draw a box around the area of interest.
* Click "Preview & Export Extracted Data" and adjust your selection until it looks right.
* Click the "Export" button and work with your data as a spreadsheet.
## Data Cleaning
Even though we have used Tabula to extract that original data provided into an Excel document, there are inevitably some data format error needs to be reorganized. Here we use "Text to Columns" in Excel to complete this text. Please click [***here***](https://support.office.com/en-us/article/Split-text-into-different-columns-with-the-Convert-Text-to-Columns-Wizard-30B14928-5550-41F5-97CA-7A3E9C363ED7) for detailed steps.
## Cluster Analysis
Below is a step-by-step description of k-means cluster analysis in Excel, you can also watch this [*vedio tutorial*](https://www.youtube.com/watch?v=Yn3VV9emiCs) in youtube for clearer explanation.
1. Use **AVERAGE** and **STDEV** functions to compute the mean and standard deviation.
2. Use **STANDARDIZE** function to compute z-scores of variables in your database.
3. Choose the number of clusters k and make an initial selection of k centroids randomly.
4. Use **VLOOKUP** function to match the information of the initial k centroids and make a subtable in your workbook.
5. Use **SUMXMY2** function to compute the distance of each data element to the initial centroids.
6. Make a new assignment of data elements to the k clusters based on the minimum distance to each of the cluster nodes.
7. The K-means clustering process can be viewed as an optimization process where the objective is to minimize the sum of the squared error (SSE). We can apply Excel [**Solver**](http://web.mit.edu/15.053/www/Excel_Solver.pdf) operation to complete this iterative process conveniently.
8. Identify what these clusters mean for your study: analyze z-scores, mean and other metrics within each cluster; compare the similarities and differences of different clusters.