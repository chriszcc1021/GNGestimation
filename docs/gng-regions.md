# GNG Lock Region → IP Region 对应关系

| Lock Region | Server | 时区 | GeoIP Region |
|---|---|---|---|
| ID | SG | +7 | ID |
| SG | SG | +7 | TH, LA, MM / MY, BN, KH, PK, LK, BT, PW, SB, PH, AU, NZ, FJ, FM, MN, PG, CN / VN / IN, NP, BD / TW, HK, MO, JP, KR / AM, AZ, BY, KZ, KG, MD, RU, TJ, TM, UA, UZ, GE |
| EU | EU | +2 | 欧洲+非洲+中东（PL, DE, FR, GB, IT, ES, NL, GR等） |
| BR | US | -3 | BR, BM, AO |
| SAC | US | -3 | AR, PE, BO, CL, PY, UY, AN, GY |
| US | US | -5 | AG, AI, AW, BB, BS, BZ, CA, DM, DO, GD, HT, JM, KN, KY, LC, MS, SR, TC, TT, US, VC, VG, VI等 |

## 关键对应（GNG数据口径）
- 数据里的 ID → Lock Region = ID
- 数据里的 TH/VN/MY → Lock Region = SG
- 数据里的 BR → Lock Region = BR
- 数据里的 MX → Lock Region = US（MX归US服，-6时区）
- SAC → AR, PE, BO, CL, PY, UY等南美

更新时间: 2026-04-10
