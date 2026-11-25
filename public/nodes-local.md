# 住宅IP 本地筛选报告

- 生成: `2026-11-25 22:01:26 UTC`
- 数据源: VPN Gate `183` 台
- **检测发起地: 用户自己家（黑龙江电信 / iStoreOS 青龙容器）**

| 阶段 | 数量 |
|---|---|
| 本轮多批抽样并集 | 183 |
| 有SSTP入口 + 国家白名单 | 83 |
| 阶段A 本地TCP打得开 | 83 |
| 阶段B 判定为住宅且国家相符 | 52 |
| **跨轮台账中的住宅(总池)** | **548** |
| 阶段C 你家实测连通 | 11 |
| **最终写入清单** | **45** |

## 清单内容

| 编号 | 目标机器 | 出口IP | 运营商 | 你家实测 | 抽查 |
|---|---|---|---|---|---|
| 本地-日本-住宅-30 | `vpn617491321.opengw.net:1931` | 121.114.151.26 | NTT Communications Corpora | 1418ms | OK |
| 本地-日本-住宅-13 | `vpn675037040.opengw.net:1205` | 175.129.80.214 | Kddi Corporation | 1430ms | OK |
| 本地-日本-住宅-12 | `vpn865744309.opengw.net:1418` | 111.99.110.28 | Kddi Corporation | 1483ms | - |
| 本地-日本-住宅-11 | `vpn379611862.opengw.net:1357` | 153.170.155.182 | NTT Communications Corpora | 1540ms | - |
| 本地-日本-住宅-09 | `vpn961954281.opengw.net:1890` | 126.214.179.9 | SoftBank Corp. | 1713ms | - |
| 本地-日本-住宅-18 | `vpn222286321.opengw.net:1714` | 113.154.137.98 | DION (KDDI CORPORATION) | 1801ms | - |
| 本地-日本-住宅-01 | `vpn480.opengw.net:5555` | 110.163.142.88 | NTT DOCOMO, INC. | 2200ms | - |
| 本地-日本-住宅-17 | `vpn857468917.opengw.net:1535` | 182.20.240.27 | TOKAI Communications Corpo | 2377ms | - |
| 本地-日本-住宅-05 | `vpn700189518.opengw.net:1843` | 175.129.193.120 | Kddi Corporation | 2391ms | - |
| 本地-日本-住宅-10 | `vpn462090888.opengw.net:1721` | 121.103.176.25 | Sony Network Communication | 2479ms | - |
| 本地-日本-住宅-03 | `vpn681398325.opengw.net:1256` | 126.208.100.178 | SoftBank Corp. | 2482ms | - |
| 本地-日本-住宅-06 | `vpn272949870.opengw.net:1355` | 115.163.220.163 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-26 | `vpn501671840.opengw.net:1285` | 119.83.242.105 | TOKAI Communications Corpo | 不通 | - |
| 本地-日本-住宅-31 | `vpn187938957.opengw.net:1362` | 120.75.57.120 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-34 | `vpn736504438.opengw.net:1834` | 126.103.157.140 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-35 | `vpn624472654.opengw.net:1588` | 220.147.184.189 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-37 | `vpn220480694.opengw.net:1900` | 60.119.0.51 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-41 | `vpn372144975.opengw.net:1572` | 210.132.182.60 | Japan Network Information  | 不通 | - |
| 本地-日本-住宅-45 | `vpn742036804.opengw.net:1665` | 116.12.0.241 | Community Network Center I | 不通 | - |
| 本地-日本-住宅-23 | `vpn164332738.opengw.net:1325` | 60.65.241.137 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-19 | `vpn295755714.opengw.net:1224` | 106.168.151.103 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-14 | `vpn585941071.opengw.net:1838` | 126.58.59.50 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-648 | `vpn154872091.opengw.net:1449` | 126.216.148.248 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-599 | `vpn600849538.opengw.net:1258` | 133.209.108.50 | NET-JP-ERX | 不通 | - |
| 本地-日本-住宅-600 | `vpn595249968.opengw.net:1647` | 175.129.84.161 | Kddi Corporation | 不通 | - |
| 本地-美国-住宅-08 | `vpn801875041.opengw.net:1382` | 74.83.248.218 | Cincinnati Bell Telephone  | 不通 | - |
| 本地-日本-住宅-29 | `vpn344602886.opengw.net:1566` | 113.153.88.108 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-40 | `vpn197759224.opengw.net:1664` | 220.146.9.93 | ASAHI Net, Inc. | 不通 | - |
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
| 本地-美国-住宅-25 | `vpn929837151.opengw.net:1560` | 141.239.115.116 | Hawaiian Telcom Services C | 不通 | - |
| 本地-日本-住宅-39 | `vpn262831086.opengw.net:1510` | 153.151.191.71 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-49 | `vpn532403382.opengw.net:1911` | 223.133.218.118 | So-net Entertainment Corpo | 不通 | - |
| 本地-美国-住宅-02 | `vpn224583441.opengw.net:1399` | 38.42.52.163 | Starry, Inc. | 不通 | - |
| 本地-日本-住宅-07 | `vpn981697033.opengw.net:1254` | 113.145.230.120 | Kddi Corporation | 未下发 | - |
| 本地-日本-住宅-16 | `vpn407145859.opengw.net:1743` | 60.124.87.220 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-20 | `vpn825186256.opengw.net:1352` | 14.101.10.239 | Kddi Corporation | 未下发 | - |

## 出口抽查（防假住宅回落）

本地-日本-住宅-30→OK; 本地-日本-住宅-13→OK

## 被剔除的

- 96 小时未再出现在任何批次: 11
- 连续3轮实测不通: 11

_由 gate-local 在本地生成，不经境外机房判断。_
