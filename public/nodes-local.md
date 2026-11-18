# 住宅IP 本地筛选报告

- 生成: `2026-11-18 01:00:10 UTC`
- 数据源: VPN Gate `98` 台
- **检测发起地: 用户自己家（黑龙江电信 / iStoreOS 青龙容器）**

| 阶段 | 数量 |
|---|---|
| 源内服务器 | 98 |
| 有SSTP入口 + 国家白名单 | 43 |
| 阶段A 本地TCP打得开 | 25 |
| 阶段B 判定为住宅且国家相符 | 25 |
| 阶段C 你家实测连通 | 2 |
| **最终写入清单** | **25** |

## 清单内容

| 编号 | 目标机器 | 出口IP | 运营商 | 你家实测 | 抽查 |
|---|---|---|---|---|---|
| 本地-日本-住宅-16 | `vpn221487938.opengw.net:1209` | 126.81.234.189 | SoftBank Corp. | 1440ms | - |
| 本地-日本-住宅-30 | `vpn152852888.opengw.net:1613` | 153.205.149.91 | NTT Communications Corpora | 1564ms | - |
| 本地-日本-住宅-01 | `vpn480.opengw.net:5555` | 110.163.140.56 | NTT DOCOMO, INC. | 未下发 | - |
| 本地-日本-住宅-02 | `laud.opengw.net:443` | 115.179.206.241 | ARTERIA Networks Corporati | 未下发 | - |
| 本地-日本-住宅-03 | `vpn681398325.opengw.net:1256` | 126.208.100.178 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-04 | `vpn953960224.opengw.net:1223` | 106.173.94.75 | Kddi Corporation | 未下发 | - |
| 本地-日本-住宅-05 | `vpn819073110.opengw.net:1460` | 175.129.177.154 | Kddi Corporation | 未下发 | - |
| 本地-日本-住宅-06 | `vpn720772320.opengw.net:1269` | 180.15.3.112 | NTT Communications Corpora | 未下发 | - |
| 本地-日本-住宅-07 | `vpn123938780.opengw.net:1716` | 180.11.151.249 | NTT Communications Corpora | 未下发 | - |
| 本地-日本-住宅-09 | `vpn390088297.opengw.net:995` | 220.221.113.238 | NTT COMMUNICATIONS CORPORA | 未下发 | - |
| 本地-日本-住宅-10 | `vpn576080304.opengw.net:1901` | 126.145.125.132 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-11 | `vpn184169581.opengw.net:1713` | 61.46.101.187 | JCOM | 未下发 | - |
| 本地-日本-住宅-12 | `vpn865744309.opengw.net:1418` | 111.99.110.28 | Kddi Corporation | 未下发 | - |
| 本地-日本-住宅-13 | `vpn774927062.opengw.net:1776` | 118.105.225.45 | Chubu Telecommunications C | 未下发 | - |
| 本地-日本-住宅-14 | `vpn919857584.opengw.net:1667` | 202.213.179.104 | Chupicom Inc. | 未下发 | - |
| 本地-日本-住宅-15 | `vpn537424733.opengw.net:1334` | 60.113.163.74 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-17 | `vpn785696764.opengw.net:1465` | 122.133.148.226 | NEC BIGLOBE Ltd. | 未下发 | - |
| 本地-日本-住宅-18 | `vpn808136125.opengw.net:1772` | 118.153.226.74 | Kddi Corporation | 未下发 | - |
| 本地-日本-住宅-19 | `vpn587729045.opengw.net:1871` | 126.66.207.99 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-20 | `vpn516403983.opengw.net:1363` | 60.110.92.86 | SoftBank Corp. | 未下发 | - |
| 本地-日本-住宅-21 | `vpn202454632.opengw.net:1563` | 223.217.19.99 | NTT Communications Corpora | 未下发 | - |
| 本地-美国-住宅-22 | `vpn833326008.opengw.net:1414` | 47.185.19.135 | Frontier Communications So | 未下发 | - |
| 本地-日本-住宅-23 | `vpn368196031.opengw.net:1735` | 223.133.172.21 | So-net Entertainment Corpo | 未下发 | - |
| 本地-日本-住宅-24 | `vpn635273976.opengw.net:1677` | 61.21.129.143 | JCOM Co., Ltd. | 未下发 | - |
| 本地-日本-住宅-25 | `vpn946329086.opengw.net:1559` | 42.125.178.221 | TOKAI Communications Corpo | 未下发 | - |

## 出口抽查（防假住宅回落）

跳过（距上次抽查仅 3.3 小时，10 小时后再抽，一天约 2 次）

## 被剔除的

- 连续3次实测不通: 1

_由 gate-local 在本地生成，不经境外机房判断。_
