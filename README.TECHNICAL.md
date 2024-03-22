# **Pharmaceutical Animal Study Analysis with Matplotlib**

----

### **Installation:**

----

If the computer has Anaconda, Jupyter Notebook, and a recent version of Python, the IPython notebook already has the following dependencies installed: datetime, io, json, matplotlib, numpy, pandas, pathlib, os, pandas, requests, requests_html, and scipy.

In addition to those modules, the Jupyter Notebook requires the following to execute: holoviews, hvplot, geoviews, geopy, aspose-words, dataframe-image.

Here are the requisite Terminal commands for the installation of these peripheral modules:

python3 -m pip install holoviews

python3 -m pip install hvplot

python3 -m pip install geoviews

python3 -m pip install geopy

python3 -m pip install aspose-words

python3 -m pip install dataframe-image

----

### **Usage:**

----

The IPython notebook, pymaceuticals.ipynb, uses the CSV files, mouse_study_data.csv and .csv, as input and will not run without them.  The interactive Python notebook must have the following Python scripts in the same folder with it:

error_handle_functions.py

log_constants.py

log_functions.py

log_subroutines.py

mathx_functions.py

matplotlibx_subroutines.py

pandas_process_functions.py

pymaceuticals_subroutines.py

If the folders, logs and images, are not present, the IPython notebook will create them.  The folder, resources, holds input files for the IPython Notebook; the folder, logs, contains log files from testing the IPython Notebook; and the folder, images, has the PNG image files of the IPython Notebook's tables and plots.

To place the IPython notebook in Log Mode or Image Mode set the parameter for the appropriate subroutine in coding cell #2 to True. If the program is in Log Mode , it writes that information to the log file. If the program is in Image Mode, it writes all DataFrames, hvplot maps, and matplotlib plots to PNG files in the Images Folder.

----

### **Resource Summary:**

----

#### Source code

pymaceuticals.ipynb, error_handle_functions.py, log_constants.py, log_functions.py, log_subroutines.py, mathx_functions.py, matplotlibx_subroutines.py, pandas_process_functions.py, pymaceuticals_subroutines.py

#### Input files

mouse_study_data.csv, mouse_study_results.csv

#### Output files

n/a

#### SQL script

n/a

#### Software

Jupyter Notebook, Matplotlib, Numpy, Pandas, Python 3.11.4

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

----

### **GitHub Repository Branches:**

----

#### main branch 

|&rarr; [./error_handle_functions.py](./error_handle_functions.py)

|&rarr; [./log_constants.py](./log_constants.py)

|&rarr; [./log_functions.py](./log_functions.py)

|&rarr; [./log_subroutines.py](./log_subroutines.py)

|&rarr; [./mathx_functions.py](./mathx_functions.py)

|&rarr; [./matplotlibx_subroutines.py](./matplotlibx_subroutines.py)

|&rarr; [./pandas_process_functions.py](./pandas_process_functions.py)

|&rarr; [./pymaceuticals_subroutines.py](./pymaceuticals_subroutines.py)

|&rarr; [./pymaceuticals.ipynb](./pymaceuticals.ipynb)

|&rarr; [./README.TECHNICAL.md](./README.TECHNICAL.md)

|&rarr; [./README.md](./README.md)

|&rarr; [./table_of_contents.md](./table_of_contents.md)

|&rarr; [./images/](./images/)

  &emsp; |&rarr; [./images/pymaceuticalsFigure421TumorVolumeLastbyDrugRegimenDistribution.png](./images/pymaceuticalsFigure421TumorVolumeLastbyDrugRegimenDistribution.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure521LastGreatestTimepointDistribution.png](./images/pymaceuticalsFigure521LastGreatestTimepointDistribution.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure611DrugRegimenbyNumberofDataPoints.png](./images/pymaceuticalsFigure611DrugRegimenbyNumberofDataPoints.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure641DrugTreatmentRegimenbyDataPointsPerMouse.png](./images/pymaceuticalsFigure641DrugTreatmentRegimenbyDataPointsPerMouse.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure741MouseWeightDistributionsforEachTreatmentGroup.png](./images/pymaceuticalsFigure741MouseWeightDistributionsforEachTreatmentGroup.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure820MalevsFemaleMouseDistributionAll.png](./images/pymaceuticalsFigure820MalevsFemaleMouseDistributionAll.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure821MalevsFemaleMouseDistributionCapomulin.png](./images/pymaceuticalsFigure821MalevsFemaleMouseDistributionCapomulin.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure822MalevsFemaleMouseDistributionCeftamin.png](./images/pymaceuticalsFigure822MalevsFemaleMouseDistributionCeftamin.png)

  &emsp; |&rarr; [./images/pymaceuticalsFigure823MalevsFemaleMouseDistributionInfubinol.png](./images/pymaceuticalsFigure823MalevsFemaleMouseDistributionInfubinol.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure824MalevsFemaleMouseDistributionKetapril.png](./images/pymaceuticalsFigure824MalevsFemaleMouseDistributionKetapril.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure825MalevsFemaleMouseDistributionNaftisol.png](./images/pymaceuticalsFigure825MalevsFemaleMouseDistributionNaftisol.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure826MalevsFemaleMouseDistributionPlacebo.png](./images/pymaceuticalsFigure826MalevsFemaleMouseDistributionPlacebo.png)

  &emsp; |&rarr; [./images/pymaceuticalsFigure827MalevsFemaleMouseDistributionPropriva.png](./images/pymaceuticalsFigure827MalevsFemaleMouseDistributionPropriva.png)
  
  &emsp; |&rarr; 
[./images/pymaceuticalsFigure828MalevsFemaleMouseDistributionRamicane.png](./images/pymaceuticalsFigure828MalevsFemaleMouseDistributionRamicane.png)

  &emsp; |&rarr; [./images/pymaceuticalsFigure829MalevsFemaleMouseDistributionStelasyn.png](./images/pymaceuticalsFigure829MalevsFemaleMouseDistributionStelasyn.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure7311TumorVolumesvsMouseWeightsPlotswithHighCorrelation.png](./images/pymaceuticalsFigure7311TumorVolumesvsMouseWeightsPlotswithHighCorrelation.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure8210MalevsFemaleMouseDistributionZoniferol.png](./images/pymaceuticalsFigure8210MalevsFemaleMouseDistributionZoniferol.png)
  
  &emsp; |&rarr; [./images/pymaceuticalsFigure8211MalevsFemaleMouseDistribution.png](./images/pymaceuticalsFigure8211MalevsFemaleMouseDistribution.png)
  
  &emsp; |&rarr; [./images/PymaceuticalsGraph351CapomulinTreatmentofMousel897.png](./images/PymaceuticalsGraph351CapomulinTreatmentofMousel897.png)
  
  &emsp; |&rarr; [./images/PymaceuticalsGraph351CapomulinTreatmentofMousem601.png](./images/PymaceuticalsGraph351CapomulinTreatmentofMousem601.png)
  
  &emsp; |&rarr; [./images/PymaceuticalsGraph352CeftaminTreatmentofMousew151.png](./images/PymaceuticalsGraph352CeftaminTreatmentofMousew151.png)
  
  &emsp; |&rarr; [./images/PymaceuticalsGraph353InfubinolTreatmentofMousea577.png](./images/PymaceuticalsGraph353InfubinolTreatmentofMousea577.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph353InfubinolTreatmentofMousec139.png](./images/PymaceuticalsGraph353InfubinolTreatmentofMousec139.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph354KetaprilTreatmentofMousep189.png](./images/PymaceuticalsGraph354KetaprilTreatmentofMousep189.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph354KetaprilTreatmentofMouseu327.png](./images/PymaceuticalsGraph354KetaprilTreatmentofMouseu327.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph355NaftisolTreatmentofMouser701.png](./images/PymaceuticalsGraph355NaftisolTreatmentofMouser701.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph355NaftisolTreatmentofMousey601.png](./images/PymaceuticalsGraph355NaftisolTreatmentofMousey601.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph356PlaceboTreatmentofMouses152.png](./images/PymaceuticalsGraph356PlaceboTreatmentofMouses152.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph356PlaceboTreatmentofMousey478.png](./images/PymaceuticalsGraph356PlaceboTreatmentofMousey478.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph357ProprivaTreatmentofMousei635.png](./images/PymaceuticalsGraph357ProprivaTreatmentofMousei635.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph357ProprivaTreatmentofMouses187.png](./images/PymaceuticalsGraph357ProprivaTreatmentofMouses187.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph358RamicaneTreatmentofMousej989.png](./images/PymaceuticalsGraph358RamicaneTreatmentofMousej989.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph358RamicaneTreatmentofMouses508.png](./images/PymaceuticalsGraph358RamicaneTreatmentofMouses508.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph359StelasynTreatmentofMousek862.png](./images/PymaceuticalsGraph359StelasynTreatmentofMousek862.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph359StelasynTreatmentofMouses565.png](./images/PymaceuticalsGraph359StelasynTreatmentofMouses565.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph731TumorVolumesvsMouseWeightsWithRegressionCapomulin.png](./images/PymaceuticalsGraph731TumorVolumesvsMouseWeightsWithRegressionCapomulin.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph732TumorVolumesvsMouseWeightsWithRegressionCeftamin.png](./images/PymaceuticalsGraph732TumorVolumesvsMouseWeightsWithRegressionCeftamin.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph733TumorVolumesvsMouseWeightsWithRegressionInfubinol.png](./images/PymaceuticalsGraph733TumorVolumesvsMouseWeightsWithRegressionInfubinol.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph734TumorVolumesvsMouseWeightsWithRegressionKetapril.png](./images/PymaceuticalsGraph734TumorVolumesvsMouseWeightsWithRegressionKetapril.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph735TumorVolumesvsMouseWeightsWithRegressionNaftisol.png](./images/PymaceuticalsGraph735TumorVolumesvsMouseWeightsWithRegressionNaftisol.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph736TumorVolumesvsMouseWeightsWithRegressionPlacebo.png](./images/PymaceuticalsGraph736TumorVolumesvsMouseWeightsWithRegressionPlacebo.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph737TumorVolumesvsMouseWeightsWithRegressionPropriva.png](./images/PymaceuticalsGraph737TumorVolumesvsMouseWeightsWithRegressionPropriva.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph738TumorVolumesvsMouseWeightsWithRegressionRamicane.png](./images/PymaceuticalsGraph738TumorVolumesvsMouseWeightsWithRegressionRamicane.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph739TumorVolumesvsMouseWeightsWithRegressionStelasyn.png](./images/PymaceuticalsGraph739TumorVolumesvsMouseWeightsWithRegressionStelasyn.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph3510ZoniferolTreatmentofMousea401.png](./images/PymaceuticalsGraph3510ZoniferolTreatmentofMousea401.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph3510ZoniferolTreatmentofMouseq633.png](./images/PymaceuticalsGraph3510ZoniferolTreatmentofMouseq633.png)

  &emsp; |&rarr; [./images/PymaceuticalsGraph7310TumorVolumesvsMouseWeightsWithRegressionZoniferol.png](./images/PymaceuticalsGraph7310TumorVolumesvsMouseWeightsWithRegressionZoniferol.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable111CompleteMedicalStudyDataFrame.png](./images/PymaceuticalsTable111CompleteMedicalStudyDataFrame.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable121MouseIDswithDuplicateTimepoints.png](./images/PymaceuticalsTable121MouseIDswithDuplicateTimepoints.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable122AllMouseIDswithDuplicateTimepointsRecords.png](./images/PymaceuticalsTable122AllMouseIDswithDuplicateTimepointsRecords.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable221SummaryStatisticsTumorVolume.png](./images/PymaceuticalsTable221SummaryStatisticsTumorVolume.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable421TumorVolumeStatisticsforCAPOMULIN.png](./images/PymaceuticalsTable421TumorVolumeStatisticsforCAPOMULIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable422TumorVolumeStatisticsforCEFTAMIN.png](./images/PymaceuticalsTable422TumorVolumeStatisticsforCEFTAMIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable423TumorVolumeStatisticsforINFUBINOL.png](./images/PymaceuticalsTable423TumorVolumeStatisticsforINFUBINOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable424TumorVolumeStatisticsforKETAPRIL.png](./images/PymaceuticalsTable424TumorVolumeStatisticsforKETAPRIL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable425TumorVolumeStatisticsforNAFTISOL.png](./images/PymaceuticalsTable425TumorVolumeStatisticsforNAFTISOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable426TumorVolumeStatisticsforPLACEBO.png](./images/PymaceuticalsTable426TumorVolumeStatisticsforPLACEBO.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable427TumorVolumeStatisticsforPROPRIVA.png](./images/PymaceuticalsTable427TumorVolumeStatisticsforPROPRIVA.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable428TumorVolumeStatisticsforRAMICANE.png](./images/PymaceuticalsTable428TumorVolumeStatisticsforRAMICANE.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable429TumorVolumeStatisticsforSTELASYN.png](./images/PymaceuticalsTable429TumorVolumeStatisticsforSTELASYN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable521LastGreatestTimepointStatisticsforCAPOMULIN.png](./images/PymaceuticalsTable521LastGreatestTimepointStatisticsforCAPOMULIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable522LastGreatestTimepointStatisticsforCEFTAMIN.png](./images/PymaceuticalsTable522LastGreatestTimepointStatisticsforCEFTAMIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable523LastGreatestTimepointStatisticsforINFUBINOL.png](./images/PymaceuticalsTable523LastGreatestTimepointStatisticsforINFUBINOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable524LastGreatestTimepointStatisticsforKETAPRIL.png](./images/PymaceuticalsTable524LastGreatestTimepointStatisticsforKETAPRIL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable525LastGreatestTimepointStatisticsforNAFTISOL.png](./images/PymaceuticalsTable525LastGreatestTimepointStatisticsforNAFTISOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable526LastGreatestTimepointStatisticsforPLACEBO.png](./images/PymaceuticalsTable526LastGreatestTimepointStatisticsforPLACEBO.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable527LastGreatestTimepointStatisticsforPROPRIVA.png](./images/PymaceuticalsTable527LastGreatestTimepointStatisticsforPROPRIVA.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable528LastGreatestTimepointStatisticsforRAMICANE.png](./images/PymaceuticalsTable528LastGreatestTimepointStatisticsforRAMICANE.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable529LastGreatestTimepointStatisticsforSTELASYN.png](./images/PymaceuticalsTable529LastGreatestTimepointStatisticsforSTELASYN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable621InfubinolStatisticalOutlier.png](./images/PymaceuticalsTable621InfubinolStatisticalOutlier.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable622StatisticalOutlierMouseRecords.png](./images/PymaceuticalsTable622StatisticalOutlierMouseRecords.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable641MouseIDbyNumberofDataPoints.png](./images/PymaceuticalsTable641MouseIDbyNumberofDataPoints.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable642DrugTreatmentRegimenbyDataPointCategoryNumberofMice.png](./images/PymaceuticalsTable642DrugTreatmentRegimenbyDataPointCategoryNumberofMice.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable740MouseIDbyDrugRegimenandWeight.png](./images/PymaceuticalsTable740MouseIDbyDrugRegimenandWeight.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable741MouseWeightStatisticsforCAPOMULIN.png](./images/PymaceuticalsTable741MouseWeightStatisticsforCAPOMULIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable742MouseWeightStatisticsforCEFTAMIN.png](./images/PymaceuticalsTable742MouseWeightStatisticsforCEFTAMIN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable743MouseWeightStatisticsforINFUBINOL.png](./images/PymaceuticalsTable743MouseWeightStatisticsforINFUBINOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable744MouseWeightStatisticsforKETAPRIL.png](./images/PymaceuticalsTable744MouseWeightStatisticsforKETAPRIL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable745MouseWeightStatisticsforNAFTISOL.png](./images/PymaceuticalsTable745MouseWeightStatisticsforNAFTISOL.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable746MouseWeightStatisticsforPLACEBO.png](./images/PymaceuticalsTable746MouseWeightStatisticsforPLACEBO.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable747MouseWeightStatisticsforPROPRIVA.png](./images/PymaceuticalsTable747MouseWeightStatisticsforPROPRIVA.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable748MouseWeightStatisticsforRAMICANE.png](./images/PymaceuticalsTable748MouseWeightStatisticsforRAMICANE.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable749MouseWeightStatisticsforSTELASYN.png](./images/PymaceuticalsTable749MouseWeightStatisticsforSTELASYN.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable811MouseGenderCountDistributionbyDrugRegimen.png](./images/PymaceuticalsTable811MouseGenderCountDistributionbyDrugRegimen.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable812MouseGenderPercentDistributionbyDrugRegimen.png](./images/PymaceuticalsTable812MouseGenderPercentDistributionbyDrugRegimen.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable4210TumorVolumeStatisticsforZoniferol.png](./images/PymaceuticalsTable4210TumorVolumeStatisticsforZoniferol.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable5210LastGreatestTimepointStatisticsforZoniferol.png](./images/PymaceuticalsTable5210LastGreatestTimepointStatisticsforZoniferol.png)

  &emsp; |&rarr; [./images/PymaceuticalsTable7410MouseWeightStatisticsforZoniferol.png](./images/PymaceuticalsTable7410MouseWeightStatisticsforZoniferol.png)

  &emsp; |&rarr; [./images/README.md](./images/README.md)

|&rarr; [./logs/](./logs/)

  &emsp; |&rarr; [./logs/20240321pymaceuticals_log.txt](./logs/20231107PymaceuticalsDebug.txt)

  &emsp; |&rarr; [./logs/README.md](./logs/README.md)

|&rarr; [./resources/](./resources/)

  &emsp; |&rarr; [./resources/mouse_study_data.csv](./resources/mouse_study_data.csv)

  &emsp; |&rarr; [./resources/mouse_study_results.csv](./resources/mouse_study_results.csv)

  &emsp; |&rarr; [./resources/README.md](./resources/README.md)

----

### **References:**

----

[Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)

[Matplotlib Documentation](https://matplotlib.org/stable/index.html)

[Numpy documentation](https://numpy.org/doc/1.26/)

[Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)

[Python Documentation](https://docs.python.org/3/contents.html)

----

### **Authors and Acknowledgment:**

----

### Copyright

Nicholas J. George © 2023. All Rights Reserved.
