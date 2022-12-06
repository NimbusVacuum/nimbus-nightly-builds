## Valetudo nightly (2022-12-06T02:30:50.473Z)

### Features

- **vendor.roborock**: Add implementations for Roborock S7 auto empty dock [`39207e8`](https://github.com/Hypfer/Valetudo/commit/39207e8b76238d2483fd4592cd6b87db9e00c6b4)
- **vendor.dreame**: D10S Pro [`0939cbd`](https://github.com/Hypfer/Valetudo/commit/0939cbdcf28bb84581b93507c997c5a24ac9bbaa)
- **vendor.viomi**: Introduce ViomiOperationModeControlCapability [`d764438`](https://github.com/Hypfer/Valetudo/commit/d7644388e63d6cd740381f31c04362fdade7f6ad)
- **vendor.viomi**: Add y_mopping quirk [`5ac847f`](https://github.com/Hypfer/Valetudo/commit/5ac847f683419b7da7065f1e4dcc1d7bb0904529)
- **vendor.3ir**: Introduce common 3irobotix map parser [`8f5013a`](https://github.com/Hypfer/Valetudo/commit/8f5013a743a50e168f725372dc9ddc82ec4a332c)
- **vendor.viomi**: Track active segments [`56b0bf6`](https://github.com/Hypfer/Valetudo/commit/56b0bf66da6a0d3cf08e20760bcbfdb4102f7d74)
- **vendor.viomi**: Refactoring, fixes and tests [`7882db4`](https://github.com/Hypfer/Valetudo/commit/7882db41a1912aad028a4d48e60877abf6f6615a)
- **ui**: remove redundant first confirmation dialog for fetching updates [`4d01657`](https://github.com/Hypfer/Valetudo/commit/4d01657e9cf196bda0b44fb3b051853c9fecdf6a)

### Fixes

- **vendor.dreame**: Remove broken operation mode control for W10 and reintroduce mop only quirk [`8b8d7a2`](https://github.com/Hypfer/Valetudo/commit/8b8d7a27b922f0e39fdfd0a52ba082f1ca11820e)
- **vendor.3ir**: Fix segment name block parsing [`99897a5`](https://github.com/Hypfer/Valetudo/commit/99897a5f8c6f1a8cbb1d2695ecd335f2e7db5d0d)
- **vendor.viomi**: Don't raise three events for a single error [`f143319`](https://github.com/Hypfer/Valetudo/commit/f14331978cd2fa5fbb23c53856102b598cc42ef5)
- **ui**: Allow valid slashes in mqtt topic prefix [`1f06b86`](https://github.com/Hypfer/Valetudo/commit/1f06b862bea577c8c22a23243c02d26b8f90c92a)
- **ui**: Fix occasional unexpected scrollbars [`bafdb4d`](https://github.com/Hypfer/Valetudo/commit/bafdb4d606d4f0d3d7d45147cba8570251460fe6)
- **vendor.3ir**: Parse temporary maps [`f43a7ed`](https://github.com/Hypfer/Valetudo/commit/f43a7ed68c17cd9edcecd98396380c67e6d9f9f8)
- **vendor.3ir**: Fix map parser going oom if uniqueMapId is all 0 [`b351686`](https://github.com/Hypfer/Valetudo/commit/b3516867c2530de1ac73a2e97cb768612670f721)
- Add .catch() handler to previously unhandled promises [`db5aeca`](https://github.com/Hypfer/Valetudo/commit/db5aeca526feb7899de43a40d511d3a9b1fdec74)
- **miio**: Protect against invalid Wi-Fi passwords [`4c873b7`](https://github.com/Hypfer/Valetudo/commit/4c873b71827c9bf8830fc30b7a6d6ee4d1aae2ca)
- **mqtt**: Make sure that we only refresh handles while we're connected [`67e66a0`](https://github.com/Hypfer/Valetudo/commit/67e66a0ee38007fbe9a2e9dabedecb525ac9f266)

### Refactoring

- **vendor.3ir**: Minor cleanup [`a151080`](https://github.com/Hypfer/Valetudo/commit/a151080aa072f0d402c2e88830de8e564ff30fac)

### Chores

- **vendor.viomi**: Remove unused map parser [`0c7d757`](https://github.com/Hypfer/Valetudo/commit/0c7d75710a865326e015239375b9a4d03ad0f564)
- minor cleanup [`79229f9`](https://github.com/Hypfer/Valetudo/commit/79229f99f690358488d7f97db1fbe8ee6f4711c5)
- Add hint regarding maps and reboots to the updater [`69b0ae7`](https://github.com/Hypfer/Valetudo/commit/69b0ae7aafb9c3621f7c10d0b3ffbcbbc637bd6b)
