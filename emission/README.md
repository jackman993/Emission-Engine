# 🌿 Emission Engine v1.0

**RollPath 翻滾索徑有限公司**  
ESG永續報告一鍵生成的專家

---

## 📋 簡介

以最少資訊，完成最可信的碳排估算（Scope 1 + 2）。

基於 80/20 法則設計，平均誤差 ±10%，適合中小企業快速完成碳盤查。

---

## 🚀 功能

| 模式 | 說明 | 精確度 |
|------|------|--------|
| Quick | 只需月電費，自動估算 | 80% |
| Detail | 完整輸入車輛、冷媒等 | 95% |

### 計算範疇

- **Scope 1**：車輛燃油、冷媒逸散
- **Scope 2**：外購電力
- **Scope 3**（選用）：水、廢棄物

---

## 📊 排放係數

| 項目 | 係數 | 單位 |
|------|------|------|
| 電力 | 0.474 | kg CO₂/kWh |
| 汽油 | 2.3 | kg CO₂/L |
| 柴油 | 2.6 | kg CO₂/L |
| 水 | 0.0004 | t CO₂/m³ |
| 廢棄物 | 0.33 | t CO₂/噸 |

---

## 🛠️ 安裝與執行

```bash
pip install -r requirements.txt
streamlit run emission_app.py
```

---

## 📁 檔案結構

```
emission/
├── emission_app.py      # Streamlit UI
├── emission_calc.py     # 計算核心
├── requirements.txt     # 依賴套件
└── README.md            # 說明文件
```

---

## 📜 授權

© 2025 RollPath 翻滾索徑有限公司. All rights reserved.

---

## 📧 聯絡

如有問題，歡迎聯繫 RollPath 團隊。

