# Real Antenna Tracking Station Extension v1.0.0

为 **RealismOverhaul（RO）+ RealAntennas + Sol** 环境扩展全球地面测控站网络的 ModuleManager 补丁包。共新增 **34 个测控站**，覆盖中国深空测控网（CDSN）、欧空局深空网（EUDSN）、中国航天测控网（含海外站）、中科院 VLBI/深空数据接收体系，以及 NASA 早期卫星跟踪数据网（STADAN）。

## 依赖

- [Kopernicus](https://github.com/Kopernicus/Kopernicus)
- [ModuleManager](https://forum.kerbalspaceprogram.com/topic/50533-module-manager/)
- [RealismOverhaul](https://github.com/KSP-RO/RealismOverhaul)
- [RealAntennas](https://github.com/KSP-RO/RealAntennas)
- Sol

## 安装

将RealAntennaTSExtension放入游戏Gamedata，RealAntennaTSExtension文件夹包括：

| 文件 | 内容 |
|---|---|
| `Real_Ant_Station_Extention.cfg` | 主 cfg：中国深空网 3 站（佳木斯 66 m、喀什 35 m、阿根廷内乌肯 35 m）+ ESA 新诺舍 35 m，并注册 `CDSN` 与 `EUDSN` 网络 |
| `Additional_Stations.cfg` | 追加 18 站：中国航天测控网国内站（渭南、华山、双城、长城、青岛、黄河、厦门、三亚、西沙）、中科院体系（密云 50 m、武清 70 m、昆明 40 m）、海外站（卡拉奇、纳米比亚、马林迪）与国际联网站（阿尔坎特拉、凯尔盖朗、奥赛盖尔） |
| `STADAN_Stations.cfg` | NASA STADAN 网 12 站（1960 年代卫星跟踪数据网：Greenbelt、Blossom Point、Rosman、East Grand Forks、Fort Myers、Winkfield、Shoe Cove、Orroral Valley、Lima、Antofagasta、Cooby Creek、Brown Field） |

`Stations_Added.csv` 为全部 34 站的汇总清单（站名、经纬度、海拔、频段、说明）。

## 站列表（34 站）

| 站 | 纬度 | 经度 | 海拔 (m) | 频段 |
|---|---|---|---|---|
| Jiamusi | 46.4936 N | 130.7700 E | 350 | VHF/UHF/S/X |
| Kashi | 38.4430 N | 76.7279 E | 1300 | VHF/UHF/S/X/Ka |
| Argentina - Neuquen | 38.1914 S | 70.1495 W | 800 | VHF/UHF/S/X/Ka |
| New Norcia | 31.0482 S | 116.1915 E | 200 | VHF/UHF/S/X/Ka |
| Weinan | 34.3583 N | 109.6015 E | 500 | VHF/UHF |
| Huashan | 34.2520 N | 109.0179 E | 400 | VHF/UHF |
| Shuangcheng | 40.7289 N | 99.9847 E | 1200 | VHF/UHF |
| Changcheng | 43.7910 N | 125.4400 E | 250 | VHF/UHF |
| Qingdao | 36.2120 N | 120.2670 E | 8 | VHF/UHF/S |
| Huanghe | 78.9232 N | 11.9345 E | 15 | VHF/UHF |
| Xiamen | 24.6199 N | 117.9986 E | 25 | VHF/UHF/S |
| Sanya | 18.2000 N | 109.5000 E | 8 | VHF/UHF/S |
| Xisha | 16.4531 N | 111.7114 E | 3 | VHF/UHF |
| Miyun | 40.5580 N | 116.9760 E | 155 | VHF/UHF/S/X |
| Wuqing | 39.3823 N | 117.0377 E | 8 | VHF/UHF/X |
| Kunming | 25.0258 N | 102.7950 E | 1985 | VHF/UHF/S/X |
| Karachi | 24.9500 N | 67.1400 E | 20 | VHF/UHF |
| Namibia | 22.5747 S | 14.5478 E | 15 | VHF/UHF/S/X |
| Malindi | 2.9900 S | 40.1900 E | 15 | VHF/UHF/S/X |
| Alcantara | 2.3717 S | 44.3908 W | 45 | VHF/UHF |
| Kerguelen | 49.3517 S | 70.2556 E | 34 | VHF/UHF |
| Aussaguel | 43.4289 N | 1.4978 E | 197 | VHF/UHF |
| Greenbelt | 38.9984 N | 76.8423 W | 54 | VHF/UHF |
| Rosman | 35.2000 N | 82.8721 W | 892 | VHF/UHF/S |
| East Grand Forks | 48.0226 N | 97.0107 W | 253 | VHF/UHF |
| Fort Myers | 26.5477 N | 81.8656 W | 5 | VHF/UHF |
| Blossom Point | 38.4196 N | 77.0866 W | 6 | VHF/UHF |
| Winkfield | 51.4470 N | 0.6961 W | 72 | VHF/UHF |
| Shoe Cove | 47.7416 N | 52.7213 W | 68 | VHF/UHF |
| Orroral Valley | 35.6313 S | 148.9530 E | 931 | VHF/UHF/S |
| Lima | 11.7764 S | 77.1495 W | 50 | VHF/UHF |
| Antofagasta | 23.6500 S | 70.4000 W | 50 | VHF/UHF |
| Cooby Creek | 27.3974 S | 151.9381 E | 550 | VHF/UHF/S |
| Brown Field | 32.5722 N | 116.9803 W | 157 | VHF/UHF |

## 数据来源与标注规则

- **实测/论文值**：中国深空站参数来自《深空探测学报》2018/2021 年论文（董光亮等、于志坚等）与《中国深空测控网现状与展望》（中国科学:信息科学 2020）；密云 50 m、昆明 40 m 来自 RAA 2009/2010 同行评审论文实测；NASA 各站坐标来自 NASA-TM-X-69902《Directory of Observation Station Locations》(1974) 勘测数据。
- **增益估算**：无公开增益的天线按抛物面公式 G = 20lg(πD/λ) + 10lg(η) 估算，η 取 0.55（武清 70 m 取 0.6）。
- **假设值**：无公开数据的 TxPower 统一取 60 dBm（1 kW）；AMWTemp 按 S 频段 150 K、X 频段 90 K 假设。所有假设/估算值均在 cfg 行内注释中标明。
- **坐标精度**：站级/岛级/城镇级/城市级/场区级近似均在注释中标注。
- **默认天线**：无公开天线数据的站仅保留标准 VHF/UHF 基础天线对（与 RealAntennas 默认规则一致）。
- **去重**：与已有测控站或发射场距离 25 km 以内、或实际为同一站的站点已排除（如 Cebreros/Malargue 与 Sol-Configs 的 DSS 63 Madrid/DSA 3 Malargüe 重合，青山与酒泉发射中心站过近等）。

## 网络注册

主 cfg 已通过 `@RealAntennasCommNetParams` 注册 `CDSN`（中国深空网）与 `EUDSN`（欧空局深空网）网络。其余站点的网络注册示例（`%CNTT`、`%VLBIN`、`%INTL`、`%STADAN`）以注释形式列于各 cfg 文件末尾，取消注释并按需调整分组后生效。

## 版本

**v1.0.0**
