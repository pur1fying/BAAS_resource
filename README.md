# BAAS_resource

Runtime resource assets for [BAAS_Cpp](https://github.com/pur1fying/BAAS_Cpp), including pinned scrcpy server, Android Debug Bridge binaries, PaddleOCR models, and YOLO ONNX models.

## Release Overview

| Resource | Release tag | Version | Assets | Status |
|---|---|---|---:|---|
| scrcpy server | [`scrcpy-server-v2.4`](https://github.com/pur1fying/BAAS_resource/releases/tag/scrcpy-server-v2.4) | `2.4` | 1 | Published |
| Android Debug Bridge | [`adb-platform-tools-v36.0.0-13206524`](https://github.com/pur1fying/BAAS_resource/releases/tag/adb-platform-tools-v36.0.0-13206524) | `36.0.0-13206524` | 3 | Published |
| PaddleOCR models | [`ocr_models-v1.0.0`](https://github.com/pur1fying/BAAS_resource/releases/tag/ocr_models-v1.0.0) | `1.0.0` | 1 | Published |
| YOLO ONNX models | [`yolo_models-v1.0.0`](https://github.com/pur1fying/BAAS_resource/releases/tag/yolo_models-v1.0.0) | `1.0.0` | 1 | Published |

## Release Assets

| Release tag | Asset | Size | SHA256 |
|---|---|---:|---|
| `scrcpy-server-v2.4` | `scrcpy-server.jar` | 67.39 KiB | `93c272b7438605c055e127f7444064ed78fa9ca49f81156777fd201e79ce7ba3` |
| `adb-platform-tools-v36.0.0-13206524` | `adb-platform-tools-windows-v36.0.0-13206524.zip` | 3.14 MiB | `312d1710b39dd99f7296968e5a74113f1c3154af6365c72f3fa67531de1ceb5a` |
| `adb-platform-tools-v36.0.0-13206524` | `adb-platform-tools-macos-v36.0.0-13206524.zip` | 6.35 MiB | `fedebe0e75bfb998660c925f83d256d6f8d5e61d549611dcaa11795d784dd46e` |
| `adb-platform-tools-v36.0.0-13206524` | `adb-platform-tools-linux-v36.0.0-13206524.zip` | 3.37 MiB | `cdbb11a634d026a6f0acba42eab0c3f5b91b740f9ed69682de40fb54d6abba24` |
| `ocr_models-v1.0.0` | `ocr_models-v1.0.0.zip` | 68.07 MiB | `a76777222e83b3ca2bfb793a2634f5b69b1123dcf770d797391eac04c3cca1a5` |
| `yolo_models-v1.0.0` | `yolo_models-v1.0.0.zip` | 15.26 MiB | `a68cfa9c053ebc92c7003cd6d6d23c49723a987bdd58f016d4b7993b2c13eff6` |

## Notes

- Releases are split by resource lifecycle so models, ADB binaries, and scrcpy server can be updated independently.
- Asset URLs and SHA256 values should be mirrored into `BAAS_Cpp/resources.lock.json`.
