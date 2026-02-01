# gearbox-predictive-maintenance
In this project, a vibration-based predictive maintenance system was developed to classify gearbox bearing conditions as normal or faulty. Real industrial vibration data was segmented into fixed-length windows, and core mechanical features—RMS, kurtosis, and FFT energy—were extracted from each segment.

The results showed that faulty bearings exhibit significantly higher vibration energy and impulsive behavior compared to healthy bearings. Using these physically meaningful features, a Random Forest classifier was trained and achieved high classification accuracy on the test data.

This demonstrates that combining vibration analysis principles with machine learning provides an effective approach for early fault detection in rotating machinery. Such a system can help reduce unplanned downtime and improve reliability in automotive and manufacturing applications.
