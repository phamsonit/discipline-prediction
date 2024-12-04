This repository contains the source code and sample data for the research project discipline prediction framework proposed in the paper "A Metadata-Based Approach for Research Discipline Prediction Using Machine Learning Techniques and Distance Metrics."


Forecasting research disciplines associated with research projects is a significant challenge in research information systems. It can reduce the administrative effort involved in entering research project-related metadata, eliminate human errors, and enhance the quality of research project metadata. It also enables the calculation of the degree of interdisciplinarity of these projects. However, predicting scientific research disciplines and measuring interdisciplinarity in a research endeavor remain difficult. In this paper, we propose a framework for predicting the research disciplines associated with a research project and measuring the degree of interdisciplinarity based on associated metadata to address these issues.


The framework includes several components that leverage various topic models and machine learning techniques. The implementation of the framework is contained in main.py. To change parameters such as the topic model or machine learning algorithm, modifications must be made directly in main.py.  The software offers two modes: train and test, which are determined by the task variable. Set task = 'train' to train the model on the provided training dataset. Set task = 'test' to test the model on the given test dataset. Other parameters such as topic model or machine learning algorithm can also changed in this file.


The software is implemented in Python and requires several libraries. Please refer to main.py for details about the required packages.


For testing purposes, a sample dataset is provided in the outputs\\data directory. It includes FRIS_project_data.csv containing a list of projects extracted from FRIS portal and Dimensions_project_data.csv containing a list of projects extracted from Dimensions. For each dataset, the coresponding distance matrix, discipline list are also provided.


Cite this source code or article: H. -S. Pham, H. Poelmans and A. Ali-Eldin, "A Metadata-Based Approach for Research Discipline Prediction Using Machine Learning Techniques and Distance Metrics," in IEEE Access, vol. 11, pp. 61995-62012, 2023, doi: 10.1109/ACCESS.2023.3287935.