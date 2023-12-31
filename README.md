# Group Assessment 1 for unit HIT140 - Group 9
## Objective
The goal of this project is to find a set of specific features that can tell apart individuals with Parkinson's disease from those without it.

## Data
We use a dataset provided by our lecturer in a .txt file. The original study collected voice recordings from 20 individuals with Parkinson's disease and 20 without. Each of these participants contributed 26 voice samples, and these were analyzed for different acoustic characteristics using software called Praat.

Learn more about Praat software: https://www.fon.hum.uva.nl/praat/

## Methodology
We divided the dataset into two groups: one representing individuals with Parkinson's disease and the other for healthy individuals. We then refined this data, enhancing its value through feature engineering. Using this enriched dataset, we delved into descriptive and inferential statistics. Ultimately, we employed statistical hypothesis testing for feature selection to pinpoint the most relevant attributes that distinguish those with Parkinson's from those without. Additionally, we segmented the dataset into 26 subsets to further identify key voice sample characteristics that differentiate the two groups. Our aim is to highlight voice samples with the most distinguishing features.

## Results
To conclude, we've pinpointed the following measurements, listed alongside their respective columns, from four distinct features to differentiate individuals with Parkinson's Disease from healthy ones:

Jitter(%, abs, rap, ppq5, ddp)

Shimmer(apq11)

Harmonicity(The autocorrelation between NHR and HNR)

Pitch(median, mean, standard deviation, max, range)

Pulse(mean period)

Jitter-Shimmer-Difference Ratio

Pulse-to-Pitch Ratio

The Unified Parkinson's Disease Rating Scale (UPDRS)

Based on the analysis of all subsets, voice samples numbered 4, 5, 6, 7, 9, 11, 12, 13, 15, 17, 18, 19, 20, 21, 23, 25, and 26 stood out as being particularly indicative (with at least 2 features selected) for distinguishing between individuals with Parkinson's disease and their healthy counterparts.

## Installation and usage guide
numpy: Used for numerical operations.

pandas: For data manipulation and analysis.

matplotlib: For plotting and visualization.

statistics: Provides functions to compute mathematical statistics of numeric data.

scipy: Used for high-level computations. Specifically, scipy.stats is being imported here.

statsmodels: Provides classes and functions for the estimation of statistical models.

To install these packages (if you haven't already), you can use 'pip'.

For example: pip install matplotlib

## Acknowledgement
We'd like to express our gratitude to our lecturer Dr. Yakub Sebastian at CDU for his invaluable guidance and insights throughout the duration of this project.

## List of project participants and contacts
I spearheaded this project as the team leader, with the invaluable collaboration of three other members: Thi Minh Chau Pham, Hai Dang Dang, and Quoc Vinh Nguyen.

Any concerns or contributions you might have, please feel free to reach me through [email](lecongdoo3@gmail.com).

## References
AZADI, H., AKBARZADEH-T, M.-R., SHOEIBI, A. & KOBRAVI, H. R. 2021. Evaluating the effect of Parkinson's disease on jitter and shimmer speech features. Advanced Biomedical Research, 10.

FERRAND, C. T. 2002. Harmonics-to-noise ratio: an index of vocal aging. Journal of voice, 16, 480-487.

FARRÚS, M., HERNANDO, J. & EJARQUE, P. Jitter and shimmer measurements for speaker recognition.  8th Annual Conference of the International Speech Communication Association; 2007 Aug. 27-31; Antwerp (Belgium).[place unknown]: ISCA; 2007. p. 778-81., 2007. International Speech Communication Association (ISCA).

RAMIG, L. O., FOX, C. & SAPIR, S. 2008. Speech treatment for Parkinson’s disease. Expert Review of Neurotherapeutics, 8, 297-309.

KHAN, T., WESTIN, J. & DOUGHERTY, M. 2014. Classification of speech intelligibility in Parkinson's disease. Biocybernetics and Biomedical Engineering, 34, 35-45.

BENBA, A., JILBAB, A. & HAMMOUCH, A. 2016. Voice analysis for detecting patients with Parkinson's disease using the hybridization of the best acoustic features. International Journal on Electrical Engineering and Informatics, 8, 108.
