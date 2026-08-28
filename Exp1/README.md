This repository contains the behavioral dataset (Reaction Time and Error Rates) and the preprocessed Event-Related Potential (ERP) dataset used in the study: "Kimura et al., Exp2".

◆Behavioral Dataset

The data is provided as a single Excel workbook. The experiment involved a manipulation with four distinct conditions: FP600/simple, FP600/complex, FP3000/simple, and FP3000/complex. The workbook contains a master summary sheet followed by individual trial-by-trial log sheets for each subject.

●Sheet 1: Summary

The first sheet provides a subject-level summary across all conditions. It includes:

・Mean Reaction Time (RT)

・Percentage of Errors (% Error)

・Outlier trial counts (responses < 200 ms or > 800 ms)

●Sheets 2 and Onwards: Individual Subject Logs

From the second sheet onwards, each sheet corresponds to a single subject and contains their trial-by-trial log data.

To organize the four experimental conditions within a single subject's sheet, the data is arranged horizontally into four 5-column blocks:

・Columns A–E: FP600/easy

・Columns F–J: FP600/hard

・Columns K–O: FP3000/easy

・Columns P–T: FP3000/hard

●Column Layout (Within Each 5-Column Block)

For every condition block (e.g., Columns A–E), the 5 columns represent the following trial-level information:

・1st Column (e.g., A, F, K, P): Trial Number (1 to 128)

・2nd Column (e.g., B, G, L, Q): Reaction Time in milliseconds (RT)

・3rd Column (e.g., C, H, M, R): Response Hand executed by the participant (2 = Left hand, 4 = Right hand)

・4th Column (e.g., D, I, N, S): Stimulus presented (3 = Left, 2 = Right)

・5th Column (e.g., E, J, O, T): Error Indicator (Contains an Excel function that evaluates whether the trial was an error based on the stimulus and response)

◆ERP dataset The data is provided as a single Excel workbook containing the averaged waveforms for each subject. The experiment involved a manipulation with four distinct conditions, which are separated into four individual sheets within the workbook.

Important Note Regarding the Jackknife Analysis
In the published manuscript, the statistical analysis for LRP and N1 interval were conducted using the "jackknife-based method" (e.g., Miller et al., 1998). However, please note that the dataset provided in this repository contains the "individual subject averaged waveforms", not the jackknifed waveforms.

●Sheets (Experimental Conditions)

・Sheet 1 FP600/easy

・Sheet 2 FP600/hard

・Sheet 3 FP3000/easy

・Sheet 4 FP3000/hard

●Column Layout

Column 1 (Time): The timeline (time points) in milliseconds (ms) relative to the event onset (0 ms).

Columns 2 to 25: The averaged EEG amplitude values in microvolts (µV) for each individual subject.
