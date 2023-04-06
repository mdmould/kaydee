# kaydee

Kernel density estimation with a wrapper of `scipy.stats.gaussian_kde`.

Includes bounded domains using reflected samples.

Includes multiprocess density evaluations using [tqdm-pathos](https://github.com/mdmould/tqdm_pathos). This is useful for KDEs fit to large sample sizes evaluated on a large set of points, which can be quicker than array evaluations.

`pip install kaydee`
