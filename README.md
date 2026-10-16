# Real Antenna Tracking Station Extension v1.0.0

A ModuleManager patch pack that adds **34 ground tracking stations** to **RealismOverhaul (RO) + RealAntennas + Sol** environments, covering the Chinese Deep Space Network (CDSN), the ESA deep space network (EUDSN), China's TT&C network (including overseas stations), the CAS VLBI/deep space data reception system, and NASA's early Spacecraft Tracking and Data Acquisition Network (STADAN).

## Dependencies

- [Kopernicus](https://github.com/Kopernicus/Kopernicus)
- [ModuleManager](https://forum.kerbalspaceprogram.com/topic/50533-module-manager/)
- [RealismOverhaul](https://github.com/KSP-RO/RealismOverhaul)
- [RealAntennas](https://github.com/KSP-RO/RealAntennas)
- Sol

## Installation

Copy the folder named "RealAntennaTSExtension" to your Gamedata, RealAntennaTSExtension includes the following files:

| File | Contents |
|---|---|
| `Real_Ant_Station_Extention.cfg` | Main cfg: 3 Chinese deep space stations (Jiamusi 66 m, Kashi 35 m, Argentina/Neuquen 35 m) + ESA New Norcia 35 m; registers the `CDSN` and `EUDSN` networks |
| `Additional_Stations.cfg` | 18 additional stations: Chinese TT&C domestic stations (Weinan, Huashan, Shuangcheng, Changcheng, Qingdao, Huanghe, Xiamen, Sanya, Xisha), CAS system (Miyun 50 m, Wuqing 70 m, Kunming 40 m), overseas stations (Karachi, Namibia, Malindi) and international network stations (Alcantara, Kerguelen, Aussaguel) |
| `STADAN_Stations.cfg` | 12 NASA STADAN stations (1960s satellite tracking network: Greenbelt, Blossom Point, Rosman, East Grand Forks, Fort Myers, Winkfield, Shoe Cove, Orroral Valley, Lima, Antofagasta, Cooby Creek, Brown Field) |

`Stations_Added.csv` is a summary table of all 34 stations (name, coordinates, altitude, bands, notes).

## Station List (34 stations)

| Station | Latitude | Longitude | Alt (m) | Bands |
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

## Data Sources and Annotation Rules

- **Measured/paper values**: Chinese deep space station parameters come from the Journal of Deep Space Exploration 2018/2021 papers (Dong Guangliang et al., Yu Zhijian et al.) and "Status and Prospect of China's Deep Space TT&C Network" (SCIENTIA SINICA Informationis, 2020); Miyun 50 m and Kunming 40 m come from peer-reviewed RAA 2009/2010 measurements; NASA station coordinates come from NASA-TM-X-69902 "Directory of Observation Station Locations" (1974) survey data.
- **Gain estimates**: antennas without public gain figures are estimated with G = 20lg(pi*D/lambda) + 10lg(eta), eta = 0.55 (0.6 for the Wuqing 70 m).
- **Assumed values**: TxPower defaults to 60 dBm (1 kW) and AMWTemp to 150 K (S-band) / 90 K (X-band) where no public data exists. All assumed/estimated values are marked in the inline comments.
- **Coordinate precision**: station/island/town/city/range-level approximations are annotated inline.
- **Default antennas**: stations without public antenna data keep only the standard VHF/UHF antenna pair (consistent with RealAntennas defaults).
- **De-duplication**: stations within 25 km of existing tracking stations or launch sites (or actually the same site) were excluded (e.g. Cebreros/Malargue duplicate DSS 63 Madrid / DSA 3 Malargue from Sol-Configs; Qingshan is too close to the Jiuquan launch center station).

## Network Registration

The main cfg registers the `CDSN` (China Deep Space Network) and `EUDSN` (ESA deep space network) home node types via `@RealAntennasCommNetParams`. Registration examples for the remaining stations (`%CNTT`, `%VLBIN`, `%INTL`, `%STADAN`) are provided as comments at the end of each cfg file; uncomment and adjust the grouping to activate them.

## Version

**v1.0.0**
