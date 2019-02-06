# SparkAR-Counter
A counter patch that updates every frame in Spark AR.

Spark AR doesn't provide a way to hold state between frames other than the Counter patch and Switch patch. In addition, because you're required to use a Pulse patch, both Counter and Switch can only be updated once every two frames (one frame for the pulse to turn on, one for it to turn off). This patch provides a counter that updates every frame that the +1 or -1 inputs are set to true and does not force you to use a Pulse patch.

