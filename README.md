# An LSTM approach to Predict Migration based on Google Trends

Codes by Nicolas Golenvaux & Pablo Gonzalez Alvarez.

This repository contains the companion codes for the paper
[An LSTM approach to Predict Migration based on Google Trends](https://arxiv.org/abs/2005.09902) by Nicolas Golenvaux, Pablo Gonzalez Alvarez, Harold Silvère Kiossou, Pierre Schaus.

This paper is part of our joint master's thesis work.

## Install requirements

`pip install -r requirements.txt`

## Structure

Files without a comment have a descriptive name to understand what they contain:

    /                                       I am (G)root!
        LICENSE.md                          MIT License
        README.md                           You are here
        extract_gti.py
        migration-gti-lstm.ipynb            Notebook to build models
        requirements.txt
        data/
            LICENSE.md                      CC-BY-4.0 License
            basicDataLSTM.pkl
            bestResultLSTM.pkl
            dataANN.pkl
            destination_countries.csv
            keywords.csv
            logDataLR.pkl
            origin_countries.csv
            replication_bilateral.dta
            resultANN_test.pkl
            resultANN_train.pkl


## License

Except stated otherwise (cf. [Credits](#credits)), the content of this repository itself as well as the data are licensed under the [Creative Commons Attribution 4.0 International License (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/), and the  source codes are licensed under the [MIT License](https://spdx.org/licenses/MIT.html).

## Credits

	Data sources:
        Google Trends (https://www.google.com/trends)
        M. H. Böhme, A. Gröger, and T. Stöhr, "Searching for a better life: Predicting international migration with online search keywords" - Researcher Data (https://www.sciencedirect.com/science/article/pii/S0304387819304900#mmc2)
        OECD International Migration Database (https://www.oecd-ilibrary.org/content/data/data-00342-en)
        United Nations Department of Economic and Social Affairs Population Division UN DESA. International Migrant Stock 2019 (https://www.un.org/en/development/desa/population/index.asp)
        World Bank 2020 World Development Indicators (https://datacatalog.worldbank.org/dataset/world-development-indicators)

    Software licenses:
        Keras (https://keras.io) - MIT License
        Matplotlib (https://matplotlib.org/) - Matplotlib License
        NumPy (https://numpy.org/) - BSD-3-Clause License
        Pandas (https://pandas.pydata.org/) - BSD-3-Clause License
        pytrends (https://github.com/GeneralMills/pytrends) -  Apache-2.0 License
        Scikit-learn (https://scikit-learn.org/) - BSD-3-Clause License
        Seaborn (https://seaborn.pydata.org) - BSD-3-Clause License
        Tensorflow (https://www.tensorflow.org) - Apache License 2.0
