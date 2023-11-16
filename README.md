# YD2023_code4Paper
code to Oculomotor working memory signals are flexible to behavioral priority and subjective imagery strength by Yueying Dong & Anastasia Kiyonaga

-------------------------processing-------------------------------
readEL: readin and transform the eyelink file into trial x time structure, ready it for subsequent processing. 
cleanELPup: preprocess the pupil data; remove outliers (e.g. due to blinks), interpolate missing data; subject rejection.
cleanELSacc: preprocess the gaze data using the blink mask generated from cleanELPup; extract saccade from gaze; 

> after processing, results is saved under /data4Paper

-------------------------results-------------------------------
pupResults: the main results for the pupil analysis; plots and stats;
saccResults: the main results for the gaze/saccade; plots and stats;
