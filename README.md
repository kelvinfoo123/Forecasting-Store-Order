# Forecasting-Store-Order
To ensure that there will always be sufficient stock supply to meet customer demand, this project uses time series analysis to forecast future order one month ahead of time. This allows the store to prepare for increasing demand should there be a lack of stock, and prevents surplus of stock in the store, which can lead to capital loss.

### **1. Models to consider**
Simple time series forecasting models (eg. ARIMA) were chosen over machine learning models although machine learning models may lead to better performance. 

### **2. Investigate model and hyparameter selection at different levels**
Model and hyperparameter selection could be done at 4 main levels: 
- Location level: The same model would be used to forecast orders for each store in the same location. 
- Store type level: The same model would be used to forecast orders for each store of the same store type.
- Store level: Different models would be used to forecast orders at different stores.
- Location & store type level: The same model would be used to forecast orders for each store of the same store type in the same location.

### **3. Determine performance of level and model**
- The performance of each model would be considered using mean absolute percentage error (MAPE), and a smaller MAPE implies a better performing model.
- For each level, the average MAPE would be obtained to determine which level would be the most optimal to be used to forecast future orders. 
