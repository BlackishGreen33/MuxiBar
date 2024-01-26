<h1 align="center">MuxiBar</h1>
<div align="center">
  <h3>一個在線即時通訊軟體</h3>
  <a href="https://github.com/BlackishGreen33/MuxiBar"><strong>探索專案文檔 »</strong></a>
  <br />
  <br />
  
  ![license](https://img.shields.io/github/license/BlackishGreen33/MuxiBar)
  ![language](https://img.shields.io/github/languages/top/BlackishGreen33/MuxiBar)
  ![last](https://img.shields.io/github/last-commit/BlackishGreen33/MuxiBar)
  
  <a href="https://muxi-bar.vercel.app/" target="_blank">在線體驗</a>
  ·
  <a href="https://github.com/BlackishGreen33/MuxiBar/issues">報告Bug</a>
  ·
  <a href="https://github.com/BlackishGreen33/MuxiBar/issues">提出新特性</a>
</div>

### 🎯 相容環境

- 現代瀏覽器（Chrome >= 64, Edge >= 79, Firefox >= 78, Safari >= 12）

### ✨ 現有功能

- 創建專屬伺服器
- 伺服器權限管理(包括 `傭有者` 、 `管理員` 與 `一般成員`)
- 建立伺服器邀請連結
- 創建頻道(包括 `文字頻道` 、 `語音頻道` 與 `視訊頻道`)
- 發送 emoji 、圖片、pdf 檔案(可在線預覽)
- 公眾頻道/私人聊天和通訊
- 螢幕畫面共享

### ✒️ 引用技術

- **框架**: [Next.js](https://nextjs.org)
- **樣式**: [Tailwind CSS](https://www.tailwindcss.cn/)
- **資料庫**: [MySQL](https://www.mysql.com/)
- **資料庫工具**: [Prisma](https://www.prisma.io/)
- **即時通訊**: [Socket.IO](https://socket.io/)
- **媒體串流**: [WebRTC](https://webrtc.org/)

### 💻 本地調試

下載到本地：
```bash
$ git https://github.com/BlackishGreen33/MuxiBar.git
$ cd MuxiBar
```

配置環境變量：
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

安裝依賴包：
```bash
$ pnpm install
```

開始調試：
```bash
$ pnpm run dev
```

### 📝 授權

上述文件皆以 MIT 許可授權
> 詳細之授權請參照 [LICENSE](LICENSE) 文件
