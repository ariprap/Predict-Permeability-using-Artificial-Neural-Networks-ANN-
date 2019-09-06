# Predict-Permeability-using-Artificial-Neural-Networks-ANN-

Permeability is defined as the efficiency with which a fluid such as oil, gas can penetrate through a reservoir. Comprehension of an appropriate value of permeability plays a key role and an efficient tool used by the oil engineers during the process when an oil field is produced and managed.

The dataset selected for prediction of permeabili tyincludes core plug permeability measurements and well log data of a well.Following three log variables: Gamma ray, bulk density, and neutron derived porosity were used in conjunction with core measured permeability to construct and ANN model. 
 
To train the ANN model, the well log data of a well was used. Well data of other wells was used for verification and production (prediction). 

**ANN MODEL**
The ANN model built had 4 layers(1 input, 2 hidden and 1 output layer).
The activation function used was tanh.
The network makes predictions using forward propagation. The model was implemented using numpy and pandas libraries.

**Accuracy**
The model gave an accuracy of approx. 99%.
