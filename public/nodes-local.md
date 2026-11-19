# 住宅IP 本地筛选报告

- 生成: `2026-11-19 10:01:33 UTC`
- 数据源: VPN Gate `191` 台
- **检测发起地: 用户自己家（黑龙江电信 / iStoreOS 青龙容器）**

| 阶段 | 数量 |
|---|---|
| 本轮多批抽样并集 | 191 |
| 有SSTP入口 + 国家白名单 | 88 |
| 阶段A 本地TCP打得开 | 88 |
| 阶段B 判定为住宅且国家相符 | 56 |
| **跨轮台账中的住宅(总池)** | **380** |
| 阶段C 你家实测连通 | 12 |
| **最终写入清单** | **45** |

## 清单内容

| 编号 | 目标机器 | 出口IP | 运营商 | 你家实测 | 抽查 |
|---|---|---|---|---|---|
| 本地-日本-住宅-12 | `vpn865744309.opengw.net:1418` | 111.99.110.28 | Kddi Corporation | 1480ms | OK |
| 本地-日本-住宅-30 | `vpn152852888.opengw.net:1613` | 153.205.149.91 | NTT Communications Corpora | 1627ms | OK |
| 本地-日本-住宅-06 | `vpn720772320.opengw.net:1269` | 180.15.3.112 | NTT Communications Corpora | 2539ms | - |
| 本地-日本-住宅-09 | `vpn390088297.opengw.net:995` | 220.221.113.238 | NTT COMMUNICATIONS CORPORA | 3748ms | - |
| 本地-日本-住宅-04 | `vpn953960224.opengw.net:1223` | 106.173.94.75 | Kddi Corporation | 3832ms | - |
| 本地-日本-住宅-24 | `vpn635273976.opengw.net:1677` | 61.21.129.143 | JCOM Co., Ltd. | 4086ms | - |
| 本地-日本-住宅-14 | `vpn630461743.opengw.net:1378` | 223.133.135.144 | Sony Network Communication | 4136ms | - |
| 本地-日本-住宅-03 | `vpn681398325.opengw.net:1256` | 126.208.100.178 | SoftBank Corp. | 4204ms | - |
| 本地-日本-住宅-05 | `vpn152857105.opengw.net:1924` | 222.6.221.181 | Kddi Corporation | 4249ms | - |
| 本地-日本-住宅-17 | `vpn785696764.opengw.net:1465` | 122.133.148.226 | NEC BIGLOBE Ltd. | 5227ms | - |
| 本地-日本-住宅-01 | `vpn480.opengw.net:5555` | 110.163.140.56 | NTT DOCOMO, INC. | 5308ms | - |
| 本地-日本-住宅-10 | `vpn297008596.opengw.net:1514` | 126.117.177.124 | SoftBank Corp. | 7082ms | - |
| 本地-日本-住宅-02 | `laud.opengw.net:443` | 115.179.206.241 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-15 | `vpn945893058.opengw.net:1242` | 59.138.139.69 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-26 | `vpn501671840.opengw.net:1285` | 119.83.242.105 | TOKAI Communications Corpo | 不通 | - |
| 本地-日本-住宅-31 | `vpn187938957.opengw.net:1362` | 120.75.57.120 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-34 | `vpn736504438.opengw.net:1834` | 126.103.157.140 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-35 | `vpn624472654.opengw.net:1588` | 220.147.184.189 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-37 | `vpn220480694.opengw.net:1900` | 60.119.0.51 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-39 | `vpn600849538.opengw.net:1258` | 133.209.108.50 | NET-JP-ERX | 不通 | - |
| 本地-日本-住宅-41 | `vpn372144975.opengw.net:1572` | 210.132.182.60 | Japan Network Information  | 不通 | - |
| 本地-日本-住宅-42 | `vpn173939682.opengw.net:1944` | 118.241.152.20 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-45 | `vpn742036804.opengw.net:1665` | 116.12.0.241 | Community Network Center I | 不通 | - |
| 本地-日本-住宅-46 | `vpn663500256.opengw.net:1965` | 180.196.186.246 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-48 | `vpn469796077.opengw.net:1805` | 106.179.239.207 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-51 | `vpn120829364.opengw.net:1206` | 126.145.51.121 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-18 | `vpn808136125.opengw.net:1772` | 118.153.226.74 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-11 | `vpn947610909.opengw.net:5555` | 126.235.87.202 | SoftBank Corp. | 不通 | - |
| 本地-美国-住宅-08 | `vpn801875041.opengw.net:1382` | 74.83.248.218 | Cincinnati Bell Telephone  | 不通 | - |
| 本地-日本-住宅-27 | `vpn657969707.opengw.net:1622` | 150.31.134.129 | Internet Initiative Japan  | 不通 | - |
| 本地-日本-住宅-28 | `vpn146183221.opengw.net:1968` | 124.212.251.101 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-29 | `vpn344602886.opengw.net:1566` | 113.153.88.108 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-32 | `vpn540491747.opengw.net:1811` | 39.110.50.237 | Sony Network Communication | 不通 | - |
| 本地-日本-住宅-33 | `vpn750706241.opengw.net:1995` | 118.104.101.56 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-36 | `vpn304914558.opengw.net:1366` | 210.147.131.249 | BIGLOBE Inc. | 不通 | - |
| 本地-日本-住宅-40 | `vpn197759224.opengw.net:1664` | 220.146.69.175 | ASAHI Net, Inc. | 不通 | - |
| 本地-日本-住宅-38 | `vpn582749252.opengw.net:1558` | 118.158.49.173 | DION (KDDI CORPORATION) | 不通 | - |
| 本地-日本-住宅-43 | `vpn668492218.opengw.net:1486` | 126.217.1.16 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-44 | `vpn198732322.opengw.net:1312` | 153.132.115.193 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-47 | `vpn199416793.opengw.net:1248` | 27.94.219.140 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-49 | `vpn311482781.opengw.net:1493` | 180.199.135.1 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-50 | `vpn284945165.opengw.net:1676` | 211.14.226.154 | KATCH Network Inc. | 不通 | - |
| 本地-日本-住宅-52 | `vpn780850191.opengw.net:1837` | 221.241.238.36 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-16 | `vpn741079885.opengw.net:1748` | 60.68.69.108 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-19 | `vpn153171586.opengw.net:1334` | 60.147.40.20 | SoftBank Corp. | 未下发 | - |

## 出口抽查（防假住宅回落）

本地-日本-住宅-12→OK; 本地-日本-住宅-30→OK

## 被剔除的

- 连续3轮实测不通: 4

_由 gate-local 在本地生成，不经境外机房判断。_
