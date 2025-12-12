# 伊 Spa 美體美學 | Yi SPA Body Aesthetics

高雄專業芳療與美膚管理網站

## 項目說明

這是一個**純靜態網站**項目，使用以下技術構建：
- HTML5
- Tailwind CSS (via CDN)
- JavaScript (Vanilla)
- AOS Animation Library
- Lucide Icons

## 本地運行方式

### 方法一：使用 Python 內建 HTTP 伺服器（推薦）

```bash
# 在項目目錄下運行
python -m http.server 8000
```

然後在瀏覽器中訪問：`http://localhost:8000`

### 方法二：使用 Flask 開發伺服器

1. 安裝依賴（如果需要）：
```bash
pip install -r requirements.txt
```

2. 創建簡單的 Flask 服務器（可選）：
```python
from flask import Flask, send_from_directory

app = Flask(__name__)

@app.route('/')
def index():
    return send_from_directory('.', 'index.html')

if __name__ == '__main__':
    app.run(debug=True, port=8000)
```

### 方法三：直接打開文件

也可以直接在瀏覽器中打開 `index.html` 文件，但某些功能可能受限。

## 項目特點

- ✨ 現代化奢華設計（奶茶色+香檳金配色）
- 📱 全響應式設計
- 🎨 優雅的動畫效果
- 🔗 社交媒體整合（LINE、Instagram、Facebook）
- 📍 位置與聯絡資訊

## 服務項目

1. **身體芳療與舒壓** - 全背精油 SPA、全身活氧精油 SPA 等
2. **美體雕塑** - G5 局部雕塑、全身去角質等
3. **臉部保養** - 液態皮秒、黃金拉提、撥筋調理等

## 聯絡方式

- **LINE ID**: @303ptpzp
- **Instagram**: @qizuomi
- **地址**: 高雄市前金區自強二路26-4號2樓

## 部署

此網站可部署至：
- Vercel（已包含 `vercel.json` 配置）
- GitHub Pages
- Netlify
- 任何靜態網站託管服務

---

© 2024 Yi Spa. All rights reserved.
