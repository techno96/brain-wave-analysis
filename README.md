# brain-wave-analysis
A detection system for Drowsy driving by analyzing sampled and classified brain waves.

* The system uses an EEG (ElectroEncephaloGraph) headset with multiple EEG sensors and inbuilt Bluetooth transmitter, to transmit the captured brain wave data to the system. 
* The collected data is fed as input to the prediction model which decides whether the driver is being drowsy or not. 
* The prediction model is trained by using the Auto Regressive and Integrated Moving Average (ARIMA) time series algorithm to predict whether the person is being drowsy.

Paper : https://ieeexplore.ieee.org/document/8474915
