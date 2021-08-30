# QCNNForecasting

This repository served as a container for notebooks investigating the development of novel quantum convolutional neural networks for foreccasting biogas production during anaerobic processes in waste-management facilites. 

No software installations are necessary for executing the models. Simply import the notebooks into Google Colab to execute code. The primary notebooks, ModelMaker, QuantumModelMaker, and Processor follow two distinct but congruent processes. Using workflow design patterns preprocessing and, validation and model building are separated and containerised.
Checkpoint pattern is used to reduce the chances of overfitting and provide some tolerance to delicate architectures like QCNNs.

The PreProcessor notebooks generates a dataset that can be utilised to obtain a continuoys time series dataset. The final dataset, named viable_dataset.csv, is used in both model makers to obtain insights.

Both, discrete and time-window models for classical and quantum architectures can be made by using 'time-window' or 'discrete' as input arguments passed into buildmodel() functions.


