# EEG Data

The MATLAB code is for analyzing EEG data, specifically for detecting sleep apnea episodes by processing EEG signals from a subject.

## Data Loading:

- Reads an EDF file containing EEG data for a specific subject.
- Extracts EEG signals from two channels (C3A2 and C4A1) for further processing.

## Preprocessing:

- Combines the two EEG channels to create a single averaged signal.
- Applies a Butterworth bandpass filter to isolate specific frequency bands: delta, theta, alpha, sigma, and beta.

## Segmentation:

- Uses Excel data to identify the start and end times of apnea episodes.
- Separates EEG data into normal and apnea periods for each frequency band.

## Feature Extraction:

- Extracts statistical and signal-based features such as:

1. Energy
2. Kurtosis
3. Skewness
4. Interquartile Range (IQR)
5. Absolute Sum (Ass)
6. Activity
7. Mobility
8. Mean Absolute Deviation (MAD)
9. Complexity (Com)
10. Integral
These features are calculated for both normal and apnea segments across all frequency bands.

## Data Aggregation:

- Aggregates features into matrices for normal and apnea segments.
- Creates files containing delta and beta band data for normal and apnea cases.

## Quantization:

- Performs quantization of EEG signals for further processing or hardware implementation.

## Output:

- Saves results (processed signals and extracted features) into text files for further analysis or machine learning models.
