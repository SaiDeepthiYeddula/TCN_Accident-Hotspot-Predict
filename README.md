# Traffic Accident Hotspot Prediction Using Temporal Convolutional Networks: A Spatio-Temporal Approach

Sai Deepthi Yeddula, Chen Jiang, Bo Hui, Wei-Shinn Ku

## Overview
Predicting traffic accident hotspots is crucial for ensuring public safety, improving transport planning, and reducing transportation costs. Traditional deep learning models, such as Transformers and Long Short-Term Memory Networks (LSTMs), have been successful in this field but encounter challenges in effectively capturing complex patterns and fail to efficiently model long-term multivariate dependencies in the data, which limits their ability to achieve the desired level of forecasting accuracy. Moreover, previous studies often fail to integrate critical attributes such as traffic volume, road attributes, and accident-specific factors. To address these limitations, we propose the utilization of a Temporal Convolutional Network (TCN),  leveraging dilated and causal convolutional layers to model complex structures and nonlinear relationships inherent in traffic accident datasets. This proposed model efficiently learns spatial, temporal, and other external factors integral to accident hotspot prediction. Our experimental results demonstrate the superior performance of the proposed model over the state-of-the-art methods, achieving 97\% accuracy for binary and 95\% for multi-class hotspot prediction. The proposed TCN architecture empowers transportation officials in promoting safety measures by offering valuable insights for proactive accident mitigation.

## Methodology
![new_proposed_archit](https://github.com/SaiDeepthiYeddula/TCN_Accident-Hotspot-Predict/assets/42706378/dcd34023-cef5-4d5b-a66f-cd5aa90a10d9)
Proposed Temporal Convolutional Network (TCN) Architecture. The diagram illustrates the integration of spatial features and temporal characteristics of traffic accident hotspots into the TCN
