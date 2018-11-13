# VHT

## Spatial Streams

**Management Frame** -> **VHT Capabilities element** -> **Supported VHT-MCS and NSS Set field** -> **Rx VHT-MCS Map**, **Tx VHT-MCS Map**

The Max VHT-MCS For n SS subfield (where n = 1, ..., 8) is encoded as follows:
- 0 indicates support for **VHT-MCS 0-7** for n spatial streams
- 1 indicates support for **VHT-MCS 0-8** for n spatial streams
- 2 indicates support for **VHT-MCS 0-9** for n spatial streams
- 3 indicates that n spatial streams is **not supported**

## VHT-MCS Index

| Spatial Streams | VHT-MCS Index | Modulation | Coding Rate | 80 MHz Data Rate (800ns GI/400ns GI) | 160 MHz / 80 + 80 MHz Data rate (800ns GI/400ns GI) |
|--|--|--|--|--|--|
| 1 | 7 | 64-QAM  | 5/6 | 292.5 / 325.0 | 585.0 / 650.0 |
| 1 | 8 | 256-QAM | 3/4 | 351.0 / 390.0 | 702.0 / 780.0 |
| 1 | 9 | 256-QAM | 5/6 | 390.0 / 433.3 | 780.0 / 866.7 |
| 2 | 7 | 64-QAM  | 5/6 | 585.0 / 650.0 | 1170.0 / 1300.0 |
| 2 | 8 | 256-QAM | 3/4 | 702.2 / 780.0 | 1404.0 / 1560.0 |
| 2 | 9 | 256-QAM | 5/6 | 780.0 / 866.7 | 1560.0 / 1733.0 |
| 3 | 7 | 64-QAM  | 5/6 | 877.5 / 975.0 | 1755.0 / 1950.0 |
| 3 | 8 | 256-QAM | 3/4 | 1053.0 / 1170.0 | 2106.0 / 2340.0 |
| 3 | 9 | 256-QAM | 5/6 | 1170.0 / 1300.0 | n/a |
| 4 | 7 | 64-QAM  | 5/6 | 1170.0 / 1300.0 | 2340.0 / 2600.0 |
| 4 | 8 | 256-QAM | 3/4 | 1404.0 / 1560.0 | 2808.0 / 3120.0 |
| 4 | 9 | 256-QAM | 5/6 | 1560.0 / 1733.3 | 3120.0 / 3466.7 |
| 5 | 7 | 64-QAM  | 5/6 | 1462.5 / 1625.0 | 2925.0 / 3250.0 |
| 5 | 8 | 256-QAM | 3/4 | 1755.0 / 1950.0 | 3510.0 / 3900.0 |
| 5 | 9 | 256-QAM | 5/6 | 1950.0 / 2166.7 | 3900.0 / 4333.3 |
| 6 | 7 | 64-QAM  | 5/6 | 1755.0 / 1950.0 | 3510.0 / 3900.0 |
| 6 | 8 | 256-QAM | 3/4 | 2106.0 / 2340.0 | 4212.0 / 4680.0 |
| 6 | 9 | 256-QAM | 5/6 | n/a | 4680.0 / 5200.0 |
| 7 | 7 | 64-QAM  | 5/6 | 2047.5 / 2275.0 | 4095.0 / 4550.0 |
| 7 | 8 | 256-QAM | 3/4 | 2457.0 / 2730.0 | 4914.0 / 5460.0 |
| 7 | 9 | 256-QAM | 5/6 | 2730.0 / 3033.3 | 5460.0 / 6066.7 |
| 8 | 7 | 64-QAM  | 5/6 | 2340.0 / 2600.0 | 4680.0 / 5200.0 |
| 8 | 8 | 256-QAM | 3/4 | 2808.0 / 3120.0 | 5616.0 / 6240.0 |
| 8 | 9 | 256-QAM | 5/6 | 3120.0 / 3466.7 | 6240.0 / 6933.3 |

# Max Data Rate

Max Date Rate는 채널폭, GI, Spatial Streams와 MCS Index를 통해 결정한다.

 - 채널폭이 160 MHz, 80 + 80 MHz를 지원하는가?
 - Short GI를 지원하는가?
 - 지원하는 NSS(Number of Spatial Streams)는 얼마인가?
 - 지원하는 MCS(Modulation and Coding Scheme)는 얼마인가?
