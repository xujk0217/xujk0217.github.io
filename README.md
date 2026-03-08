# 🌐 個人網站模板

<div align="center">

![GDG on Campus NTPU](https://img.shields.io/badge/GDG%20on%20Campus-NTPU-4285F4?style=for-the-badge&logo=google&logoColor=white)

**由 GDG on Campus NTPU 提供的課程教材**

[📸 Instagram](https://www.instagram.com/gdg.ntpu/) 

</div>

---

這是一個簡單好用的個人網站模板，可以快速建立你自己的 GitHub Pages 網站！

## 🚀 快速開始

### 1. Fork 這個專案

1. 點擊右上角的 **Fork** 按鈕
2. 在彈出視窗中，**修改 Repository name** 為 `你的GitHub帳號.github.io`
   - 例如你的帳號是 `student123`，就改成 `student123.github.io`
   - ⚠️ **這步很重要！** 名稱必須完全符合這個格式
3. 點擊 **Create fork**

> 💡 如果 Fork 時忘記改名，可以之後到 Settings > General > Repository name 修改

### 2. 確認 GitHub Pages 已啟用

1. 進入你 Fork 的專案
2. 點擊 **Settings** > 左側選單 **Pages**
3. 確認 Source 是 `Deploy from a branch`
4. Branch 選擇 `main`，資料夾選 `/ (root)`
5. 點擊 **Save**

> 對於 `username.github.io` 命名的 repo，GitHub 通常會自動啟用，但建議還是確認一下

### 3. 等待部署完成

1. 回到專案首頁，點擊 **Actions** 分頁
2. 等待 workflow 跑完（綠色勾勾表示成功）
3. 約 1-2 分鐘後，你的網站就會上線！

### 4. 查看你的網站

打開瀏覽器，輸入：
```
https://你的GitHub帳號.github.io
```
例如：`https://student123.github.io`

---

## ✏️ 如何修改內容

打開 `index.html`，搜尋 `✏️` 符號找到所有需要修改的地方：

### 基本資料
| 項目 | 說明 |
|------|------|
| 網站標題 | `<title>` 標籤內的文字 |
| 你的名字 | 導覽列和 Hero 區塊的名稱 |
| 大頭照 | 替換圖片 URL |
| 自我介紹 | Hero 區塊的描述文字 |

### 社交媒體連結
修改以下連結網址：
- GitHub：`https://github.com/你的帳號`
- Instagram：`https://www.instagram.com/你的帳號`
- YouTube：`https://www.youtube.com/@你的頻道`
- Email：`mailto:你的email@example.com`

### 技能標籤
複製或修改 `<span class="skill-badge">技能名稱</span>` 來新增技能。

### 作品集
每個作品卡片包含：
- 作品截圖 URL
- 作品名稱
- 作品描述
- 展示連結
- GitHub 原始碼連結

複製整個 `col-md-6` 區塊可以新增更多作品。

### 興趣
修改興趣的圖示和名稱。常用圖示：
| 圖示 | class 名稱 |
|------|-----------|
| 🎮 遊戲 | `bi-controller` |
| 🎵 音樂 | `bi-music-note-beamed` |
| 📷 攝影 | `bi-camera` |
| 📚 閱讀 | `bi-book` |
| 🚴 騎車 | `bi-bicycle` |
| 🎬 電影 | `bi-film` |
| 🎨 繪畫 | `bi-palette` |
| 💻 程式 | `bi-code-slash` |
| ☕ 咖啡 | `bi-cup-hot` |

更多圖示請參考：[Bootstrap Icons](https://icons.getbootstrap.com/)

---

## 🎨 如何更換配色

打開 `style.css`，修改最上方的顏色變數：

```css
:root {
    --primary-color: #6366f1;      /* 主色 */
    --secondary-color: #8b5cf6;    /* 副色 */
}
```

### 配色參考
| 風格 | primary-color | secondary-color |
|------|---------------|-----------------|
| 紫色系（預設） | `#6366f1` | `#8b5cf6` |
| 藍色系 | `#3b82f6` | `#60a5fa` |
| 綠色系 | `#10b981` | `#34d399` |
| 粉色系 | `#ec4899` | `#f472b6` |
| 橘色系 | `#f97316` | `#fb923c` || 🌟 **Google 藍** | `#4285F4` | `#5a9bf6` |
| 🌟 **Google 綠** | `#34A853` | `#4fbb6e` |
---

## 📁 檔案結構

```
你的專案/
├── index.html    # 網頁主要內容
├── style.css     # 樣式設定
└── README.md     # 說明文件（本檔案）
```

---

## 📸 如何上傳圖片

### 方法一：使用 Imgur
1. 前往 [imgur.com](https://imgur.com)
2. 上傳圖片
3. 複製圖片連結（以 `.jpg` 或 `.png` 結尾）

### 方法二：上傳到 GitHub
1. 在專案中建立 `images` 資料夾
2. 上傳圖片到該資料夾
3. 使用相對路徑：`images/photo.jpg`

---

## 💡 小技巧

- 修改後記得 **Commit** 並 **Push** 到 GitHub
- GitHub Pages 更新需要等待 1-2 分鐘
- 可以用瀏覽器的「開發者工具」預覽修改效果
- 手機也可以正常瀏覽（響應式設計）

---

## 🛠️ 使用技術

- [Bootstrap 5](https://getbootstrap.com/) - CSS 框架
- [Bootstrap Icons](https://icons.getbootstrap.com/) - 圖示庫
- [GitHub Pages](https://pages.github.com/) - 免費網站託管

---

## 📝 授權

此專案可自由使用、修改和分享。

---

<div align="center">

### 🚀 Made with ❤️ by GDG on Campus NTPU

[📸 追蹤我們的 Instagram](https://www.instagram.com/gdg.ntpu/)

</div>
