# Project4

Graph convolutional network with attention heads. Used 4 nearest neighbours but this is adjustable parameter. We look at previous 24 hours to predict the weather 6 hours in the future. The nearest neighbours are source based, each node looks at the 4 nodes closest to it but this is not necessarily reciprocal.

Training takes a long time so limited to 20 epochs with best epoch and patience.