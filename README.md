# stacking-ensemble

Short-term load forecasting is an important problem. With reliable and precise prediction of short-term load, schedules can be generated in order to determine the allocation of generation resources,
operational limitations, environmental and equipment usage constraints. Knowing the short-term energy demand can also help in ensuring the power system security since accurate load prediction can
be used to determine the optimal operational state of power systems. 
Accurate prediction of electricity consumption is essential for providing actionable insights to decision-makers for managing volume and potential trends in future energy consumption for efficient resource management. 
A single model might not be sufficient to solve the challenges that result from linear and non-linear problems that occur in electricity consumption prediction. 
In this project, we use a stacking ensemble model for short-term electricity consumption on an open dataset.
The base layer is made up of models like Random Forests, Long Short Term Memory, Deep Neural Networks, and Evolutionary Trees.
The predictions of the base models are combined using Extreme Gradient Boosting (XGB). 
Experimental validation revealed that the proposed ensemble model built on XGB is more accurate than the state-of-the-art solution. 

This project is an enhancement of the work proposed in <a href="https://www.mdpi.com/1996-1073/11/4/949/htm" target="_blank">Stacking Ensemble Learning for Short-Term Electricity Consumption Forecasting</a>
