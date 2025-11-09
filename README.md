# 系統架構圖資源庫

這個倉庫彙整多個領域的系統設計與架構圖，協助團隊快速對齊方案概念、部署拓撲與資料流。每個領域均提供獨立的 `README.md`，收錄該資料夾內的圖面預覽與補充說明。

## 專案結構
- [`AI/`](AI/README.md)：智慧應用與模型流程架構。
- [`cloud-native/`](cloud-native/README.md)：雲原生與微服務部署設計。
- [`dataops/`](dataops/README.md)：資料治理與資料管線作業流程。

> 若新增其他領域，請建立對應資料夾並撰寫專屬 `README.md`，同時在此處補充連結。

## 圖檔與命名建議
- 圖檔格式建議使用 `.drawio`、`.png`、`.svg` 或 PlantUML/Mermaid 原始碼。
- 檔名採 `{領域}-{主題}-{版本}.{副檔名}`（例如 `cloud-native-event-driven-v1.drawio`）。
- 重大調整請新增版本號；微調可在資料夾 `README.md` 中註記日期與修改重點。

## 更新流程
1. 在對應領域資料夾新增或更新圖檔。
2. 於該資料夾的 `README.md` 新增圖面預覽（Markdown `![alt](./檔名)`）與使用情境描述。
3. 若有背景脈絡或決策紀錄，建議一併紀錄於 `README.md` 或相關文件。
