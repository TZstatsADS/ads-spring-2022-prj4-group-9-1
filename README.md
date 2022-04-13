# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2022

+ Team 9
+ Project title: Machine Learning Fairness Algorithms Evaluation
+ Team members
	+ Clement, Micol mc5104@columbia.edu
	+ Naik, Vaishak vvn2107@columbia.edu
	+ Shi, Yinan ys3387@columbia.edu
	+ Zha, Yvonne lz2806@columbia.edu
	+ Zhang, Ran rz2568@columbia.edu
+ Project summary: In this project, we implemented, evaluated and compared algorithms for Machine Learning Fairness. Our study compared two different algorithms, Learning Classification without Disparate Mistreatment (DM and DM-sen) and Information Theoretic Measures for Fairness-aware Feature selection (FFS). Implementation and evaluation was based on the COMPAS dataset, which contains the criminal history, jail and prison time, demographics, and COMPAS risk scores for defendants from Broward County from 2013 and 2014. Our goal is to compare the performance and efficiency of the above algorithms.
	
**Contribution statement**:  
+ Micol Clement - Analized and implemented DM and DM-sen, wrote the initial code of DM and DM-sen.
+ Vaishak Naik - Presenter. Analysis of FFS algorithm, implementation of FFS, result analysis and comparison of two algorithms, matrix visualization and added to FFS contents in the presentation file.
+ Yinan Shi - Calibration Calculation; Confusion Matrix Visualization (not used for the final analysis); Implementation of FFS; Some adjustments in feature preprocessing in FFS algorithm; Code proofreading. 
+ Yvonne Zha - Implemented algorithm DM based on DM-sen and calculation of metrics DFPR, DFNR, calibration; Added experiments on different constraints; Made the slides on DM, DM-sen and results comparison.
+ Ran Zhang - Implemented FFS algorithm, wrote the initial version of FFS algorithm; Edited readme file, uploaded and organized files in GitHub repo; Edited description in the presentation file.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```
**Note**: The DM.ipynb is the final version of DM and DM-sen, and the ITFFS.ipynb is the final version of FFS.

Please see each subfolder for a README file.
