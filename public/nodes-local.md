# 住宅IP 本地筛选报告

- 生成: `2026-11-17 21:15:36 UTC`
- 数据源: VPN Gate `97` 台
- **检测发起地: 用户自己家（黑龙江电信 / iStoreOS 青龙容器）**

| 阶段 | 数量 |
|---|---|
| 源内服务器 | 97 |
| 有SSTP入口 + 国家白名单 | 45 |
| 阶段A 本地TCP打得开 | 28 |
| 阶段B 判定为住宅且国家相符 | 28 |
| 阶段C 你家实测连通 | 10 |
| **最终写入清单** | **28** |

## 清单内容

| 编号 | 目标机器 | 出口IP | 运营商 | 你家实测 | 抽查 |
|---|---|---|---|---|---|
| 本地-日本-住宅-01 | `laud.opengw.net:443` | 115.179.206.241 | ARTERIA Networks Corporati | 1559ms | OK |
| 本地-日本-住宅-02 | `vpn681398325.opengw.net:1256` | 126.208.100.178 | SoftBank Corp. | 1617ms | OK |
| 本地-日本-住宅-16 | `vpn537424733.opengw.net:1334` | 60.113.163.74 | SoftBank Corp. | 2177ms | - |
| 本地-日本-住宅-15 | `vpn785696764.opengw.net:1465` | 122.133.148.226 | NEC BIGLOBE Ltd. | 2334ms | - |
| 本地-日本-住宅-10 | `vpn221487938.opengw.net:1209` | 126.81.234.189 | SoftBank Corp. | 2406ms | - |
| 本地-日本-住宅-05 | `vpn720772320.opengw.net:1269` | 180.15.3.112 | NTT Communications Corpora | 2452ms | - |
| 本地-日本-住宅-09 | `vpn184169581.opengw.net:1713` | 61.46.101.187 | JCOM | 2497ms | - |
| 本地-日本-住宅-20 | `vpn808136125.opengw.net:1772` | 118.153.226.74 | Kddi Corporation | 2523ms | - |
| 本地-日本-住宅-13 | `vpn390172289.opengw.net:1217` | 131.147.15.145 | Sony Network Communication | 2721ms | - |
| 本地-日本-住宅-03 | `vpn953960224.opengw.net:1223` | 106.173.94.75 | Kddi Corporation | 4800ms | - |
| 本地-日本-住宅-21 | `vpn819073110.opengw.net:1460` | 175.129.177.154 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-06 | `vpn123938780.opengw.net:1716` | 180.11.151.249 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-07 | `vpn249418964.opengw.net:1641` | 114.142.119.224 | QTnet, Inc. | 不通 | - |
| 本地-日本-住宅-08 | `vpn390088297.opengw.net:995` | 220.221.113.238 | NTT COMMUNICATIONS CORPORA | 不通 | - |
| 本地-日本-住宅-11 | `vpn865744309.opengw.net:1418` | 111.99.110.28 | Kddi Corporation | 不通 | - |
| 本地-日本-住宅-12 | `vpn774927062.opengw.net:1776` | 118.105.225.45 | Chubu Telecommunications C | 不通 | - |
| 本地-日本-住宅-14 | `vpn919857584.opengw.net:1667` | 202.213.179.104 | Chupicom Inc. | 不通 | - |
| 本地-日本-住宅-17 | `vpn587729045.opengw.net:1871` | 126.66.207.99 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-18 | `vpn516403983.opengw.net:1363` | 60.110.92.86 | SoftBank Corp. | 不通 | - |
| 本地-日本-住宅-19 | `vpn202454632.opengw.net:1563` | 223.217.19.99 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-22 | `vpn980909101.opengw.net:443` | 180.146.240.18 | OPTAGE Inc. | 不通 | - |
| 本地-美国-住宅-04 | `vpn833326008.opengw.net:1414` | 47.185.19.135 | Frontier Communications So | 不通 | - |
| 本地-日本-住宅-23 | `vpn894969506.opengw.net:1697` | 133.155.116.75 | ITEC Hankyu Hanshin Co., L | 未下发 | - |
| 本地-美国-住宅-28 | `vpn311751110.opengw.net:995` | 209.114.127.122 | Fort Hays State University | 未下发 | - |
| 本地-日本-住宅-24 | `vpn152852888.opengw.net:1613` | 153.205.149.91 | NTT Communications Corpora | 不通 | - |
| 本地-日本-住宅-25 | `vpn368196031.opengw.net:1735` | 223.133.172.21 | So-net Entertainment Corpo | 不通 | - |
| 本地-日本-住宅-26 | `vpn780850191.opengw.net:1837` | 221.241.238.36 | ARTERIA Networks Corporati | 不通 | - |
| 本地-日本-住宅-27 | `vpn635273976.opengw.net:1677` | 61.21.129.143 | JCOM Co., Ltd. | 不通 | - |

## 出口抽查（防假住宅回落）

日本-住宅-01→OK; 日本-住宅-02→OK

## 被剔除的


_由 gate-local 在本地生成，不经境外机房判断。_
