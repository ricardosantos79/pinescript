Description:
    A Function that returns a linear regression channel using (X,Y) vector points.

Inputs:
    _X: Array containing x data points.¹
    _Y: Array containing y data points.¹

    Note:
        ¹: _X and _Y size must match. 

Outputs:
    _predictions:   Array with adjusted _Y values at _X.
    _max_dev:       Max deviation from the mean.
    _min_dev:       Min deviation from the mean.
    _stdev/_sizeX:  Average deviation from the mean.

Resources:
    https://www.statisticshowto.com/probability-and-statistics/regression-analysis/find-a-linear-regression-equation/#FindaLinear
    https://en.wikipedia.org/wiki/Linear_regression