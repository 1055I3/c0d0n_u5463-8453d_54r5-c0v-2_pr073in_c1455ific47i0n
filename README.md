[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)](https://en.wikipedia.org/wiki/Project_Jupyter)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Windows](https://img.shields.io/badge/Windows-0078D6)](https://en.wikipedia.org/wiki/Windows_10)

# Codon Usage Based SARS-CoV-2 Protein Classification

Elements of my term paper in Data Mining 2 at Faculty of Mathematics, University of Belgrade.

## Description

The task was to classify different protein types of *SARC-CoV-2* virus, based on codon usage.
A dataset was given that included protein types and coding sequences, among other data.
After extracting features and preprocessing the data, a number of visualization techniques were applied, *t-SNE* among others.
Finally, seven different classifiers were trained and analysed.
Classifier behavinors were evaluated on training and test datasets.
Accuracy, precision, recall, and f1 scores were observed, along with confusion matrix and precision-recall curves.

## Requirements

To run this notebook, I used *Python 3.11.4* on *Windows 10 Pro* 22H2 and the libraries given in the following list.

| package         | ver.   |
|      :---:      | :---:  |
| notebook        | 7.0.4  |
| pandas          | 2.1.1  |
| numpy           | 1.24.4 |
| matplotlib      | 3.8.0  |
| seaborn         | 0.13.0 |
| dtreeviz        | 2.2.2  |
| dalex           | 1.6.0  |
| scikit-learn    | 1.3.1  |
| mlxtend         | 0.23.0 |
| openTSNE        | 1.0.0  |
| annoy           | 1.17.3 |
| xgboost         | 2.0.1  |
| tensorflow-cpu  | 2.14.0 |
| scikeras        | 0.12.0 |
| sklearn-genetic | 0.5.1  |
| yellowbrick     | 1.5    |

Please be aware that some of these libraries might have additional dependencies.

## License

This project uses BSD 3-Clause License.
The complete text can be found in *LICENCE* file.

## Additional

I would like to thank professor [*Nenad Mitic*](https://poincare.matf.bg.ac.rs/~nenad.mitic/) for his guidance and mentorship on this project.
