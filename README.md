HandBrake 1.5.1 (2022011000)
OS: Microsoft Windows NT 10.0.22621.0
CPU: Intel(R) Core(TM) i7-9700K CPU @ 3.60GHz
Ram: 32713 MB
GPU Information: NVIDIA GeForce RTX 2070 - 30.0.15.1179

Encoding 4K 24 FPS advertising low motion movie to 3 Kbps VBR.
| movie.mkv (24 FPS) | speed (FPS) | size (MB) | PSNR  | VMAF  |
|--------------------|-------------|-----------|-------|-------|
| original           |             | 960       |       |       |
| x265               | 4.60        |           |       |       |
| NVENC2 H.265       | 28.88       |           |       |       |
| VideoToolbox H.265 |             | 60.8      | 38.98 | 77.58 |
| 

Encoding 4K 24 FPS advertising low motion movie to 5 Kbps VBR.
| movie.mkv (24 FPS) | speed (FPS) | size (MB) | PSNR  | VMAF  |
|--------------------|-------------|-----------|-------|-------|
| original           |             | 960       |       |       |
| x265               | 4.60        | 96        | 42.88 | 90.83 |
| NVENC2 H.265       | 28.88       | 100       | 42.62 | 89.40 |
| VideoToolbox H.265 | 24.19       | 101       | 40.97 | 85.29 |


| movie.mkv (24 FPS) | speed (FPS) | size (MB) | PSNR | VMAF  |
|--------------------|-------------|-----------|------|-------|
| original           |             | 960       |      |       |
| x265               | 4.60        | 235       |      | 94.29 |
| NVENC2 H.265       | 28.88       | 330       |      | 93.71 |
| VideoToolbox H.265 |             |           |      |       |
