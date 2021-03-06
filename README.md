# array-means
Calculates various averages of an array

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/57813ca8a5d943ecabbe8decc36d04da)](https://www.codacy.com/app/Bikossor/array-means?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Bikossor/array-means&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/Bikossor/array-means.svg?branch=develop)](https://travis-ci.org/Bikossor/array-means)
[![codecov](https://codecov.io/gh/Bikossor/array-means/branch/develop/graph/badge.svg)](https://codecov.io/gh/Bikossor/array-means)
![npm bundle size (minified + gzip)](https://img.shields.io/bundlephobia/minzip/array-means.svg)
![npm](https://img.shields.io/npm/dm/array-means.svg)
![GitHub issues](https://img.shields.io/github/issues/bikossor/array-means.svg)
![GitHub closed issues](https://img.shields.io/github/issues-closed/bikossor/array-means.svg)
![GitHub](https://img.shields.io/github/license/bikossor/array-means.svg)

## Installing
### Node.js environment
```
npm i array-means --save
```

### Browser environment
Download the latest version of array-means [here](https://github.com/Bikossor/array-means/releases/latest).

## Usage
### Node.js environment

```javascript
const arrayMeans = require("array-means");
```

### Arithmetic mean ([Wikipedia](https://en.wikipedia.org/wiki/Arithmetic_mean)):
```javascript
var amean = arrayMeans.arithmetic([10, 25, 50]);
var amean = arrayMeans.a([10, 25, 50]);
// amean => 28.333333333333332
```

### Quadratic mean ([Wikipedia](https://en.wikipedia.org/wiki/Quadratic_mean)):
```javascript
var qmean = arrayMeans.quadratic([10, 25, 50]);
var qmean = arrayMeans.q([10, 25, 50]);
// qmean => 32.78719262151
```

### Harmonic mean ([Wikipedia](https://en.wikipedia.org/wiki/Harmonic_mean)):
```javascript
var hmean = arrayMeans.harmonic([10, 25, 50]);
var hmean = arrayMeans.h([10, 25, 50]);
// hmean => 18.75
```

### Geometric mean ([Wikipedia](https://en.wikipedia.org/wiki/Geometric_mean)):
```javascript
var gmean = arrayMeans.geometric([10, 25, 50]);
var gmean = arrayMeans.g([10, 25, 50]);
// gmean => 23.20794417
```

### Cubic mean ([Wikipedia](https://en.wikipedia.org/wiki/Cubic_mean)):
```javascript
var cmean = arrayMeans.cubic([10, 25, 50]);
var cmean = arrayMeans.c([10, 25, 50]);
// cmean => 36.14150411
```

## Benchmark
| Algorithm | Operations per second | Tolerance | Number of runs |
| :-- | :-- | :-- | :-- |
| arithmetic | 57,677,242 ops/sec | ±0.09% | 92 runs sampled |
| quadratic | 31,527,477 ops/sec | ±0.04% | 96 runs sampled |
| harmonic | 107,957,742 ops/sec | ±0.39% | 95 runs sampled |
| geometric | 122,245,766 ops/sec | ±0.22%| 95 runs sampled |
| cubic | 106,860,481 ops/sec | ±0.44% | 92 runs sampled |

Tested with the benchmark suite inside the package on a PC with an Intel Core i7-4790K @ 4.40 GHz using Node.js v10.13.0.

## Contributing
Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags](https://github.com/bikossor/array-means/tags) on this repository. 

## Authors
- [Bikossor](https://github.com/Bikossor)
- [Dergeraetwirdniemuede](https://github.com/Dergeraetwirdniemuede)

See also the list of [contributors](https://github.com/bikossor/array-means/contributors) who participated in this project.

## License
This project is licensed under the GPL-3.0 License - see [here](LICENSE) for more details.