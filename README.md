## NOTE: Three (3) different Modeling projects are included in this repository:
1. Image Classification task of satellite image chips of the Amazon Rainforests to understand from space what is going on there. This project was completed Convolutional Neural Networks(CNN) archtecture. More details are found in the notebook (Amazon).

2. Time Series Analysis to understand Electricity consumption per household. A type of Artificial Neural Network called LSTM (see the notebook)

3. Binary Classification Task to predict whether electric grids are stable or not.


======================================================================================================================================================================



### Below Contains information about the project number 3 (Only). See Each Notebook for other Details

### PROJECT 3: To Predict the Stability or not of Electricity Grids
#### Description: Stability of the Grid System
Electrical grids require a balance between electricity supply and demand in order to be stable. Conventional systems achieve this balance through demand-driven electricity production. For future grids with a high share of inflexible (i.e., renewable) energy source, the concept of demand response is a promising solution. This implies changes in electricity consumption in relation to electricity price changes. In this work, different algorithms were used to built binary classifiers to predict if a grid is stable or unstable using the UCI Electrical Grid Stability Simulated dataset. Performnce Metrics are used to determine the accuracy of the predictions.

Dataset Link: https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+ It has 12 primary predictive features and two dependent variables.

**Dataset Link:** https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+
It has 12 primary predictive features and two dependent variables.

#### Predictive features:	
1.	'tau1' to 'tau4': the reaction time of each network participant, a real value within the range 0.5 to 10 ('tau1' corresponds to the supplier node, 'tau2' to 'tau4' to the consumer nodes);
2.	'p1' to 'p4': nominal power produced (positive) or consumed (negative) by each network participant, a real value within the range -2.0 to -0.5 for consumers ('p2' to 'p4'). As the total power consumed equals the total power generated, p1 (supplier node) = - (p2 + p3 + p4);
3.	'g1' to 'g4': price elasticity coefficient for each network participant, a real value within the range 0.05 to 1.00 ('g1' corresponds to the supplier node, 'g2' to 'g4' to the consumer nodes; 'g' stands for 'gamma');

#### Dependent variables:
1.	'stab': the maximum real part of the characteristic differential equation root (if positive, the system is linearly unstable; if negative, linearly stable);
2.	'stabf': a categorical (binary) label ('stable' or 'unstable').
