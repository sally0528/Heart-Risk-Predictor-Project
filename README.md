# Heart-Risk-Predictor-Project
基於 297 例臨床數據的心臟病風險分析與 AI 預測工具，整合 Power BI 看板與 Firebase 雲端部署。
# 心臟病風險預測與數據分析系統 

本專案為實習期間開發之醫療數據解決方案，結合了統計看板分析與即時風險預測。

線上展示
Web App: [https://heart-risk-predictor-2026.web.app/](https://heart-risk-predictor-2026.web.app/)

技術棧
數據分析: 數Power BI (ETL, DAX, 可視化分析)
機器學習: Python (Logistic Regression 邏輯迴歸模型)
前端開發: HTML5, CSS3, JavaScript (Explainable AI 邏輯)
雲端佈署: Firebase Hosting

功能亮點
1.互動式看板: 分析 297 位病患樣本，提供性別、年齡及病症之分佈統計。
2.風險預測器: 基於 13 項醫學特徵，提供準確率 88.33% 的患病機率預估。
3.可解釋性建議: 系統會自動抓出「主要風險因子」，並對比醫學常規值提供「健康優化建議」。

檔案結構
`index.html`: 核心網頁與預測邏輯
`心臟病風險預測.pbix`: Power BI 原始報表檔案
`firebase.json`: 佈署設定檔
