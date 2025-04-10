# MOF-Ni-Catalysts

## Interpretable Machine Learning Reveals Structural Insights into Selective C–H Borylation by Metal-Organic Framework-Supported Ni Catalysts
This repository contains the source codes and documentation used in the publication **"Interpretable Machine Learning Reveals Structural Insights into Selective C–H Borylation by Metal-Organic Framework-Supported Ni Catalysts"**. It provides tools for descriptor calculation, factor analysis, dimension reduction, and machine learning workflows.

---

## Installation
To use the code in this repository, clone the repository and install the necessary dependencies listed in the [Requirements](#requirements) section.

```code
git clone <repository-url>
cd mof-ni-catalysts
```


### Requirements
Ensure you have the following dependencies installed before running the code:
```code
Python 3.8+
pandas
numpy
scikit-learn
matplotlib
seaborn
```
Install the dependencies using pip.

## Usage
### 1. Calculating Descriptors of Synthesized MOFs
The MOF descriptors for the synthesized MOFs were calculated according to the methods described in the [ARC-MOF paper](https://pubs.acs.org/doi/abs/10.1021/acs.chemmater.2c02485). Please refer to [mof_descriptor_calculator](https://github.com/Wang-Group/mof_descriptor_calculator) for the details to calculate the descriptors.

### 2. Factor Analysis of the Existing MOF Dataset
The factor analysis of the MOF dataset was performed in [MOFscreen_FA.ipynb](./Machine_learning/MOFscreen_FA.ipynb). The correlation of the factors and the descriptors are shown in the output panel of the notebook. 

### 3. Dimension Reduction and Machine Learning
The dimension reduction to study the correlation between the MOF descriptors and catalysis performance was performed in [MOFscreen_Bayes_ML.ipynb](./Machine_learning/MOFscreen_Bayes_ML.ipynb). In the same notebook, we also performed machine learning and Bayesian regression for data analysis. The ouput panels show all the relavent results in the notebook.

### 4. Plotting the Frequency and Significance of Factors
The frequency and significance of factors were analyzed in the ML notebook. They are showin in Figure 1 and Figure 3 in the manuscript. The source code to plot them can be found in [Figures](./Figures/).

## Documentation and Citation
For a detailed understanding of the methods and results, please refer to the publication.

## Contributions and Support
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License.