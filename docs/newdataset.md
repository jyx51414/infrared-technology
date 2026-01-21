---
layout: default
title: Datasets
---

# 数据集
---
## Dataset Comparison (Updated Task Categories)

| 数据集简称 | 任务 | 图像数量 | 分辨率 | 是否有配对数据（可见光、红外） |
|---|---|---|---|---|
| KAIST | 目标检测，融合 | 95k | 640×480 | 是 |
| GTOT | 视频目标跟踪 | 50 | Various | 未找到 |
| MS | 视频目标跟踪 | 2999 | RGB/FIR: 640×480；MIR/NIR: 320×256 | 未找到 |
| MFNet | 语义分割 | 1569 | 640×480 | 未找到 |
| CATS | 立体匹配，3D重建 | 1400 | Various | 是 |
| VT1000 | 显著目标检测 | 1000 | Various | 是 |
| RGBT234 | 单目标跟踪 | 234 | Various | 未找到 |
| LSOTB | 单目标跟踪 | 1400 | Various | 未找到 |
| PST900 | 语义分割 | 894 | Various | 未找到 |
| Freiburg Thermal | 语义分割 | 20647 | Various | 是 |
| DroneRGBT | 人群计数，密度图估计，模态生成 | 3600 | 512×640 | 是 |
| SIRST | 小目标检测 | 427 | Various | 否 |
| LLVIP | 图像融合，行人检测，模态生成 | 16836 | 1280×720 | 是 |
| RGBT-CC | 人群计数，密度图估计 | 2030 | 640×480 | 是 |
| LasHeR | 单目标跟踪 | 1224 | Various | 未找到 |
| SBTI | 去模糊 | 49000 | 640×480 | 否 |
| SIRST V2 | 小目标检测 | 1024 | Various | 否 |
| IRSTD-1K | 小目标检测 | 1000 | 512×512 | 否 |
| NUDT-SIRST | 小目标检测 | 1327 | 256×256 | 否 |
| VTUAV | 单目标跟踪，分割 | 500 sequences；1,664,549 RGB-T frame pairs | 1920×1080 | 是 |
| UTUAV | 未找到 | 未找到 | 未找到 | 未找到 |
| DroneVehicle | 目标检测 | 28439 | Various | 是 |
| M3FD | 图像融合，目标检测 | 4200 | 1024×768 | 是 |
| ViViD | 建图、定位 | 36 | Various | 未找到 |
| VT5000 | 显著目标检测 | 5000 | Various | 是 |
| UIRD | 去模糊 | 30k | Various | 否 |
| IST-A | 小目标检测 | 74309 | 288×384 | 否 |
| SIRST-Aug | 小目标检测 | 9070 | 256×256 | 否 |
| IRDST | 小目标检测 | 142,727 | Various | 否 |
| HIT-UAV | 目标检测 | 2898 | 640×512 | 未找到 |
| FMB | 图像融合、语义分割 | 1500 | 800×600 | 是 |
| SemanticRT | 语义分割 | 11371 | Various | 是 |
| MS2 | 深度估计（单目/双目） | 195k | Various | 未找到 |
| TIVID | 视频/去噪 | 518 | 320×256 | 否 |
| ODinMJ | 目标检测 | 23075 | 640×512 | 是 |
| RGBT-Tiny | 小目标检测，融合、检测与跟踪 | 115 paired sequences；93K frame pairs | 640×512 | 是 |
| HM-TIR | 图像增强 | 1503 | 640×512 | 否 |
| NATO SET-140 | 去噪/对比度增强 | various | Various | 否 |
| CASIA Interval v3 | 超分 | 2655 | 320×280 | 否 |
| ULB17-VT | 可见光生红外/超分 | 404 pairs | 320×240 | 是 |
| IR-COLOR2000 | 可见光生红外/超分 | 2000 pairs | Various | 是 |
| IR100 | 超分 | 100 | 640×480 | 否 |
| CVC-09 | 超分 | 11,071 frames | 640×480 | 否 |
| Rivadeneira et al. | 超分 | 1021 images | Various | 否 |
| CDN-MRF | 超分 | 20 | Various | 否 |
| IRBFD
IRBFD-syn and IRBFD-real. | 非均匀性校正（NUC）+ 红外 UAV 目标检测 | 未找到 | 未找到 | 未找到 |

---

**说明**
- `任务`：严格按照 `数据集最新.xlsx` 的分类。
- `图像数量 / 分辨率 / 是否有配对数据`：从原 `dataset.md` 对应条目提取；若在原文件中未检索到对应数据集或字段，则填 `未找到`。
