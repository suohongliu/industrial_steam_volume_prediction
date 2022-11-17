# industrial_steam_volume_prediction

The data collected by the boiler sensor (the collection frequency is at the minute level), predicts the amount of steam generated according to the working conditions of the boiler.

* independent variables: "V0" - "V37"
* dependent variable: "target"
* The prediction results are judged by the mean square error (MSE)
 *  MSE = $\frac{1}{n} \Sigma_{i=1}^n({y}-\hat{y})^2$
