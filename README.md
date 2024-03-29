# Exoplanet-Detection-Using-Machine-Learning

Exoplanets are defined as planets orbiting a star outside our solar system. NASA launched the Kepler satellite in 2009 with the mission to hunt exoplanets. The data gathered by the satellite have been made publicly available by NASA in an attempt to increase development in the field of astroinformatics, a cross-disciplinary field consisting of astronomy, data science and informatics. 

## Paper Synopsis
In this paper, various deep learning techniques to detect exoplanets using the intensity of light captured by Kepler space telescope have been explored. The dimming in flux (light intensity) of the stars indicates an orbiting body around that star. Preliminary analysis is performed and the data is prepared to be fed in to the data mining models. Multiple models have been used to efficiently classify the exoplanets. The first model, H2O’s Deep Learning, is based on a multi-layer feedforward artificial neural network. Then a Convolutional Neural Network, a Black Box method, is deployed to classify the exoplanets.  Finally, Gradient Boosting technique is performed using the XGBoost algorithm, an ensemble technique that works on the concept of Decision Tree and Bootstrap Aggregation. This paper will provide the results, model performance and efficiency of the various algorithms used to detect such exoplanets.

## Dataset
The dataset for the research was created by [WΔ](https://github.com/winterdelta) who has now open-sourced them and can be downloaded [here](https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data). NASA open-sources the original Kepler Mission data and it is hosted at the [Mikulski Archive](https://archive.stsci.edu/k2/). The data presented here was cleansed and derived from observations made by the NASA Kepler space telescope. Over 99% of this dataset originates from Campaign 3. To boost the number of exoplanet-stars in the dataset, confirmed exoplanets from other campaigns were also included. To be clear, all observations from Campaign 3 are included. And in addition to this, confirmed exoplanet-stars from other campaigns are also included. All of this was done by [WΔ](https://github.com/winterdelta).

The data has a total of 5657 records and 3197 flux values which are numeric in nature. The dependent variable is a categorical variable – whether a star has a confirmed exoplanet or not.

## Video Link
[Over Here](https://www.youtube.com/watch?v=yKK-vfEytUU)
