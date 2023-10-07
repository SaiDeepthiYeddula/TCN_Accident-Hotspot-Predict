# Traffic Accident Hotspot Prediction Using Temporal Convolutional Networks: A Spatio-Temporal Approach

[ACM SIGSPATIAL 2023] Traffic Accident Hotspot Prediction Using Temporal Convolutional Networks: A Spatio-Temporal Approach

Sai Deepthi Yeddula, Chen Jiang, Bo Hui, Wei-Shinn Ku

## Overview
Predicting traffic accident hotspots is crucial for ensuring public safety, improving transport planning, and reducing transportation costs. Traditional deep learning models, such as Transformers and Long Short-Term Memory Networks (LSTMs), have been successful in this field but encounter challenges in effectively capturing complex patterns and fail to efficiently model long-term multivariate dependencies in the data, which limits their ability to achieve the desired level of forecasting accuracy. Moreover, previous studies often fail to integrate critical attributes such as traffic volume, road attributes, and accident-specific factors. To address these limitations, we propose the utilization of a Temporal Convolutional Network (TCN),  leveraging dilated and causal convolutional layers to model complex structures and nonlinear relationships inherent in traffic accident datasets. This proposed model efficiently learns spatial, temporal, and other external factors integral to accident hotspot prediction. Our experimental results demonstrate the superior performance of the proposed model over the state-of-the-art methods, achieving 97\% accuracy for binary and 95\% for multi-class hotspot prediction. The proposed TCN architecture empowers transportation officials in promoting safety measures by offering valuable insights for proactive accident mitigation.

## Methodology
![new_proposed_archit](https://github.com/SaiDeepthiYeddula/TCN_Accident-Hotspot-Predict/assets/42706378/4cf46a45-6cd1-45ed-bfbf-5a6471dfc814)
Proposed Temporal Convolutional Network (TCN) Architecture. The diagram illustrates the integration of spatial features and temporal characteristics of traffic accident hotspots into the TCN

## Preliminary Data Analysis

## Annual Trend Analysis in Accident Frequency
Significant trends have emerged in the analysis of the number of traffic accidents recorded annually from 2016 to 2021, providing insights into traffic conditions across the USA, as shown in the below Figure. The data shows a consistent and moderate decline in accident rates from 2016 through 2019. This is likely due to factors such as improvements in vehicle safety standards, implementation of more effective traffic regulations, and enhancements in infrastructural design, all of which have significantly contributed to safer road conditions.

Despite these positive developments, a shift in trends is evident from 2020, as the number of accidents surged substantially through 2021. This abrupt increase coincides with the outbreak of the COVID-19 pandemic. The accident rates did not follow the expected downward trajectory despite stay-at-home orders, lockdowns, and the shift to remote work that noticeably diminished daily commuting, particularly in urban areas. A plausible explanation could be that the reduced vehicular congestion encouraged riskier driving behaviors, such as speeding. Concurrently, a shift in traffic patterns was observed, with increased pedestrian and cyclist traffic in certain areas, possibly escalating the likelihood of accidents. Furthermore, the pandemic-induced economic strain might have impacted public health resources and prompted adjustments in traffic law enforcement strategies, potentially affecting the effective monitoring and imposition of traffic regulations.

<img src="https://github.com/SaiDeepthiYeddula/TCN_Accident-Hotspot-Predict/assets/42706378/897f0239-f7a6-4381-85df-ec0d5dcd086d/" width="500" height="350">

## Impact of Weather Conditions on Accident Frequency (2016-2021)
The correlation between weather conditions and the number of traffic accidents has been explored, as shown in the below Figure. It demonstrates that more accidents occurred during clear weather than adverse conditions on average between 2016 and 2021. In contrast to the common belief that severe weather such as fog, snow or heavy rain contributes significantly to accidents, the data suggests otherwise. The primary reason for this may be that clear weather makes drivers feel safer, resulting in less vigilance, overspeeding, and distracted driving.  Additionally, clear weather is generally associated with higher traffic volumes, which inherently increases accident probabilities. On the other hand, in adverse weather, drivers exercise greater caution, and fewer accidents are caused through the efficiency of weather alert systems that cause people to stay indoors, thereby reducing traffic volume.

<img src="https://github.com/SaiDeepthiYeddula/TCN_Accident-Hotspot-Predict/assets/42706378/e10ca293-770f-42dd-a7d7-e4a409967dc4" width="500" height="300">

## Route-Specific Accident Frequency Analysis (2016-2021)
Across various road types in the USA over six years, it becomes clear that State Highway Routes and Local Streets consistently reported the highest number of accidents on an average, likely due to increased traffic density and complex intersections, as shown in the below Figure. Conversely, with fewer conflict points and safety-focused designs, U.S. Highways and Interstates recorded lower accident figures. County Roads reported fewer accidents, serving less populated areas and experiencing reduced traffic volume. This trend has persisted over the years, suggesting the dominant influence of road type and usage on accident rates. 

<img src="https://github.com/SaiDeepthiYeddula/TCN_Accident-Hotspot-Predict/assets/42706378/f1181231-4289-4c69-9427-7ed31c310f16" width="500" height="350">
