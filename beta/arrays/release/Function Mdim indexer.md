Method:
    A Function that returns the flatten index of a array of N dimensions.

Inputs:
    _indices: Array containing dimension indices.¹
    _limits: Array containing dimension size.¹

    Note:
        ¹: _indices and _limits size must match. indices must be within dimension size.

Outputs:
    _offset: the flatten 1D index.

Resources:
    https://eli.thegreenplace.net/2015/memory-layout-of-multi-dimensional-arrays