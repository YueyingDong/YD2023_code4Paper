# YD2023_code4Paper
code to Oculomotor working memory signals are flexible to behavioral priority and subjective imagery strength by Yueying Dong & Anastasia Kiyonaga

-------------------------processing-------------------------------

readEL: readin and transform the eyelink file into trial x time structure, ready it for subsequent processing. (note: this code runs on the raw data, which is not included in this repo.)

cleanELPup: preprocess the pupil data; remove outliers (e.g. due to blinks), interpolate missing data; subject rejection.
cleanELSacc: preprocess the gaze data using the blink mask generated from cleanELPup; extract saccade from gaze; 

> after processing, results is saved under /data4Paper
> for accessing the processing the data, please visit our OSF repository, data should be unziped under /data4paper folder.
> link to OSF repository: https://osf.io/qyv5z/?view_only=f52d68da115342c1af4bd72dea119a8c

-------------------------results-------------------------------

pupResults: the main results for the pupil analysis; plots and stats;
saccResults: the main results for the gaze/saccade; plots and stats;
