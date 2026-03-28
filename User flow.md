# User Flow — warotasan.github.io

## 使用者類型

| 類型 | 目的 |
|------|------|
| 潛在委託客戶 | 了解作品風格，送出委託需求 |
| 粉絲 | 欣賞角色與粉絲藝術 |
| 合作夥伴 | 確認創作者背景，聯繫合作 |

---

## 整體頁面流程

```
[首頁 index.html]
       │
       ├──> [作品集 Collection.html]
       │           │
       │           └──> [聯絡頁 ContactMe.html] (委託)
       │
       ├──> [粉絲藝術 Fansart.html]
       │
       └──> [聯絡頁 ContactMe.html]
```

---

## 各頁面 User Flow

### 1. 首頁 (`index.html`)

```
進入網站
    │
    ▼
看見全屏英雄圖 (角色立繪)
    │
    ▼
閱讀角色介紹 (Warota 自介)
    │
    ├── 點擊社交媒體圖標 ──> 離開至 Instagram / Twitter / Twitch / YouTube
    │
    └── 點擊導覽列
              ├── Collection  ──> Collection.html
              ├── FanArt      ──> Fansart.html
              └── Contact     ──> ContactMe.html
```

---

### 2. 作品集 (`Collection.html`)

```
進入頁面
    │
    ▼
看見頁面頂部 Banner
    │
    ▼
瀏覽 3D 模型作品卡片 (3×2 網格)
    │
    ├── 滑鼠懸停卡片 ──> 圖片放大效果 (scale 1.1)
    │
    ├── 查看各委託作品
    │       ├── Yanhua (多種髮型 / 服裝)
    │       ├── Zona  (VRM 格式)
    │       ├── Feifei (VRM 格式)
    │       ├── Subin  (VRChat)
    │       ├── Ca6   (VRM 格式)
    │       └── Chichi (VRM 格式)
    │
    └── 對作品感興趣
              │
              ▼
        點擊導覽列 Contact ──> ContactMe.html (送出委託)
```

---

### 3. 粉絲藝術 (`Fansart.html`)

```
進入頁面
    │
    ▼
看見全屏 Banner
    │
    ▼
觀看三行無限滾動圖片廊
    │
    ├── 圖片自動循環滾動 (30 秒 CSS animation)
    │
    ├── 點擊任意圖片
    │       │
    │       ▼
    │   浮層放大顯示圖片
    │       │
    │       └── 點擊 × 或浮層外部 ──> 關閉，回到圖片廊
    │
    └── 點擊社交媒體圖標 ──> 離開至各平台
```

---

### 4. 聯絡頁 (`ContactMe.html`)

```
進入頁面
    │
    ▼
看見 "Contact" 大標題 Banner
    │
    ▼
填寫聯絡表單
    │
    ├── 選擇聯絡意圖
    │       ├── Commission  (委託)
    │       ├── Collaboration (合作)
    │       └── Fan message  (粉絲留言)
    │
    ├── 輸入姓名
    ├── 輸入電子郵件
    ├── 輸入訊息內容
    │
    └── 點擊送出按鈕
              │
              ▼
        表單送出完成
```

---

## 委託客戶完整路徑

```
Google / 社群媒體 / 口耳相傳
    │
    ▼
首頁 (index.html)
確認創作者是 Vtuber / 3D 模型師
    │
    ▼
Collection.html
瀏覽過往委託作品，評估風格與品質
    │
    ▼
ContactMe.html
選擇 "Commission"，填寫需求並送出
    │
    ▼
等待 Warota 回覆 (Email)
```

---

## 粉絲完整路徑

```
追蹤社群媒體後點入網站連結
    │
    ▼
首頁 (index.html)
欣賞角色立繪與介紹
    │
    ▼
Fansart.html
瀏覽粉絲繪圖，點擊放大欣賞
    │
    ▼
點擊社交媒體圖標，回到 Twitch / YouTube 觀看直播
```
