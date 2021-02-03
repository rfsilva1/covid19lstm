# An in-depth analysis on the use of long short-term memory networks to predict incidence and prevalence of Covid-19 in Latin America
## Description
This repository contains the code and datasets for the paper An in-depth analysis on the use of long short-term memory networks to predict incidence and prevalence of Covid-19 in Latin America, by Bruna L. Barreira, Roberto F. Silva, and Carlos E. Cugnasca. We studied the following countries: Argentina, Bolivia, Brazil, Colombia, Cuba, Guatemala, Haiti, Mexico, and Peru. This paper was published at the FAIML 2020 (2020 International Conference on Frontiers of Artificial Intelligence and Machine Learning) scientific event. Descriptions of the implementation and the dataset are contained in the paper. The PDF is available in this repository. The code is composed of 1 Colab notebook.

The code was developed by Bruna Lobato Barreira and Roberto Fray da Silva.

Reference of the paper and to cite this repository: 
BARREIRA, B. L. ; SILVA, R. F. ; CUGNASCA, C.E. . An in-depth analysis on the use of long short-term memory networks to predict incidence and prevalence of Covid-19 in Latin America. In: 2020 International Conference on Frontiers of Artificial Intelligence and Machine Learning (FAIML), 2020, Berlin. Proceedings of (2020 International Conference on Frontiers of Artificial Intelligence and Machine Learning, 2020. v. 1.

## To Do (further research, out of the scope of this paper):
- optimize code for deployment in production (there are several parts of the code that can be improved)
- deploy code for daily evaluation
- incorporate new variables (socioeconomic, population density, etc) and more recent data
- automate data collection
- automate model choice and hyperparameters (AutoML with Optuna?)
- optimize gridsearch (Optuna?)
- evaluate other models, such as bi-lstms
- evaluate other options of feature engineering

## Credits for the code:
The code was implemented using Google Colab to improve replicability (https://colab.research.google.com/) and was based on the following:
- Use of econometrics and machine learning models to predict the number of new cases per day of COVID-19 - Code and datasets: https://github.com/rfsilva1/covid19timeseries
- Time series forecasting tutorial from TensorFlow 2.0: https://www.tensorflow.org/tutorials/structured_data/time_series
- SVR tutorial from Scikit-Learn 0.23 : https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html

The authors would like to thank the authors of the codes for providing them as examples for the use of the libraries and model implementation. 

The authors would also like to thank all the developers that were and are involved on the development of the following Python libraries: 
- TensorFlow: https://www.tensorflow.org/
- Statsmodels: https://www.statsmodels.org/stable/index.html
- Pandas: https://pandas.pydata.org/
- Scikit-Learn: https://scikit-learn.org/
- Matplotlib: https://matplotlib.org/
- NumPy: https://numpy.org/
- Seaborn: https://seaborn.pydata.org/

## Credits for the dataset:
The authors would like to thank the following institutions/researchers for providing the data collected:
- World Bank: total population: http://wdi.worldbank.org/table/2.1#
- Johns Hopkins University CSSE [Dong, Du, Gardner, 2019]: number of recovered patients for Brazil: https://github.com/CSSEGISandData/COVID-19  and  Dong, E., Du, H., Gardner, L. (2020) "An interactive web-based dashboard to track COVID-19 in real time". The Lancet Infectious Diseases, Correspondence, p.1-2.
- Max Roser, Hannah Ritchie, Esteban Ortiz-Ospina and Joe Hasell (2020) - "Coronavirus Pandemic (COVID-19)". Published online at OurWorldInData.org. Retrieved from: 'https://ourworldindata.org/coronavirus' [Online Resource]

## Acknowledgements:
This work was supported by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brazil (CAPES) - Finance Code 001, Itaú Unibanco S.A. through the Itaú Scholarship Program, at the Centro de Ciência de Dados (C2D), Universidade de São Paulo, Brazil, and also by the National Council for Scientific and Technological Development (CNPq).
