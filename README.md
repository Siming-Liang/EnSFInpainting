# EnSF_Inpainting
Code repository for the paper:
ENSEMBLE SCORE FILTER WITH IMAGE INPAINTING FOR TRACKING SURFACE QUASI-GEOSTROPHIC DYNAMICS WITH PARTIAL OBSERVATION

## How to use
first run `sqg_nature_run.py` to generate nature run for 3hourly and 12 hourly data. This code and LETKF codes are originally from https://github.com/jswhit/sqgturb

Then run five Jupyter Notebook for 5 methods in the paper. You will need to chage input file names, number of observation and percentage of arctange observations. For LETKF, you need set the $L_h$ and RTPS based the result in our paper.
