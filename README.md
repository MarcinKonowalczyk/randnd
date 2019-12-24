# randnd

[![View randnd on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://uk.mathworks.com/matlabcentral/fileexchange/59305-randnd)

This function is a "decorator" for the Matlab in-build `randn` function. It takes an additional first argument (beta) which shapes the spectral characteristic of the data (in all dimensions) as f^beta. The output data is scaled to the original mean and standard deviation. It creates N-dimensional 1/beta (e.g. pink, brown, blue) noise generation via spectral shaping of white noise.
