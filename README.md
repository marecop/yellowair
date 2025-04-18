# 黃色航空 | Yellow Airlines

這是一個模擬航空公司網站，提供航班搜索、預訂等功能。網站採用 Next.js、React 和 TypeScript 開發。

## 主要功能

- 航空公司首頁展示
- 航班搜索功能（出發地、目的地、日期、艙位等）
- 航班結果過濾與排序
- 模擬航班數據生成
- 響應式設計適配各種設備

## 技術棧

- **前端框架**: Next.js 14
- **UI 庫**: React 18
- **CSS 框架**: Tailwind CSS
- **編程語言**: TypeScript
- **圖表**: Chart.js + React-Chartjs-2
- **日期處理**: date-fns

## 目錄結構

```
yellairlines/
├── app/              # Next.js 14 應用主目錄
│   ├── components/   # React 組件
│   ├── flights/      # 航班搜索結果頁面
│   └── page.tsx      # 首頁
├── data/             # 生成的航班數據 (JSON & CSV)
├── public/           # 靜態資源
├── scripts/          # 數據生成腳本
├── types/            # TypeScript 類型定義
└── utils/            # 工具函數
```

## 開始使用

### 安裝依賴

```bash
npm install
```

### 生成航班數據

```bash
npm run generate-data
```

### 開發模式運行

```bash
npm run dev
```

### 構建生產版本

```bash
npm run build
```

### 運行生產版本

```bash
npm start
```

## 航班數據模型

航班數據包含以下信息：

- 航班號 (例如: YA123 - 國內航班, YA12 - 國際航班)
- 出發機場 (含 IATA 代碼)
- 到達機場 (含 IATA 代碼)
- 出發時間
- 到達時間
- 飛行時長
- 各艙位價格 (經濟艙, 商務艙, 頭等艙)
- 剩餘座位數
- 是否經停及中轉信息

## 貢獻者

- 黃色航空開發團隊 