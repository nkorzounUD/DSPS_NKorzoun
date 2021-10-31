![histogram](https://github.com/nkorzounUD/DSPS_NKorzoun/blob/main/HW6/histogram.pdf) <br>
![histogram_fixed](https://github.com/nkorzounUD/DSPS_NKorzoun/blob/main/HW6/histogram_fixed.pdf)

Above are histograms of image parameters calculated from simulated data. These plots were made over the previous summer as I was conducting research. They are meant to show how the variance increases as the number of samples decreases - an example of the law of large numbers. In the first image, the histograms are truncated on both axes. The y-scale is not absolute; meaning the plots ambiguous and not easily comparable.  Additionally, the legend plots a 5th parameter that is mislabelled as "size" - which is quite confusing when each subplot is labelled by the size (number of samples).

In the fixed version, both axes are no longer being truncated and the mislabelled parameter has been removed alltogether. It did not make sense to plot the last parmeter, because it did not behave the same way as the other paramters due to a bug in the code. It is far easier to see the expected behavior in the second figure than the first.
