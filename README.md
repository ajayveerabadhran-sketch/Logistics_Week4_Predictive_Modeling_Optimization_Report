## Week 4: Predictive modeling and optimization

The Week 4 report uses the simulated shipment dataset introduced in Week 3 to predict delivery duration before dispatch. It compares a median baseline, Ridge regression, and two random forest configurations.

The models are selected using expanding window validation on earlier weeks and evaluated on held out weeks 10 to 12. The report explains mean absolute error (MAE), root mean squared error (RMSE), and R². It also includes a predicted versus observed delivery time chart and Python code excerpts.

In this simulation, Ridge regression achieved a test MAE of 8.72 minutes, compared with 20.11 minutes for the baseline. A proposed dispatcher review rule flags shipments at risk of missing their promised duration. Flagging a shipment does not mean a delay has been prevented.

**Report:** `Logistics_Week4_Predictive_Modeling_Optimization_Report.docx`

**Data note:** The shipment data and model results are simulated. Real dispatch data would be needed to validate the model or make operational changes.
