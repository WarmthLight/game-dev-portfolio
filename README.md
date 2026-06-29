# 🎮 游戏开发作品集

Unity游戏开发工程师个人作品集网站。

## 📁 项目结构

```
portfolio/
├── index.html          # 主页面
├── videos/             # 演示视频
│   ├── shadowplay.mp4  # Shadow Play 皮影戏演示
│   └── jyjh.mp4        # 剑影江湖演示
├── vercel.json         # Vercel 配置
├── wrangler.toml       # Cloudflare 配置
└── README.md           # 项目说明
```

## 📋 项目展示

### Shadow Play 皮影戏
中国传统皮影戏创作与表演工具，包含：
- DIY角色绘制系统
- 三杆操控系统
- Timeline录制与回放
- Vosk语音识别集成
- FFmpeg视频导出

### 剑影江湖：血刃争锋
3D动作RPG游戏，包含：
- 敌人AI状态机
- 技能系统与Buff系统
- NavMesh寻路
- 角色控制系统

## 🚀 部署到 Cloudflare Pages

### 步骤1：推送代码到 GitHub
```bash
git add .
git commit -m "更新作品集"
git push origin main
```

### 步骤2：登录 Cloudflare
- 访问 https://dash.cloudflare.com
- 注册/登录账号

### 步骤3：创建 Pages 项目
1. 点击 "Workers & Pages"
2. 点击 "Create application"
3. 选择 "Pages" 标签
4. 点击 "Connect to Git"
5. 选择 GitHub 仓库
6. 配置：
   - Production branch: `main`
   - Build command: 留空
   - Build output directory: `/`
7. 点击 "Save and Deploy"

### 步骤4：访问网站
部署完成后，获得地址：`https://xxx.pages.dev`

## 🛠️ 技术栈

- HTML5 + Tailwind CSS
- 响应式设计（支持多端）
- 视频播放
- 模态框交互

## 📄 License

MIT License
