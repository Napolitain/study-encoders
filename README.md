HandBrake 1.5.1 (2022011000)
OS: Microsoft Windows NT 10.0.22621.0
CPU: Intel(R) Core(TM) i7-9700K CPU @ 3.60GHz
Ram: 32713 MB
GPU Information: NVIDIA GeForce RTX 2070 - 30.0.15.1179

Encoding 4K 24 FPS advertising low motion movie to 3 Mbps VBR.
| movie.mkv (24 FPS)      | speed (FPS) | size (MB) | PSNR  | VMAF  |
|-------------------------|------------:|----------:|------:|------:|
| original                |             | 960.0     |       |       |
| x264 - 9700k 32GB       | 17.96       | 57.6      | 40.43 |       |
| x265 - 9700k 32GB       | 4.60        | 57.6      | 41.36 |       |
| libvpx_vp9 - 9700k 32GB | 1.28        | 57.5      | 42.27 |       |
| svtav1 - 9700k 32GB     | 4.??        | 57.4      | 42.85 |       |
| NVENC H.265 - RTX 2070  | 28.88       | 60.3      | 41.24 |       |
| VideoToolbox H.264 - T2 | 22.62       | 61.2      | 37.41 | 77.58 |
| VideoToolbox H.265 - T2 | 24.19       | 60.8      | 38.98 | 77.58 |
| VideoToolbox H.265 - M1 |             |           |       |       |


Encoding 4K 24 FPS advertising low motion movie to 5 Mbps VBR.
| movie.mkv (24 FPS)      | speed (FPS) | size (MB) | PSNR  | VMAF  |
|-------------------------|------------:|----------:|------:|------:|
| original                |             | 960.0     |       |       |
| x265 - 9700k 32GB       | 4.60        | 96.0      | 42.88 | 90.83 |
| NVENC H.265 - RTX 2070  | 28.88       | 100.0     | 42.62 | 89.40 |
| VideoToolbox H.265 - T2 | 24.19       | 101.0     | 40.97 | 85.29 |
| VideoToolbox H.265 - M1 |             |           |       |       |


Encoding 4K 24 FPS advertising low motion movie to 8 Mbps VBR.
| movie.mkv (24 FPS)      | speed (FPS) | size (MB) | PSNR  | VMAF  |
|-------------------------|------------:|----------:|------:|------:|
| original                |             | 960.0     |       |       |
| x265 - 9700k 32GB       |             |           |       |       |
| NVENC H.265 - RTX 2070  |             |           |       |       |
| VideoToolbox H.265 - T2 |             | 161.6     | 41.53 | 86.75 |
| VideoToolbox H.265 - M1 |             |           |       |       |

Encoding 4K 24 FPS advertising low motion movie to 14 Mbps VBR.
| movie.mkv (24 FPS)      | speed (FPS) | size (MB) | PSNR  | VMAF  |
|-------------------------|------------:|----------:|------:|------:|
| original                |             | 960.0     |       |       |
| x265 - 9700k  32GB      |             |           |       |       |
| NVENC H.265 - RTX 2070  |             |           |       |       |
| VideoToolbox H.265 - T2 | 27.66       | 281.5     | 43.96 | 91.90 |
| VideoToolbox H.265 - M1 |             |           |       |       |
