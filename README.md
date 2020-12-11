# Network-Traffic-Analysis
Basic Network Traffic Analysis using K-Means and PCA algorithms. 

## Part 1 
In this part, I have used a dataset to perform pay-load based and port-based analysis. The dataset has 22 columns with details regarding the destination id, source id, port, byte size, among other necessary inofrmation.  
The dataset used in this notebook can be found [here](http://www.secrepo.com/Security-Data-Analysis/Lab_1/conn.log.zip).

## Part 2
This part involves K-Means and PCA Analysis of the datasets that can be found [here](https://github.com/sooshie/Security-Data-Analysis/tree/master/Lab_4).  
I have also used the VirusTotal API that provides us with a list of antivirus softwares that have detected each of the hosts in the 'host_detections.csv' dataset. 
In K-Means, we are primarily just clustering the different domains into 2 categories - malicious and non-malicious. Once we perform the clustering, I have visualised these clusters by reducing the number of dimensions to 3, 2, and 1 respectively using PCA.  
Finally, after scaling the values, we can see that the malicious domains, or rather, the domains that have a high detection count, have a scaled value closer to 1, while the domains that have a detection count as low as 1 have a value close to  10<sup>-14</sup>.

## Requirements 
* Jupyter Notebook/ IPython
* Pandas 
* NumPy
* Matplotlib/Pylab
* Scipy
* Scikit Learn
