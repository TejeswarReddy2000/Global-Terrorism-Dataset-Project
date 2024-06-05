# Global-Terrorism-Dataset-Project
The code filters the dataset to exclude 'Unknown' terrorist groups, then converts the 'year' column to datetime, sets it as the index, and resamples by 10-year intervals. It identifies the most common terrorist group for each interval and resets the index to include the 'year' as a column.
