# GNG Estimation

GNG 新版本首月人数 / Install / DAU / PCU / 匹配等待时长预估资料。

## 目录

- `reports/`：从初版到 v10 的 HTML 预估报告
  - `gng_forecast.html`
  - `gng_forecast_v2.html` ~ `gng_forecast_v8.html`
  - `gng_forecast_v8_scenarios.html`
  - `gng_forecast_v9_scenarios.html`
  - `gng_forecast_v10_scenarios.html`
- `data/raw/`：原始参考数据
  - `GNG_Data_Request_678_rawdata1.txt`：前两个版本按月/区域基础数据，含 avg_dau / avg_ccu / avg_pcu / avg_wait_time_secs
  - `gng_OM_device_retention_2026-04-08.txt`：OM device retention 明细
  - `gng_New_Device_Retention_2026-04-08.txt`：New Device retention 明细
- `docs/`：模型说明、区域映射、任务记录

## 最新版本

最新版报告：`reports/gng_forecast_v10_scenarios.html`

## 核心模型

总 Install = 回流（Revival） + OM（买量） + Organic（自然），三类 Install 均通过留存曲线贡献 DAU。

覆盖区域：ID / VN / MY / US / BR / SAC。
