# WarotaWorks — warotasan.github.io

Warota 的個人品牌網站，展示 3D 模型編輯作品與粉絲藝術，部署於 GitHub Pages。

## 網站頁面

| 頁面 | 檔案 | 說明 |
|------|------|------|
| 首頁 | `index.html` | 角色介紹與社交媒體連結 |
| 作品集 | `Collection.html` | 3D 模型編輯委託作品展示 |
| 粉絲藝術 | `Fansart.html` | 粉絲創作圖片無限滾動畫廊 |
| 聯絡 | `ContactMe.html` | 委託 / 合作 / 留言表單 |

## 技術棧

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Bootstrap 5.1.1** — 響應式佈局與 UI 元件
- **Google Fonts** — Montserrat、Noto Sans JP、Silkscreen
- **GitHub Pages** — 靜態網站託管

## 專案結構

```
warotasan.github.io/
├── index.html
├── Collection.html
├── Fansart.html
├── ContactMe.html
├── CSS/
│   └── bootstrap.min.css
├── JS/
│   ├── bootstrap.min.js
│   └── popper.min.js
└── img/
    ├── BackGround/     # 各頁面背景圖
    ├── Collections/    # 作品集圖片
    ├── FansArt/        # 粉絲藝術圖片 (30 張)
    ├── icon/           # 社交媒體圖標 (SVG)
    ├── LOGO/           # 品牌標誌
    └── Vtuber/         # 角色立繪
```

## 本地預覽

直接在瀏覽器開啟 `index.html`，或使用任意靜態伺服器：

```bash
# 使用 VS Code Live Server 擴充套件
# 或 Python
python -m http.server 8080
```

## 授權

© WarotaWorks. All rights reserved.
