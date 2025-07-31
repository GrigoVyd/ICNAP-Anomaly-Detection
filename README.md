# ICNAP-Anomaly-Detection

For this taks, the recorded current of four motors in the production line was provided. Based on the course of the current, we have designed an algorithm that identifies the filling of entire plaquettes and individual vials based on thresholding. The resulting individual fillings are used to train a variational autoencoder that maps the fillings into a 5-dim embedding space. In this embedding space, we run a k-Means clustering algorithm and detect outliers deviating from the found clusters.<br>
As a result, we find unusual signatures in the filling of individual vials.

<p>The entire analysis can be found in the corresponding notebook *motor_anomalies.ipynb*. Furthermore, we have uploaded the trained VAE model, data and example outliers.</p>


