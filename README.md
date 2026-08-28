This repository contains the datasets and custom analysis scripts used in the study: "[Temporal-preparation-can-yield-benefits-that-are-independent-of-task-difficulty]" by Kimura et al.

It includes behavioral data (Reaction Times and Error Rates) and Event-Related Potential (ERP) data from two experiments (Experiment 1 and Experiment 2), as well as the R script used for calculating the Lateralized Readiness Potential (LRP) onset latencies.

◆Repository Structure

The repository is organized into three main folders. For detailed descriptions, data structures, and instructions, please refer to the specific README.md file located inside each folder.


1. Experiment_1
Contains the data for Experiment 1:

Behavioral Data: A workbook containing the master summary (mean RTs, % errors) and trial-by-trial logs for all four conditions (FP600/simple, FP600/complex, FP3000/simple, FP3000/complex) per subject.

ERP Data: Individual subject averaged waveforms formatted for time-series analysis.

2. Experiment_2
Contains the data for Experiment 2:

Behavioral Data: Reaction times, error rates, and trial-by-trial logs for Experiment 2.

ERP Data: Individual subject averaged waveforms for Experiment 2.

3. The regression line method
Contains the custom R script for estimating ERP/LRP onset latencies. The script utilizes an Optimized Segmented Regression Method to dynamically identify the most linear portion of the waveform slope and calculate the zero-crossing point.
(Includes instructions on how to set parameters for your own data.)
