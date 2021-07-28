# Matplotlib-challenge

Process and workflow of the analysis for this Project

1.	Extract the Data from the files “Mouse_metadata.csv” and “Study_results.csv”
2.	Do an inner merge on the column “Mouse ID” of both files and create a single Data Frame
3.	Remove the duplicated ID
4.	Create the summary Statistics of the whole data
    - Mean
    - Median
    - Variance
    - Standard deviation
    - Standard error of the mean
5.	As an example, it was chosen to do an analysis the mouse with the ID: s185 and the Drug Regimen Capomulin
6.	For this, it was created the following plots
    - Linear Plot of Tumor Volume (mm3) vs Timepoint
    - Scatter Plot of Tumor Volume vs Weight
![image](https://user-images.githubusercontent.com/49955534/127284647-4e172868-9258-4d64-a221-7ce421f85da1.png)


![Capomulin](images/boxPlot.png)

Generate a line plot of tumor volume vs. time point for a mouse treated with Capomulin
![Capmoulin](images/TumorVolume.png)

Tumor Volume (mm3) vs Timpoint Mouse ID: s185 Drug Regimen: Capomulin'

![Scatte Plot](images/scatter.png)

![Scatter Plot](images/scatterCorelation.png)
