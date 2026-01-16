---
layout: default
title: Dataset Catalog
---

# 数据集展示说明

本页汇总了 **46** 个与红外/多光谱相关的数据集条目（含任务类型、来源、链接与简介）。

---

## 1. 概览

- **条目数量**：46
- **字段说明**
  - **任务**：数据集主要面向的任务/用途（例如：可见光生红外、视频跟踪、超分、去噪等）
  - **出处**：论文/会议/期刊或发布来源
  - **网址**：论文、项目页或数据集主页链接

---

## 2. 统计

### 2.1 任务类型 Top（按“任务”字段拆分统计）

- **视频**：21
- **可见光生红外**：17
- **超分**：7
- **去噪**：5
- **图像检测**：2
- **对比度增强**：2
- **未标注**：1
- **深度估计**：1
- **立体匹配**：1
- **视差估计**：1
- **语义分割**：1

---

## 3. 数据集列表（适合快速浏览）

> 表格中的“描述”做了截断，完整描述见下一节。

| 任务                                           | 数据集名字         | 出处                | 网址                                                                                                                                                                                                                                                                | 描述(简)                                                                                                                                                       |
|:-----------------------------------------------|:-------------------|:--------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 可见光生红外                                   | KAIST              | CVPR 2015           | https://openaccess.thecvf.com/content_cvpr_2015/papers/Hwang_Multispectral_Pedestrian_Detection_2015_CVPR_paper.pdf                                                                                                                                                 | 多光谱行人检测基准数据集，包含 RGB 彩色图像和红外图像两种版本，适用于行人检测和属性分析等任务                                                                  |
| 视频                                           | GTOT               | TIP 2016            | https://github.com/xuboyue1999/RGBT-Tracking/blob/main/datasets/GTOT/gtot.md                                                                                                                                                                                        | 50对视频，均为灰度和热红外图像序列，每对均存在统计偏差。此外，数据集还包含视频每一帧的真实注释和两个评估指标                                                   |
| 视频/图像检测                                  | MS                 | 2017 ACM MM         | https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/                                                                                                                                                                                                   | 多光谱 目标检测                                                                                                                                                |
| 语义分割                                       | MFNet              | 2017 IROS           | https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/                                                                                                                                                                                                   | RGB-Thermal（RGB+热红外）语义分割（Semantic Segmentation）                                                                                                     |
| 可见光生红外<br>立体匹配 / 视差估计 / 深度估计 | CATS               | 2017 CVPR           | https://openaccess.thecvf.com/content_cvpr_2017/html/Treible_CATS_A_Color_CVPR_2017_paper.html                                                                                                                                                                      | 双目可见光,双目热红外,跨模态（color↔thermal）成对图像                                                                                                          |
| 可见光生红外                                   | VT1000             | 2019 TMM            | https://arxiv.org/pdf/1905.06741.pdf<br>https://chenglongli.cn/_code-dataset/dataset                                                                                                                                                                                | 1000 对高对齐的 RGB 与热红外图像以及对应的显著性 GT 标注                                                                                                       |
| 视频                                           | RGBT234            | 2019 PR             | https://doi.org/10.1016/j.patcog.2019.106977                                                                                                                                                                                                                        | 234 对严格对齐的 RGB-T 视频序列（总帧数约 234K，单序列最长可达 8K 帧），跨模态对齐精度高到“不需要任何预处理或后处理”，并对每一帧在两种模…                      |
| 视频                                           | LSOTB              | 2020 ACM MM         | https://arxiv.org/abs/2008.00836                                                                                                                                                                                                                                    | 总规模约 1,400 段 TIR 序列、60 万帧以上，并对所有序列逐帧标注目标边界框                                                                                        |
| 可见光生红外                                   | PST900             | 2020 ICRA           | https://arxiv.org/abs/1909.10980                                                                                                                                                                                                                                    | 894 对同步采集且完成标定对齐的 RGB 与热红外图像构成，并提供像素级人工标注                                                                                      |
| 可见光生红外/视频                              | Freiburg Thermal   | 2020 IROS           | https://arxiv.org/abs/2003.04645                                                                                                                                                                                                                                    | 面向城市道路场景的 RGB–热红外（thermal infrared）多模态数据集，时间同步且对齐的 RGB 与热红外图像对                                                             |
| 可见光生红外                                   | DroneRGBT          | 2020 ACCV           | https://openaccess.thecvf.com/content/ACCV2020/papers/Peng_RGB-T_Crowd_Counting_from_Drone_A_Benchmark_and_MMCCN_Network_ACCV_2020_paper.pdf                                                                                                                        | 无人机视角的 RGB–Thermal人群计数基准数据集，由 3600 对对齐的 RGB 与热红外图像对构成                                                                            |
| 视频/图像检测                                  | SIRST              | 2021 WACV           | https://openaccess.thecvf.com/content/WACV2021/papers/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.pdf                                                                                                                  | 单帧红外弱小目标检测,从大量红外序列中挑选具有代表性的帧以覆盖不同场景背景，并提供可用于检测与分割的标注形式                                                    |
| 可见光生红外                                   | LLVIP              | 2021 ICCVW          | https://openaccess.thecvf.com/content/ICCV2021W/RLQ/papers/Jia_LLVIP_A_Visible-Infrared_Paired_Dataset_for_Low-Light_Vision_ICCVW_2021_paper.pdf                                                                                                                    | 面向低照度视觉的可见光–红外（VIS–IR）严格配对数据集,在“非常暗”的真实场景中采集的可见光与红外图像组成，并强调两模态在时间与空间上严格对齐，同时提供行…          |
| 可见光生红外                                   | RGBT-CC            | 2021 CVPR           | https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578312                                                                                                                                                                                                    | 面向 RGB-T（可见光 RGB + 热红外 thermal）人群计数的大规模基准数据集，作者在论文中说明它由 2,030 对分辨率为 640×480 的 R…                                       |
| 视频                                           | LasHeR             | 2021 TIP            | https://arxiv.org/abs/2104.13202                                                                                                                                                                                                                                    | 包含 1224 对对齐的可见光-热红外视频序列、总计 73万+帧对，对每一帧提供人工标注边界框                                                                            |
| 去噪                                           | SBTI               | 2022 Sensors        | https://doi.org/10.3390/s22051893                                                                                                                                                                                                                                   | 由作者采集的真实热红外清晰图像出发，结合他们提出的、面向热探测器成像机理的运动模糊模型与惯性传感器信息来合成不同强度的模糊热图像，从而形成“模糊图像—清晰真值…  |
| 视频                                           | SIRST V2           | 2022 JSTARS         | https://arxiv.org/abs/2212.08472                                                                                                                                                                                                                                    | 旨在覆盖复杂背景下更具挑战性的红外小目标，同时提供多种标注/监督形式以支持不同建模方式，作者将它与归一化对比度指标及 DeepInfrared 工具链一起作为…               |
| 视频                                           | IRSTD-1K           | 2022 CVPR           | https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_ISNet_Shape_Matters_for_Infrared_Small_Target_Detection_CVPR_2022_paper.html                                                                                                                              | 从真实场景中收集了约 1000 张具有多样目标形状、不同目标尺度以及复杂杂波背景的红外图像，并为每个小目标提供精确的像素级掩膜标注，目的是在长期缺少大规模真实…      |
| 视频                                           | NUDT-SIRST         | 2022 TIP            | https://arxiv.org/abs/2106.00487                                                                                                                                                                                                                                    | 合成（synthesized）数据集，包含 1327 张 256×256 的红外图像，并强调合成方式带来的优势在于标注更精确、生成成本更低且可覆盖更多目标类别…                          |
| 视频                                           | VTUAV              | 2022 CVPR           | https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Visible-Thermal_UAV_Tracking_A_Large-Scale_Benchmark_and_New_Baseline_CVPR_2022_paper.pdf                                                                                                               | 面向可见光-热红外（RGB-T）无人机目标跟踪的大规模基准数据集，作者在论文与项目页中说明其包含 500 段序列、约 170 万对严格配准的高分辨率（1920…                    |
| 视频                                           | UTUAV              |                     | https://www.mdpi.com/2504-446X/10/1/15                                                                                                                                                                                                                              | 支持 UAV 车流场景下的车辆检测研究，数据采自哥伦比亚麦德林（Medellín）的街道路段，重点覆盖当地交通组成中占比很高的摩托车等小目标，并以高分辨率视频…             |
| 可见光生红外                                   | DroneVehicle       | 2022 TCSVT          | https://doi.org/10.1109/TCSVT.2022.3168279                                                                                                                                                                                                                          | 为缓解低照度等复杂条件下单一模态检测困难的问题，采集并标注了大规模的成对 RGB 与红外航拍图像数据，数据覆盖从白天到夜晚的多种场景（如城市道路、居民区、停车…     |
| 可见光生红外                                   | M3FD               | 2022 CVPR           | https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Target-Aware_Dual_Adversarial_Learning_and_a_Multi-Scenario_Multi-Modality_Benchmark_To_CVPR_2022_paper.pdf                                                                                               | 用同步标定良好的可见光与红外传感器采集的多场景多模态（可见光–红外）对齐图像对数据集，作者在官方仓库说明其主要用于融合与检测相关实验，包含用于融合/检测/融合…   |
| 视频                                           | ViViD              | 2022 RAL            | https://arxiv.org/pdf/2204.06183v2                                                                                                                                                                                                                                  | 面向低能见度/光照剧烈变化条件下机器人视觉与 SLAM 的多传感器同步数据集，作者将传感器系统配置为手持与车载两种平台，在同一空间中反复采集以覆盖从白天到夜晚…       |
| 可见光生红外                                   | VT5000             | 2022 TMM            | https://doi.org/10.1109/TMM.2022.3171688                                                                                                                                                                                                                            | 面向 RGB-T（可见光 RGB + 热红外 TIR）显著性目标检测的大规模成对数据集，论文中作者明确指出他们构建了名为 VT5000 的数据集，包含 500…                             |
| 去噪                                           | UIRD               | 2022 IEEE Sen.      | https://doi.org/10.1109/JSEN.2023.3327413                                                                                                                                                                                                                           | 面向非制冷微测辐射热计（microbolometer）热红外相机运动去模糊任务构建的大规模基准数据集，作者指出其反映了非制冷红外成像特有的模糊累积特性，数据由…              |
| 视频                                           | IST-A              | 2023 TGRS           | https://doi.org/10.1109/TGRS.2023.3269092                                                                                                                                                                                                                           | 面向红外小目标检测的真实采集数据集，所有图像大小为 288×384，目标主要是远距离天空中的 鸟、无人机、直升机、飞机等非合作目标（也包含大量地面背景如植被、…         |
| 视频                                           | SIRST-Aug          | 2023 TAES           | https://doi.org/10.1109/TAES.2023.3238703                                                                                                                                                                                                                           | 让 SIRST 更适合训练深度网络并增强模型在复杂背景下检测微弱小目标的能力，因此他们将扩增后的数据作为与 MDFA 并列的公开基准来做对比实验与消融分析，并…             |
| 视频                                           | IRDST              | 2023 TGRS           | https://doi.org/10.1109/TGRS.2023.3235150                                                                                                                                                                                                                           | 每一帧都同时提供从细到粗的三种标注形式（像素级掩膜、目标框、中心点），并在数据集页面明确给出了真实/仿真数据的目录组织方式以及不同标注文件（masks/box…          |
| 视频                                           | HIT-UAV            | 2023 SD             | https://www.nature.com/articles/s41597-023-02066-6                                                                                                                                                                                                                  | 面向无人机高空视角的热红外目标检测数据集，并为每张图像提供飞行高度、相机视角、日期与日光强度等飞行/采集信息，同时为目标实例提供两种形式的人工框标注以应对航拍… |
| 可见光生红外                                   | FMB                | 2023 ICCV           | https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_Multi-interactive_Feature_Learning_and_a_Full-time_Multi-modality_Benchmark_for_Image_ICCV_2023_paper.pdf                                                                                                 | 通过标定与单应性估计将红外投影到可见光坐标并裁剪，最终得到 1500 对像素级严格配准的红外–可见光图像对，分辨率为 800×600；数据覆盖不同照明条件下的…               |
| 可见光生红外                                   | SemanticRT         | 2023 ACM MM         | https://doi.org/10.1145/3581783.3611738                                                                                                                                                                                                                             | 面向多光谱语义分割（Multispectral Semantic Segmentation, MSS）的大规模 RGB–热红外数据集                                                                        |
| 视频/可见光生红外                              | MS2                | 2023 CVPR           | https://openaccess.thecvf.com/content/CVPR2023/papers/Shin_Deep_Depth_Estimation_From_Thermal_Image_CVPR_2023_paper.pdf                                                                                                                                             | 面向户外驾驶场景的多光谱立体数据集，官方主页说明它提供校正并同步的立体 RGB、立体 NIR、立体热红外图像，以及同步的立体 LiDAR、GPS/IMU 导航…                      |
| 视频/去噪                                      | TIVID              | 2024 TIP            | https://ieeexplore.ieee.org/document/10507231                                                                                                                                                                                                                       | 面向热红外视频去噪的专用数据集/基准，作者在官方仓库中将其作为三大贡献之一，与“物理启发的噪声生成器”和去噪网络（MDIVDnet）配套使用；其组织方式按训练…           |
| 可见光生红外                                   | ODinMJ             | 2024 GRSM           | https://doi.org/10.1109/MGRS.2024.3492069                                                                                                                                                                                                                           | 用于山地丛林场景 RGB-T 目标检测的配对数据集，作者先采集了超过 6 万对 RGB-T 图像对并进行严格人工筛选与预处理，最终提供分辨率为 640×512…                         |
| 视频                                           | RGBT-Tiny          | 2025 TPAMI          | https://arxiv.org/abs/2406.14482                                                                                                                                                                                                                                    | 面向 RGB-T 微小目标检测的大规模基准数据集，覆盖 7 类目标与 8 类场景，其中 超过 81% 的目标尺寸小于 16×16；数据提供可见光与热红外两模态…                         |
| 对比度增强/去噪                                | HM-TIR             | 2025 NeurIPS        | https://openreview.net/forum?id=yEddfz9SgJ                                                                                                                                                                                                                          | 建立了一个覆盖多种环境与视角的高质量 TIR 数据集，包含 1503 张清晰聚焦的 TIR 图像，同时在官方代码仓库中提供了与这些清晰图像配套的退化版本，用于…                |
|                                                |                    |                     |                                                                                                                                                                                                                                                                     |                                                                                                                                                                |
| 去噪/对比度增强                                | NATO SET-140       | 2012 SPIE           | https://publications.tno.nl/publication/102842/oSh1Fo/weiss-2012-standard.pdf                                                                                                                                                                                       | 评测 超分（SR）、对比度增强/动态范围压缩（CE/DRC）、场景非均匀校正（SB-NUC）以及 MWIR/LWIR 融合等算法表现。                                                    |
| 超分                                           | CASIA Interval v3  | 2016 IA-CAS         | 数据集：https://hycasia.github.io/dataset/                                                                                                                                                                                                                          | 这是近红外（NIR）虹膜图像子集，包含约2655张、320×280分辨率的灰度虹膜图像，来自249名受试者，多用于虹膜识别与分割研究；如果用于超分，通常是把原…                 |
| 可见光生红外/超分                              | ULB17-VT           | 2018 ACCV workshorp | https://link.springer.com/chapter/10.1007/978-3-030-21074-8_28                                                                                                                                                                                                      | 这是一个手工抽取并标注的可见光-热红外配对数据集（文献中常写为约570对），适用于研究“多模态传感器融合”场景下的热红外超分或重建，即利用可见光的高频细节特征…      |
| 可见光生红外/超分                              | IR-COLOR2000       | 2020 Sensors        | https://www.mdpi.com/1424-8220/20/1/281                                                                                                                                                                                                                             | 该数据集由论文作者采集，核心是成对的RGB与IR同场景图像（论文中用作训练与评测），用于研究“RGB与IR联合输入/特征融合”来提升红外超分重建质量，同时通过…             |
| 超分                                           | IR100              | 2021 IEEE           | https://doi.org/10.1109/LSP.2021.3077801                                                                                                                                                                                                                            | 指一个规模约100张的红外图像测试集，用法通常是把原始红外图像当作参考，再按×2/×4/×8等倍率下采样得到输入LR，从而评测重建的PSNR/SSIM等指标                         |
| 超分/视频                                      | CVC-09             | 2013 ICCV           | Socarras, Y.; Ramos, S.; Vázquez, D.; López, A.; Gevers, T. Adapting Pedestrian Detection from Synthetic to Far Infrared Images.<br>In Proceedings of the ICCV Workshop on Visual Domain Adaptation and Dataset Bias (VisDA), Sydney, Australia, 7 December<br>2013 | 指从CVC-09热红外行人序列中随机抽取约1000帧构成的子集，用于红外SR等低层任务时再进一步通过下采样合成LR/HR对                                                      |
| 超分                                           | Rivadeneira et al. | 2022 VISAPP         | https://refbase.cvc.uab.es/files/RSV2020.pdf                                                                                                                                                                                                                        | 提出热红外超分方法并配套构建数据集，核心思路是用不同分辨率热红外传感器（文献与后续挑战常提到包含Tau2等设备采集）在尽量同步与可配准的条件下获取同场景数据，…    |
| 超分                                           | CDN-MRF            | 2019 IEEE           | https://doi.org/10.1109/TCSVT.2018.2864777                                                                                                                                                                                                                          | 一篇红外单帧SR方法及其配套实验数据设置，文献/代码常使用“真实红外图像”并通过下采样生成LR/HR对进行训练与评测                                                     |

---

## 4. 逐条详情

<details>
<summary>点击展开/收起完整条目</summary>

### 1. KAIST

- **任务**：可见光生红外
- **出处**：CVPR 2015
- **链接**：https://openaccess.thecvf.com/content_cvpr_2015/papers/Hwang_Multispectral_Pedestrian_Detection_2015_CVPR_paper.pdf

**描述**：多光谱行人检测基准数据集，包含 RGB 彩色图像和红外图像两种版本，适用于行人检测和属性分析等任务


### 2. GTOT

- **任务**：视频
- **出处**：TIP 2016
- **链接**：https://github.com/xuboyue1999/RGBT-Tracking/blob/main/datasets/GTOT/gtot.md

**描述**：50对视频，均为灰度和热红外图像序列，每对均存在统计偏差。此外，数据集还包含视频每一帧的真实注释和两个评估指标


### 3. MS

- **任务**：视频/图像检测
- **出处**：2017 ACM MM
- **链接**：https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/

**描述**：多光谱 目标检测


### 4. MFNet

- **任务**：语义分割
- **出处**：2017 IROS
- **链接**：https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/

**描述**：RGB-Thermal（RGB+热红外）语义分割（Semantic Segmentation）


### 5. CATS

- **任务**：可见光生红外
立体匹配 / 视差估计 / 深度估计
- **出处**：2017 CVPR
- **链接**：https://openaccess.thecvf.com/content_cvpr_2017/html/Treible_CATS_A_Color_CVPR_2017_paper.html

**描述**：双目可见光,双目热红外,跨模态（color↔thermal）成对图像


### 6. VT1000

- **任务**：可见光生红外
- **出处**：2019 TMM
- **链接**：https://arxiv.org/pdf/1905.06741.pdf
https://chenglongli.cn/_code-dataset/dataset

**描述**：1000 对高对齐的 RGB 与热红外图像以及对应的显著性 GT 标注


### 7. RGBT234

- **任务**：视频
- **出处**：2019 PR
- **链接**：https://doi.org/10.1016/j.patcog.2019.106977

**描述**：234 对严格对齐的 RGB-T 视频序列（总帧数约 234K，单序列最长可达 8K 帧），跨模态对齐精度高到“不需要任何预处理或后处理”，并对每一帧在两种模态上都提供覆盖目标的最小外接框标注，同时额外标注了遮挡程度以支持遮挡敏感分析


### 8. LSOTB

- **任务**：视频
- **出处**：2020 ACM MM
- **链接**：https://arxiv.org/abs/2008.00836

**描述**：总规模约 1,400 段 TIR 序列、60 万帧以上，并对所有序列逐帧标注目标边界框


### 9. PST900

- **任务**：可见光生红外
- **出处**：2020 ICRA
- **链接**：https://arxiv.org/abs/1909.10980

**描述**：894 对同步采集且完成标定对齐的 RGB 与热红外图像构成，并提供像素级人工标注


### 10. Freiburg Thermal

- **任务**：可见光生红外/视频
- **出处**：2020 IROS
- **链接**：https://arxiv.org/abs/2003.04645

**描述**：面向城市道路场景的 RGB–热红外（thermal infrared）多模态数据集，时间同步且对齐的 RGB 与热红外图像对


### 11. DroneRGBT

- **任务**：可见光生红外
- **出处**：2020 ACCV
- **链接**：https://openaccess.thecvf.com/content/ACCV2020/papers/Peng_RGB-T_Crowd_Counting_from_Drone_A_Benchmark_and_MMCCN_Network_ACCV_2020_paper.pdf

**描述**：无人机视角的 RGB–Thermal人群计数基准数据集，由 3600 对对齐的 RGB 与热红外图像对构成


### 12. SIRST

- **任务**：视频/图像检测
- **出处**：2021 WACV
- **链接**：https://openaccess.thecvf.com/content/WACV2021/papers/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.pdf

**描述**：单帧红外弱小目标检测,从大量红外序列中挑选具有代表性的帧以覆盖不同场景背景，并提供可用于检测与分割的标注形式


### 13. LLVIP

- **任务**：可见光生红外
- **出处**：2021 ICCVW
- **链接**：https://openaccess.thecvf.com/content/ICCV2021W/RLQ/papers/Jia_LLVIP_A_Visible-Infrared_Paired_Dataset_for_Low-Light_Vision_ICCVW_2021_paper.pdf

**描述**：面向低照度视觉的可见光–红外（VIS–IR）严格配对数据集,在“非常暗”的真实场景中采集的可见光与红外图像组成，并强调两模态在时间与空间上严格对齐，同时提供行人标注


### 14. RGBT-CC

- **任务**：可见光生红外
- **出处**：2021 CVPR
- **链接**：https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9578312

**描述**：面向 RGB-T（可见光 RGB + 热红外 thermal）人群计数的大规模基准数据集，作者在论文中说明它由 2,030 对分辨率为 640×480 的 RGB–thermal 图像组成，覆盖商场、街道、车站等多种城市场景并同时包含明亮与黑暗光照条件，数据集中共对 138,389 名行人做了点标注以支持密度图监督与计数评测


### 15. LasHeR

- **任务**：视频
- **出处**：2021 TIP
- **链接**：https://arxiv.org/abs/2104.13202

**描述**：包含 1224 对对齐的可见光-热红外视频序列、总计 73万+帧对，对每一帧提供人工标注边界框


### 16. SBTI

- **任务**：去噪
- **出处**：2022 Sensors
- **链接**：https://doi.org/10.3390/s22051893

**描述**：由作者采集的真实热红外清晰图像出发，结合他们提出的、面向热探测器成像机理的运动模糊模型与惯性传感器信息来合成不同强度的模糊热图像，从而形成“模糊图像—清晰真值（GT）”成对数据，并被用来以 PSNR/SSIM 等指标对热红外去模糊方法做定量评测；论文同时提到他们也采集了真实模糊热图像用于更贴近实际场景的定性验证。


### 17. SIRST V2

- **任务**：视频
- **出处**：2022 JSTARS
- **链接**：https://arxiv.org/abs/2212.08472

**描述**：旨在覆盖复杂背景下更具挑战性的红外小目标，同时提供多种标注/监督形式以支持不同建模方式，作者将它与归一化对比度指标及 DeepInfrared 工具链一起作为一个完整 benchmark 推动红外小目标检测研究


### 18. IRSTD-1K

- **任务**：视频
- **出处**：2022 CVPR
- **链接**：https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_ISNet_Shape_Matters_for_Infrared_Small_Target_Detection_CVPR_2022_paper.html

**描述**：从真实场景中收集了约 1000 张具有多样目标形状、不同目标尺度以及复杂杂波背景的红外图像，并为每个小目标提供精确的像素级掩膜标注，目的是在长期缺少大规模真实标注数据的背景下，为红外小目标检测方法提供更具代表性和可量化比较的训练/评测基准。


### 19. NUDT-SIRST

- **任务**：视频
- **出处**：2022 TIP
- **链接**：https://arxiv.org/abs/2106.00487

**描述**：合成（synthesized）数据集，包含 1327 张 256×256 的红外图像，并强调合成方式带来的优势在于标注更精确、生成成本更低且可覆盖更多目标类别/尺寸与多样杂波背景，从而用于系统评测单帧红外小目标检测算法的鲁棒性与泛化能力


### 20. VTUAV

- **任务**：视频
- **出处**：2022 CVPR
- **链接**：https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Visible-Thermal_UAV_Tracking_A_Large-Scale_Benchmark_and_New_Baseline_CVPR_2022_paper.pdf

**描述**：面向可见光-热红外（RGB-T）无人机目标跟踪的大规模基准数据集，作者在论文与项目页中说明其包含 500 段序列、约 170 万对严格配准的高分辨率（1920×1080）RGB-T 帧对，并围绕无人机视角下的多类别、多场景与多挑战属性来构建评测，除了常规短期/长期跟踪评估外，还考虑了更全面的应用设置（例如掩膜预测等），同时论文给出了一个新的 RGB-T 跟踪基线 HMFT 用于展示两模态融合带来的收益。


### 21. UTUAV

- **任务**：视频
- **出处**：
- **链接**：https://www.mdpi.com/2504-446X/10/1/15

**描述**：支持 UAV 车流场景下的车辆检测研究，数据采自哥伦比亚麦德林（Medellín）的街道路段，重点覆盖当地交通组成中占比很高的摩托车等小目标，并以高分辨率视频抽帧进行人工标注（车辆类别以摩托车/普通车辆/大型车辆为核心），以反映“Global South”城市交通的真实分布与遮挡、密集等难点


### 22. DroneVehicle

- **任务**：可见光生红外
- **出处**：2022 TCSVT
- **链接**：https://doi.org/10.1109/TCSVT.2022.3168279

**描述**：为缓解低照度等复杂条件下单一模态检测困难的问题，采集并标注了大规模的成对 RGB 与红外航拍图像数据，数据覆盖从白天到夜晚的多种场景（如城市道路、居民区、停车场等），并以车辆为核心目标提供检测标注，用于系统评测与推动跨模态（RGB+IR）融合/对齐条件下的车辆目标检测方法


### 23. M3FD

- **任务**：可见光生红外
- **出处**：2022 CVPR
- **链接**：https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Target-Aware_Dual_Adversarial_Learning_and_a_Multi-Scenario_Multi-Modality_Benchmark_To_CVPR_2022_paper.pdf

**描述**：用同步标定良好的可见光与红外传感器采集的多场景多模态（可见光–红外）对齐图像对数据集，作者在官方仓库说明其主要用于融合与检测相关实验，包含用于融合/检测/融合后检测的约 4200 对对齐红外-可见光图像对（共 8400 张图像），并额外提供一个独立场景子集（约 300 对）用于融合评测，图像分辨率多为 1024×768，并为 行人、汽车、公交车、摩托车、路灯、卡车 六类目标提供了大量人工检测标注（仓库写明共 34407 个标签），数据覆盖校园、景区与主干道路等多种环境与光照/天气条件以增强场景多样性。


### 24. ViViD

- **任务**：视频
- **出处**：2022 RAL
- **链接**：https://arxiv.org/pdf/2204.06183v2

**描述**：面向低能见度/光照剧烈变化条件下机器人视觉与 SLAM 的多传感器同步数据集，作者将传感器系统配置为手持与车载两种平台，在同一空间中反复采集以覆盖从白天到夜晚等不同照明条件，并提供对齐的多模态视觉数据（文中明确包含 RGB、热红外以及事件相机，同时还配套深度/激光与惯导等信息，热红外以 16-bit raw 格式记录），并结合外部定位或 SLAM 生成方式给出可用于评测的轨迹真值与标定链路，从而支持研究在复杂光照下如何利用热成像/事件等“非可见光强度主导”的传感信息提升鲁棒性。


### 25. VT5000

- **任务**：可见光生红外
- **出处**：2022 TMM
- **链接**：https://doi.org/10.1109/TMM.2022.3171688

**描述**：面向 RGB-T（可见光 RGB + 热红外 TIR）显著性目标检测的大规模成对数据集，论文中作者明确指出他们构建了名为 VT5000 的数据集，包含 5000 对空间对齐的 RGB-T 图像对并提供显著性真值标注（ground truth annotations），同时在不同场景与环境中整理了 11 类挑战因素用于检验算法在复杂条件下的鲁棒性，并以此建立更系统的 RGB-T 显著性检测基准与分析框架


### 26. UIRD

- **任务**：去噪
- **出处**：2022 IEEE Sen.
- **链接**：https://doi.org/10.1109/JSEN.2023.3327413

**描述**：面向非制冷微测辐射热计（microbolometer）热红外相机运动去模糊任务构建的大规模基准数据集，作者指出其反映了非制冷红外成像特有的模糊累积特性，数据由“冷却式 MWIR 相机图像”通过帧插值、红外波段转换以及专门的模糊累积模型合成生成，并形成超过 30k 组模糊—清晰（blur–sharp）图像对用于训练与评测，同时论文还展示了用该数据集训练的去模糊模型在真实非制冷红外图像上的效果。


### 27. IST-A

- **任务**：视频
- **出处**：2023 TGRS
- **链接**：https://doi.org/10.1109/TGRS.2023.3269092

**描述**：面向红外小目标检测的真实采集数据集，所有图像大小为 288×384，目标主要是远距离天空中的 鸟、无人机、直升机、飞机等非合作目标（也包含大量地面背景如植被、建筑等干扰），训练集约 59,553 张、测试集约 14,756 张，并且存在“图中无目标”的样本（例如目标被建筑/植被遮挡）；官方说明强调该数据集不含合成图像、目标并非人为控制捕获，且 87% 以上目标小于 6×6 像素，从而对复杂背景下的小目标检测提出更高挑战。


### 28. SIRST-Aug

- **任务**：视频
- **出处**：2023 TAES
- **链接**：https://doi.org/10.1109/TAES.2023.3238703

**描述**：让 SIRST 更适合训练深度网络并增强模型在复杂背景下检测微弱小目标的能力，因此他们将扩增后的数据作为与 MDFA 并列的公开基准来做对比实验与消融分析，并在官方仓库中以 “SIRST Augment dataset” 的形式提供下载入口（Google Drive / 百度网盘）供复现使用。


### 29. IRDST

- **任务**：视频
- **出处**：2023 TGRS
- **链接**：https://doi.org/10.1109/TGRS.2023.3235150

**描述**：每一帧都同时提供从细到粗的三种标注形式（像素级掩膜、目标框、中心点），并在数据集页面明确给出了真实/仿真数据的目录组织方式以及不同标注文件（masks/boxes/center）的对应关系与生成规则，从而支持红外弱小目标检测在不同监督粒度下的训练与评测


### 30. HIT-UAV

- **任务**：视频
- **出处**：2023 SD
- **链接**：https://www.nature.com/articles/s41597-023-02066-6

**描述**：面向无人机高空视角的热红外目标检测数据集，并为每张图像提供飞行高度、相机视角、日期与日光强度等飞行/采集信息，同时为目标实例提供两种形式的人工框标注以应对航拍场景中目标密集重叠的问题，从而作为 UAV 热红外检测算法的公开评测基准


### 31. FMB

- **任务**：可见光生红外
- **出处**：2023 ICCV
- **链接**：https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_Multi-interactive_Feature_Learning_and_a_Full-time_Multi-modality_Benchmark_for_Image_ICCV_2023_paper.pdf

**描述**：通过标定与单应性估计将红外投影到可见光坐标并裁剪，最终得到 1500 对像素级严格配准的红外–可见光图像对，分辨率为 800×600；数据覆盖不同照明条件下的丰富道路场景，并对绝大多数像素进行语义标注，以支持“融合 + 语义分割”的联合评测。


### 32. SemanticRT

- **任务**：可见光生红外
- **出处**：2023 ACM MM
- **链接**：https://doi.org/10.1145/3581783.3611738

**描述**：面向多光谱语义分割（Multispectral Semantic Segmentation, MSS）的大规模 RGB–热红外数据集


### 33. MS2

- **任务**：视频/可见光生红外
- **出处**：2023 CVPR
- **链接**：https://openaccess.thecvf.com/content/CVPR2023/papers/Shin_Deep_Depth_Estimation_From_Thermal_Image_CVPR_2023_paper.pdf

**描述**：面向户外驾驶场景的多光谱立体数据集，官方主页说明它提供校正并同步的立体 RGB、立体 NIR、立体热红外图像，以及同步的立体 LiDAR、GPS/IMU 导航信息，并且提供将点云投影到不同模态图像平面的深度图与里程计信息，数据覆盖城市、住宅区、道路、校园、郊区等地点以及早晨/白天/夜晚与晴天/多云/雨天等条件，目的是为多光谱传感器下的几何视觉算法（尤其深度估计）提供大规模公开基准


### 34. TIVID

- **任务**：视频/去噪
- **出处**：2024 TIP
- **链接**：https://ieeexplore.ieee.org/document/10507231

**描述**：面向热红外视频去噪的专用数据集/基准，作者在官方仓库中将其作为三大贡献之一，与“物理启发的噪声生成器”和去噪网络（MDIVDnet）配套使用；其组织方式按训练/测试划分，并同时提供 MP4 视频与对应的PNG 帧序列两种格式，用于视频去噪模型的训练与评估，并在工程上支持用“干净序列作为监督真值/参考”以及与噪声建模模块联动的实验流程


### 35. ODinMJ

- **任务**：可见光生红外
- **出处**：2024 GRSM
- **链接**：https://doi.org/10.1109/MGRS.2024.3492069

**描述**：用于山地丛林场景 RGB-T 目标检测的配对数据集，作者先采集了超过 6 万对 RGB-T 图像对并进行严格人工筛选与预处理，最终提供分辨率为 640×512 的弱对齐/配准后双模态图像，并按 8:1:1 划分为 18457/2309/2309 的 train/val/test；同时数据集包含人工检测标注，既有 RGB 与红外各自的标签，也有两模态弱对齐后的“融合标签”，标注格式为 YOLO。


### 36. RGBT-Tiny

- **任务**：视频
- **出处**：2025 TPAMI
- **链接**：https://arxiv.org/abs/2406.14482

**描述**：面向 RGB-T 微小目标检测的大规模基准数据集，覆盖 7 类目标与 8 类场景，其中 超过 81% 的目标尺寸小于 16×16；数据提供可见光与热红外两模态的配对边界框标注并附带跟踪 ID，从而既能用于“微小目标检测”的标准评测，也能支撑融合、检测与跟踪等更广泛的 RGB-T 任务研究


### 37. HM-TIR

- **任务**：对比度增强/去噪
- **出处**：2025 NeurIPS
- **链接**：https://openreview.net/forum?id=yEddfz9SgJ

**描述**：建立了一个覆盖多种环境与视角的高质量 TIR 数据集，包含 1503 张清晰聚焦的 TIR 图像，同时在官方代码仓库中提供了与这些清晰图像配套的退化版本，用于评测“单一退化”和“复合退化”两种场景，从而为热红外“all-in-one”增强方法提供统一的训练与测试基准


### 38. Dataset 38

- **任务**：
- **出处**：
- **链接**：（缺失）

**描述**：（缺失）


### 39. NATO SET-140

- **任务**：去噪/对比度增强
- **出处**：2012 SPIE
- **链接**：https://publications.tno.nl/publication/102842/oSh1Fo/weiss-2012-standard.pdf

**描述**：评测 超分（SR）、对比度增强/动态范围压缩（CE/DRC）、场景非均匀校正（SB-NUC）以及 MWIR/LWIR 融合等算法表现。


### 40. CASIA Interval v3

- **任务**：超分
- **出处**：2016 IA-CAS
- **链接**：数据集：https://hycasia.github.io/dataset/

**描述**：这是近红外（NIR）虹膜图像子集，包含约2655张、320×280分辨率的灰度虹膜图像，来自249名受试者，多用于虹膜识别与分割研究；如果用于超分，通常是把原始图像当作“高分辨率参考”，再通过下采样生成“低分辨率输入”形成配对数据。


### 41. ULB17-VT

- **任务**：可见光生红外/超分
- **出处**：2018 ACCV workshorp
- **链接**：https://link.springer.com/chapter/10.1007/978-3-030-21074-8_28

**描述**：这是一个手工抽取并标注的可见光-热红外配对数据集（文献中常写为约570对），适用于研究“多模态传感器融合”场景下的热红外超分或重建，即利用可见光的高频细节特征来辅助提升热红外图像的空间分辨率与结构清晰度。


### 42. IR-COLOR2000

- **任务**：可见光生红外/超分
- **出处**：2020 Sensors
- **链接**：https://www.mdpi.com/1424-8220/20/1/281

**描述**：该数据集由论文作者采集，核心是成对的RGB与IR同场景图像（论文中用作训练与评测），用于研究“RGB与IR联合输入/特征融合”来提升红外超分重建质量，同时通过引导滤波层等设计缓解红外图像噪声并保留边缘细节。


### 43. IR100

- **任务**：超分
- **出处**：2021 IEEE
- **链接**：https://doi.org/10.1109/LSP.2021.3077801

**描述**：指一个规模约100张的红外图像测试集，用法通常是把原始红外图像当作参考，再按×2/×4/×8等倍率下采样得到输入LR，从而评测重建的PSNR/SSIM等指标


### 44. CVC-09

- **任务**：超分/视频
- **出处**：2013 ICCV
- **链接**：Socarras, Y.; Ramos, S.; Vázquez, D.; López, A.; Gevers, T. Adapting Pedestrian Detection from Synthetic to Far Infrared Images.
In Proceedings of the ICCV Workshop on Visual Domain Adaptation and Dataset Bias (VisDA), Sydney, Australia, 7 December
2013

**描述**：指从CVC-09热红外行人序列中随机抽取约1000帧构成的子集，用于红外SR等低层任务时再进一步通过下采样合成LR/HR对


### 45. Rivadeneira et al.

- **任务**：超分
- **出处**：2022 VISAPP
- **链接**：https://refbase.cvc.uab.es/files/RSV2020.pdf

**描述**：提出热红外超分方法并配套构建数据集，核心思路是用不同分辨率热红外传感器（文献与后续挑战常提到包含Tau2等设备采集）在尽量同步与可配准的条件下获取同场景数据，用于训练/评测热红外SR与跨设备分辨率映射；后续PBVS相关TISR挑战也围绕类似数据组织与评测


### 46. CDN-MRF

- **任务**：超分
- **出处**：2019 IEEE
- **链接**：https://doi.org/10.1109/TCSVT.2018.2864777

**描述**：一篇红外单帧SR方法及其配套实验数据设置，文献/代码常使用“真实红外图像”并通过下采样生成LR/HR对进行训练与评测


</details>

---

