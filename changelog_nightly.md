## Valetudo nightly (2022-10-14T03:05:26.811Z)
### Breaking Changes

- **mqtt**: Provide better error information [`da6994a`](https://github.com/Hypfer/Valetudo/commit/da6994a34de68654a35daf9819936fa20cc12539)

### Features

- **vendor.dreame**: Newer 1C firmwares do seem to support no mop zones [`a06a86d`](https://github.com/Hypfer/Valetudo/commit/a06a86d3e542429232714dc932702bf2a0703c74)
- **vendor.dreame**: Operation mode control [`aefa436`](https://github.com/Hypfer/Valetudo/commit/aefa436dafb590ba13c8d1fd36751d6918d5a93f)
- **vendor.dreame**: D9 Pro+ special edition support [`ffbcb73`](https://github.com/Hypfer/Valetudo/commit/ffbcb736e45ad156be67b8565d1f6e1a9e1c93e0)
- **vendor.dreame**: Mop Stuff [`0081cba`](https://github.com/Hypfer/Valetudo/commit/0081cbaad4be58e3a0d220408f211f013e776cc0)
- **ui**: Allow configuration of optional exposable capabilities for mqtt [`3f31186`](https://github.com/Hypfer/Valetudo/commit/3f31186fd0bf8578252b47dab586525a0b6b1c96)
- **mqtt**: Introduce optional exposed capabilities starting with the SpeakerVolumeControlCapabilityMqttHandle [`685227b`](https://github.com/Hypfer/Valetudo/commit/685227b226505ea669a2a53ef2f70386dee37580)
- **vendor.dreame**: Initial support for the W10 [`6da6556`](https://github.com/Hypfer/Valetudo/commit/6da6556644b145896add18e221c19f5c2b79f082)
- **ui**: Warn the user when attempting to start a full cleanup with a MapAction pending [`bc6a4ce`](https://github.com/Hypfer/Valetudo/commit/bc6a4ce18c542f3f38feeefa273a7a375e502bed)
- **ui**: Add current browser timezone hint to timer timePicker [`892cc09`](https://github.com/Hypfer/Valetudo/commit/892cc096919ce3aca4382497416ce36c62a03749)
- **vendor.dreame**: Automatically dismiss the MopAttachmentReminderValetudoEvent on Mop detachment [`19f96a2`](https://github.com/Hypfer/Valetudo/commit/19f96a2ee09cc690af375995117f997037c77189)
- **mqtt**: Update wrapper image to point to docs microsite [`67f600a`](https://github.com/Hypfer/Valetudo/commit/67f600a4e0f1c3aea67c8a6c968acec2d911ee46)
- **vendor.dreame**: Map some internal error codes [`c9bc1b8`](https://github.com/Hypfer/Valetudo/commit/c9bc1b85e3afdd9d79263ee7fef7c084f3beedf3)
- **vendor.roborock**: Add hardware fault error code mappings [`19ce6aa`](https://github.com/Hypfer/Valetudo/commit/19ce6aad052dbccbb04e9ff539bef0dd5af75937)

### Fixes

- **vendor.dreame**: 1C error codes might occasionally be numbers [`93fdfb9`](https://github.com/Hypfer/Valetudo/commit/93fdfb927f0fbbba1b5eabcc15a3a858d97281d3)
- Hide non-functional Wi-Fi configuration editor if not supported [`fbcfd47`](https://github.com/Hypfer/Valetudo/commit/fbcfd47051af37d17d8de7640adb318620dc8790)
- **vendor.dreame**: Handle carpet information in maps [`d1ad1af`](https://github.com/Hypfer/Valetudo/commit/d1ad1aff916ddce260dbd65f231149c3ae8687fc)
- **ui**: Strip even more characters that home assistant doesn't like from all mqtt topic building blocks [`5877381`](https://github.com/Hypfer/Valetudo/commit/587738132a2d7a5bb4c8b4ca0b60d001f50a550a)
- **vendor.dreame**: Voicepack hash must be lowercase [`0deff82`](https://github.com/Hypfer/Valetudo/commit/0deff822f29962eab2afea92b7e881c31b386397)
- **ui**: Weekday order should be ISO 8601 compliant [`3c884f5`](https://github.com/Hypfer/Valetudo/commit/3c884f58c424f7e173815bc2a1f89bd7bdbdd95f)

### Refactoring

- Misc cleanup [`9fa98df`](https://github.com/Hypfer/Valetudo/commit/9fa98dfdacf478534d944f49471d39c6c0eda95f)

### Chores

- Bump github actions to setup-node@v3 [`4dbb745`](https://github.com/Hypfer/Valetudo/commit/4dbb745e00538f2e3be8d2275413c68230c02701)
- bump upx dependency [`38fb6e4`](https://github.com/Hypfer/Valetudo/commit/38fb6e43eff6b158b1d18e09259910d2341758b0)
- Revert axios bump due to broken builds [`c3de7e5`](https://github.com/Hypfer/Valetudo/commit/c3de7e505b2a9ea3e0323e4131197a34ed0a24fc)
- Bump dependencies [`cefd3a7`](https://github.com/Hypfer/Valetudo/commit/cefd3a77196cc1b151551e3eef910ffe5d99c377)
- **webserver**: Minor data validation cleanup [`263774b`](https://github.com/Hypfer/Valetudo/commit/263774b845d627b6c6c589614a79198a79592f11)
- **vendor.dreame**: Ignore irrelevant POST_CHARGE_CONTINUE update on initial root [`0fdec0c`](https://github.com/Hypfer/Valetudo/commit/0fdec0c7922a1dab2e613e254144a3352ce6c349)
- Docs update [`a96501f`](https://github.com/Hypfer/Valetudo/commit/a96501f972e351ec9f2a7cdab51618bb3c4172bb)
- **mqtt**: Update wrapper image [`cd3b75f`](https://github.com/Hypfer/Valetudo/commit/cd3b75f8550acbba3bfeedda1bc2967adb995881)
