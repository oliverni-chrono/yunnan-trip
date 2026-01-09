# 🌏 老挝+云南 8天7夜自驾游行程

一个精心规划的老挝万象、万荣 + 云南景迈山、普洱、大理、玉龙雪山、丽江自驾游行程网页。

## 📸 预览

交互式地图 + 详细行程时间线，支持高德地图POI标注。

## 🗺️ 行程概览

| Day | 行程 | 亮点 |
|-----|------|------|
| Day 1 | 🇱🇦 抵达万象 | 塔銮、凯旋门、湄公河日落 |
| Day 2 | 🇱🇦 万象→万荣 | 南松河漂流、万荣夜市 |
| Day 3 | 🇱🇦 万荣一日游 | 泄湖Blue Lagoon、丛林飞跃 |
| Day 4 | 🚂 万荣→西双版纳→景迈山 | 中老铁路、翁基古寨 |
| Day 5 | 景迈山→普洱 | 日出云海、古茶林 |
| Day 6 | 普洱→大理 | 双廊、洱海环游 |
| Day 7 | 大理→玉龙雪山→白沙 | 冰川公园、蓝月谷 |
| Day 8 | 白沙→丽江→✈️ | 古城漫游、飞回 |

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/YOUR_USERNAME/yunnan-trip.git
cd yunnan-trip
```

### 2. 配置高德地图API Key

```bash
# 复制配置模板
cp config.example.js config.js

# 编辑 config.js，填入您的高德地图API Key
# 申请地址: https://console.amap.com/dev/key/app
```

### 3. 启动本地服务器

```bash
# 使用Python
python3 -m http.server 8080

# 或使用Node.js
npx serve
```

### 4. 访问

打开浏览器访问 `http://localhost:8080`

## 🔑 高德地图API Key申请

1. 访问 [高德开放平台](https://console.amap.com/)
2. 注册/登录账号
3. 创建应用 → 添加Key
4. 选择 "Web端(JS API)" 服务
5. 将获得的Key填入 `config.js`

## 📁 文件结构

```
yunnan-trip/
├── index.html          # 主页面
├── config.js           # API Key配置 (不上传)
├── config.example.js   # 配置模板
├── .gitignore
└── README.md
```

## ✨ 特性

- 📱 响应式设计，支持移动端
- 🗺️ 高德地图集成，POI标注
- 📍 完整行程时间线
- 🍜 每日美食推荐
- 💡 实用旅行贴士

## 📝 License

MIT

---

Made with ❤️ for travel lovers

