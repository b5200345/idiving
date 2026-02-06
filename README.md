# iDiving 財務管理系統

一個專為 iDiving 設計的財務管理系統，整合 POS、支出管理、銀行對帳及報表功能。

## 功能特點

- 📊 **儀表板** - 即時財務數據總覽
- 💰 **POS 系統** - 銷售與收入管理
- 📝 **支出管理** - 支出申請、審核與批次撥款
- 🏦 **銀行對帳** - 自動/手動勾稽功能
- 📈 **報表分析** - 財務報表與數據分析
- 📥 **銀行帳單匯入** - 支援 CSV/Excel 格式

## 技術棧

- React 18
- Vite
- Tailwind CSS
- Lucide React Icons

## 安裝與執行

### 前置需求

- Node.js 16.x 或更高版本
- npm 或 yarn

### 安裝步驟

1. 克隆專案
```bash
git clone <your-repository-url>
cd idiving-finance-system
```

2. 安裝依賴套件
```bash
npm install
```

3. 啟動開發伺服器
```bash
npm run dev
```

4. 在瀏覽器中開啟 `http://localhost:3000`

### 建置生產版本

```bash
npm run build
```

建置完成的檔案會在 `dist` 資料夾中。

### 預覽生產版本

```bash
npm run preview
```

## 專案結構

```
idiving-finance-system/
├── src/
│   ├── App.jsx          # 主應用程式元件
│   ├── main.jsx         # 應用程式入口
│   └── index.css        # 全域樣式
├── index.html           # HTML 模板
├── package.json         # 專案配置
├── vite.config.js       # Vite 配置
├── tailwind.config.js   # Tailwind CSS 配置
└── README.md            # 專案說明
```

## 使用說明

### 預設帳號權限

系統包含四種權限角色：
- **小幫手** - 基本操作權限
- **員工** - 一般員工權限
- **店長** - 管理權限
- **管理員** - 完整系統權限

### 主要功能模組

#### 1. POS 系統
- 快速銷售登記
- 多種付款方式（現金、匯款、Line Pay）
- 客戶資訊記錄

#### 2. 支出管理
- 支出申請與審核流程
- 批次撥款功能
- 支出類別分類

#### 3. 銀行對帳
- 銀行帳單匯入
- 自動/手動勾稽
- 待處理項目管理

#### 4. 報表分析
- 營收與成本分析
- 毛利率計算
- 分店別數據統計

## 開發注意事項

- 本系統目前使用 Mock 資料，實際部署需整合後端 API
- 建議使用 Chrome 或 Edge 瀏覽器以獲得最佳體驗
- 響應式設計支援桌面與行動裝置

## 授權

MIT License

## 聯絡方式

如有問題或建議，請聯繫專案維護者。
