# eol-mistrust
Race and Mistrust in End-of-Life Care

Short workshop paper (FAT/ML 2018): https://arxiv.org/abs/1807.00124

    @article{boag-fatml2018,
     title={Modeling Mistrust in End-of-Life Care},
     author={W. Boag and H. Suresh and L.A. Celi and P. Szolovits and M. Ghassemi},
     publisher={Fairness, Accountability, and Transparency in Machine Learning (FAT/ML 2018) workshop},
     year={2018}
    }

15-page conference paper (MLHC 2018): https://arxiv.org/abs/1808.03827

    @article{boag-mlhc2018,
     title={Racial Disparities and Mistrust in End-of-Life Care},
     author={W. Boag and H. Suresh and L.A. Celi and P. Szolovits and M. Ghassemi},
     publisher={Machine Learning for Healthcare (MLHC)},
     year={2018}
    }

Masters Thesis: https://willieboag.files.wordpress.com/2018/05/wboag-masters.pdf

    @MastersThesis{boag-thesis2018,
     title={Quantifying Racial Disparities in End-of-Life Care},
     author={W. Boag},
     school={MIT},
     year={2018}
    }


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
