# eol-mistrust
Race and Mistrust in End-of-Life Care

The code folder has 6 notebooks:
	1. race_mimic_aggressive.ipynb: Generate the figures for race-based treatment disparities in MIMIC

	2. trust.ipynb: Generates the various mistrust metric proxies and saves them to file.

	3. mistrust_mimic_aggressive.ipynb: Generate the figures for mistrust-based treatment disparities in MIMIC

	4. cohort.ipynb: Generate additional stats (e.g. table one, pairwise comparisons of metrics & severity score, etc)

	5. outcomes_ml.ipynb: Uses trust-based features to improve predictions for clinical tasks.

	6. race_eicu_aggressive.ipynb: Generate the figures for race-based treatment disparities in eICU


Run trust.ipynb before running:
	- mistrust_mimic_aggressive.ipynb

	- cohort.ipynb

	- outcomes_ml.ipynb
