# 2PMI

General description:
(1) "2PMIPreprocessing v2_4" is used for motion correction of the raw movie.
(2) "2PMISpikedetect v3_2" is used for data extraction. 
(3) ROIs are manually defined using Fiji software. 


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

