# 2PMI

General description:
(1) "2PMIPreprocessing v2_4" is used for motion correction of the raw movie.
(2) "2PMISpikedetect v3_2" is used for data extraction. 
(3) In the folder of "example data", raw movie and processed movie after motion correction are both provided. ROIs are manually defined using Fiji software. In the folder of extracted data, we use the excel file "spike number of roi" for statistic analysis and the folder named "Trace" are the pictures showing all the calcium traces with labels showing detected SSCS.


For using '2PMIPreprocessing v2_4':
1. Please use MATLAB (after version 2016b).
2. Please use main.m to run the code.
3. Preferences.m for setting parameters. Please adjust the defaults to achieve better performance for different data. Current version is used for our example data.
4. Only single channel .tiff (8 or 16 bit) data are supported.
5. DON'T include '.' (dot) in the file path.
6. Please DON'T use these functions: BM3D, Enhancing when test the code.


For using '2PMISpikedetect v3_2':
1. Please use MATLAB (after version 2016b).
2. Please use main.m to run the code.
3. Preferences.m for setting parameters. Please adjust the defaults to achieve better performance for different data.
4. Only single channel .tiff (8 or 16 bit) data are supported.
5. DON'T include '.' (dot) in the file path.
6. Please DON'T use these functions: B ROI Subtraction, Prediction, Data Annotation, Single ROI Data.
7. Please use the form named "spike number of roi.xls" for results of automatic detection of SSCS (spontaneous somatic calcium signal).
8. The example movie provided is 2.15 min long (0.129 second * 1000 frames).

