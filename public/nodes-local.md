# 住宅IP 本地筛选报告

- 生成: `2026-11-28 10:03:17 UTC`
- 数据源: VPN Gate `177` 台
- **检测发起地: 用户自己家（黑龙江电信 / iStoreOS 青龙容器）**

| 阶段 | 数量 |
|---|---|
| 本轮多批抽样并集 | 177 |
| 有SSTP入口 + 国家白名单 | 87 |
| 阶段A 本地TCP打得开 | 87 |
| 阶段B 判定为住宅且国家相符 | 70 |
| **跨轮台账中的住宅(总池)** | **447** |
| 阶段C 你家实测连通 | 14 |
| **最终写入清单** | **45** |

## 清单内容

| 编号 | 目标机器 | 出口IP | 运营商 | 你家实测 | 抽查 |
|---|---|---|---|---|---|
| 本地-日本-住宅-06 | `vpn718496341.opengw.net:1625` | 110.135.205.179 | JCOM Co., Ltd. | 1220ms | OK |
| 本地-日本-住宅-03 | `vpn129214879.opengw.net:1767` | 59.138.218.10 | Kddi Corporation | 1437ms | 抽查失败 URLError |
| 本地-日本-住宅-17 | `vpn946019409.opengw.net:1557` | 126.130.164.3 | SoftBank Corp. | 2273ms | - |
| 本地-日本-住宅-12 | `vpn865744309.opengw.net:1418` | 111.99.110.28 | Kddi Corporation | 2314ms | - |
| 本地-日本-住宅-13 | `vpn675037040.opengw.net:1205` | 175.129.80.214 | Kddi Corporation | 2506ms | - |
| 本地-日本-住宅-24 | `vpn384442907.opengw.net:1746` | 101.1.152.200 | STNet, Incorporated | 2508ms | - |
| 本地-日本-住宅-01 | `vpn873543396.opengw.net:1556` | 122.210.82.161 | ARTERIA Networks Corporati | 2777ms | - |
| 本地-日本-住宅-23 | `vpn255636415.opengw.net:1452` | 175.129.113.227 | Kddi Corporation | 3040ms | - |
| 本地-日本-住宅-30 | `vpn617491321.opengw.net:1931` | 114.183.35.196 | NTT Communications Corpora | 3088ms | - |
| 本地-日本-住宅-10 | `vpn462090888.opengw.net:1721` | 121.103.176.25 | Sony Network Communication | 3458ms | - |
| 本地-日本-住宅-05 | `vpn669010119.opengw.net:1628` | 59.130.24.201 | KDDI | 4052ms | - |
| 本地-日本-住宅-19 | `vpn468833361.opengw.net:1259` | 60.108.251.162 | SoftBank Corp. | 4061ms | - |
| 本地-日本-住宅-18 | `vpn222286321.opengw.net:1714` | 113.154.137.98 | DION (KDDI CORPORATION) | 4665ms | - |
| 本地-日本-住宅-16 | `vpn632254640.opengw.net:1822` | 115.36.138.45 | Chubu Telecommunications C | 8883ms | - |
| 本地-日本-住宅-491 | `vpn700189518.opengw.net:1843` | 175.129.193.120 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-469 | `vpn257845930.opengw.net:1256` | 115.36.211.48 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-26 | `vpn501671840.opengw.net:1285` | 119.83.242.105 | TOKAI Communications Corpo | 不通 | - |
| 本地-日本-住宅-31 | `vpn187938957.opengw.net:1362` | 120.75.57.120 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-34 | `vpn736504438.opengw.net:1834` | 126.103.157.140 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-35 | `vpn624472654.opengw.net:1588` | 220.147.184.189 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-37 | `vpn220480694.opengw.net:1900` | 60.119.0.51 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-45 | `vpn742036804.opengw.net:1665` | 116.12.0.241 | Community Network Center I | 不通 | - |
| 本地-日本-住宅-09 | `vpn961954281.opengw.net:1890` | 126.214.179.9 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-14 | `vpn188345165.opengw.net:1448` | 111.217.31.206 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-20 | `vpn743284148.opengw.net:1201` | 124.211.146.144 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-648 | `vpn154872091.opengw.net:1449` | 126.216.148.248 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-599 | `vpn600849538.opengw.net:1258` | 133.209.108.50 | NET-JP-ERX | 不通 | - |
| 本地-日本-住宅-600 | `vpn595249968.opengw.net:1647` | 175.129.84.161 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-446 | `vpn372144975.opengw.net:1572` | 210.132.182.60 | Japan Network Information  | 不通 | - |
| 本地-日本-住宅-439 | `vpn634109661.opengw.net:1284` | 126.218.26.174 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-29 | `vpn344602886.opengw.net:1566` | 113.153.88.108 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-38 | `vpn582749252.opengw.net:1558` | 118.158.49.173 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-美国-住宅-15 | `vpn799794865.opengw.net:1919` | 135.180.93.53 | Sonic Telecom LLC | 不通 | - |
| 本地-日本-住宅-36 | `vpn102042272.opengw.net:1822` | 14.132.71.245 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-42 | `vpn777651061.opengw.net:1326` | 118.159.28.138 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-43 | `vpn401356693.opengw.net:1448` | 153.125.118.19 | Toyohashi Cable Network In | 不通 | - |
| 本地-日本-住宅-46 | `vpn396437599.opengw.net:1603` | 218.112.71.240 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-47 | `vpn664739414.opengw.net:1722` | 60.107.169.27 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-22 | `vpn294431000.opengw.net:1426` | 106.174.122.123 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-32 | `vpn110472687.opengw.net:1418` | 36.12.228.153 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-48 | `vpn500462083.opengw.net:1754` | 106.179.195.53 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-39 | `vpn262831086.opengw.net:1510` | 153.151.191.71 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-49 | `vpn532403382.opengw.net:1911` | 223.133.218.118 | So-net Entertainment Corpo | 不通 | - |
| 本地-日本-住宅-08 | `vpn161109829.opengw.net:1305` | 126.36.20.200 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-27 | `vpn277943631.opengw.net:1949` | 126.38.142.184 | SoftBank Corp. | 不通 | - |

## 出口抽查（防假住宅回落）

本地-日本-住宅-06→OK

## 被剔除的

- 连续3轮实测不通: 14
- 96 小时未再出现在任何批次: 12

_由 gate-local 在本地生成，不经境外机房判断。_
