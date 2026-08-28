This R script provides a data-driven method for estimating the onset latency of the Lateralized Readiness Potential (LRP). Required Data Format (which is in the other Repository)

Column 1: Time values (e.g., milliseconds).

Columns 2 to a: Amplitude data (µV) for each subject or condition. (Note: The data must be applied baseline-correction prior to running this script.)

a: "n + 1", where "n" represents the total number of subjects (corresponding to the total number of columns in the data frame).

b: The start row index of the search range for sliding the regression start point, set in a stable baseline region where the amplitude is flat.

c: The end row index of the search range for sliding the regression start point, set at an arbitrary point where the waveform deflection/rise begins.

x: A data frame containing the time series in the first column and individual subject waveform data in columns 2 through a.

y: The start row index of the search window defined to identify the peak (maximum) amplitude.

z: The end row index of the search window defined to identify the peak (maximum) amplitude.
