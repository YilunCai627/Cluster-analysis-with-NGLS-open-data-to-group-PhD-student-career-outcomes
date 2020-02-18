# Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes
## Background
We'll work with NGLS open data to group the career outcomes of PhD students in the Life Sciences Programs of Duke University. The result of cluster analysis might be helpful for academic institutions and prospective PhD students.  
## Data Analytics Outline  
### **1. Research Questions**  
Is it possible to bring transparency to empower academic institutions to make better decisions about their PhD training programs? How can we group the open career outcomes data in order to inform perspective or current PhD students with a brighter future and broader opportunities? What policy or regulations can be designed to build a bridge between PhD students and an efficient job market?
### **2. Data Questions**
In this study, we explore the publishing career outcomes data of life science PhD training programs in Duke Uinversity. More specifically, we attempt to group the collecting data and analyze the potential characteristics of each category so as to provide some constructive suggestions for strengthening the biomedical workforce.  

![](https://github.com/YilunCai627/Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes/raw/master/cluster%20analysis_images/original%20data.png)

With comprehensive long-term career pathways information, programs could more effectively assess their own contribution to the profession. What is the comprehensive and recent picture of the career outcomes? Do the career outcomes of PhD students differ by cluster/discipline? Besides, how can perspective PhD students more fully understand his/her responding to the needs of the job market?  
### **3. K-means Clustering and Evaluation Metric**  
Cluster analysis can help us better understand natural groupings in our datasets based on defined variables. By allocating different data points into several clusters, it is possible to reveal the underlying relationship and characterize each group using certain matrics.  

Distance metrics plays a very important role in the clustering process. The more the similarity among the data in clusters, more the chances of particular data-items to belong to particular group. In general, [K-means](https://towardsdatascience.com/k-means-clustering-algorithm-applications-evaluation-methods-and-drawbacks-aa03e644b48a) is a heuristic algorithm that partitions a data set into K clusters by minimizing the sum of squared distance (SSE) in each cluster. 
### **4. Data Answers**  
We apply Excel Solver operations for a cluster anaysis on the career outcomes by sector of Life Science PhD Programs in Duke University. The minimization of the sum of squared distance is compared between the initial centroids and the final solved cluster centroids. We can further analyze the characteristics of each cluster according to the z-scores.
![](https://github.com/YilunCai627/Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes/raw/master/cluster%20analysis_images/comparison%20between%20different%20clusters.png)  

The table below display the specific grouping results of the PhD programs in Duke University. We can see that the number of programs in each cluster is similar, which indicates that it is reasonable to assign three group for these programs.

![](https://github.com/YilunCai627/Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes/raw/master/cluster%20analysis_images/solved%20clusters.png)


### **5. Research Answers**
Here we present the statistics of the final three clusters and list the corresponding programs within each group. Through this chart, the similarities and differences between each cluster is relatively apparent:

* In each cluster, most of PhD students pursue their career in academia sector after graduation, which is in line with our expectation.
* Programs fall into cluster 1 have a larger population, which suggest the employment pressure might be relatively lower in this category.
* Government departments should strengthen employment promotion to attract more current PhD students for specific job positions.
* The Job market is supposed to provide clearer pathways for PhD students into a diversity of careers.
* It might be necessary for the society to decrease the sense of isolation that PhD students sometimes report when considering a career beyond the academy.
* To guarantee a brighter future, prospective PhD students should take the career outcomes in each cluster into consideration before they choose a certain program.  
  
![](https://github.com/YilunCai627/Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes/raw/master/cluster%20analysis_images/Cluster%20Analysis%20Result%20Summary.png)

In conclusion, not only would academic institutions better understand the impacts of PhD programs on their students’ career trajectories, but students themselves, benefiting from improved programs and comprehensive information, would be better prepared for the full range of professions they enter in different sectors. 

## Data Manipulation Instructions
The original data were exported from the [NGLS Coalition](https://nglscoalition.org/coalition-data/#close) as [PDF documents](https://gradschool.duke.edu/about/statistics/statistics-coalition-next-generation-life-science), and the processed version Excel document in this repository is integrated using [Tabula](https://tabula.technology).  

Want to learn more details about data manipulation in Excel to clean complex dataset and conduct linear regression analysis? Click [***here***](https://github.com/YilunCai627/Cluster-analysis-with-NGLS-open-data-to-group-PhD-student-career-outcomes/blob/master/Data%20Manipulation%20Instructions.md) for a simple step-by-step instructions!  

## Data Sources
* [Next Generation Life Science (NGLS) Coalition](https://nglscoalition.org/coalition-data/)
* [Career outcomes data of Phd programs provided from Duke University](https://gradschool.duke.edu/about/statistics/statistics-coalition-next-generation-life-science)
* [Tabula](https://tabula.technology)