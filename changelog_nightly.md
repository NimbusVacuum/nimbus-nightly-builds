## Valetudo nightly (2022-10-29T11:09:37.229Z)

### Features

- **ui**: Limit wifi scan results [`552e312`](https://github.com/Hypfer/Valetudo/commit/552e3126ef7af0b0ccdf6610e49d9e77c13054e4)
- **ui**: WiFiScanCapability support for the provisioning page [`9a8691c`](https://github.com/Hypfer/Valetudo/commit/9a8691c99799aac1adcf5390a3064978988025d8)
- **ui**: Cache layers in render worker for improved performance [`3c9b469`](https://github.com/Hypfer/Valetudo/commit/3c9b469373e9d42a0e98b341f0762dd2eba95522)
- **vendor.dreame**: Some dreames allow for more than one zone [`f7ff27c`](https://github.com/Hypfer/Valetudo/commit/f7ff27ca9d7bb4db02792894037c2455bacb6018)
- **ui**: Segment selection improvements [`cc34e20`](https://github.com/Hypfer/Valetudo/commit/cc34e2025c28b4e21167e90cb5953aa86eada755)
- **ui**: Render mapLayers to cropped imageData for better performance and less memory usage [`5bb3fae`](https://github.com/Hypfer/Valetudo/commit/5bb3fae055d9878f05a162cc41485b72458d5040)
- **vendor.dreame**: More mop stuff [`5a6d9d1`](https://github.com/Hypfer/Valetudo/commit/5a6d9d15dba3472a568812968b475ddbd0e17800)
- **vendor.dreame**: Support for the L10 Plus [`5ec12d3`](https://github.com/Hypfer/Valetudo/commit/5ec12d373c55672909cafb3c3be41b8ce95cbc14)
- **updater**: Attempt to use upx in low storage situations [`4227918`](https://github.com/Hypfer/Valetudo/commit/42279189051c196b827dc8dbb63339d219baa784)
- **ui**: Provide some feedback on virtual restriction save [`e685e3e`](https://github.com/Hypfer/Valetudo/commit/e685e3e54857215acb95216999b928d72d61185e)

### Fixes

- **miio**: Fix deviceID being changed to an invalid value [`3a1582d`](https://github.com/Hypfer/Valetudo/commit/3a1582d7b34c5113b1cadb2f478c354fe272c192)
- **ui**: Add workaround for DOMMatrix.invertSelf() issues with Chrome 107++ [`46ed757`](https://github.com/Hypfer/Valetudo/commit/46ed75737c6aab8d1803bbd2479f39b0f20a4990)
- **ui**: Reset preset slider if value wasn't applied after 1s [`c6cbdc2`](https://github.com/Hypfer/Valetudo/commit/c6cbdc22e9dc2e33c23c4a48ecf22f4bd836ca14)
- Fix incorrectly reported virtual restrictions [`c4d5df8`](https://github.com/Hypfer/Valetudo/commit/c4d5df8f78421d7254dd0a55ea610825552612e8)

### Chores

- Minor cleanup [`5f13e8f`](https://github.com/Hypfer/Valetudo/commit/5f13e8f130615a78d68688a8f780c1de09fd49ce)
- Minor cleanup [`1a614e9`](https://github.com/Hypfer/Valetudo/commit/1a614e9fd7925a33cf68d4428d6c396c36854877)
- **build**: More heap for regular armv7 [`08ec8b7`](https://github.com/Hypfer/Valetudo/commit/08ec8b7c6444ffbfab7f73514259c19200f9e959)
- **vendor.dreame**: Add test case map with left cutoff by firmware [`040d4fb`](https://github.com/Hypfer/Valetudo/commit/040d4fb2a616c36e572aaf536c1f2cc419a0d705)
- **ui**: 75% battery should not be displayed in a warning color [`a5e1bc2`](https://github.com/Hypfer/Valetudo/commit/a5e1bc2541c2ca268b6de25b9d7790f01314b8d6)
