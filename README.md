# 量迹AI科技小量餐饮版 | 基于MCP的智能餐饮系统

（中文 | [English](README_en.md) | [日本語](README_ja.md)）

## 🎬 演示视频

**🍽️ 小量餐饮AI：智能语音点餐与支付系统**

[![小量餐饮AI点餐系统演示](https://img.youtube.com/vi/9rN328GPnCM/hqdefault.jpg)](https://youtu.be/9rN328GPnCM)

**🏢 小量智能OA：打通任意OA系统，MCP工具调用实现任务管理**

[![小量智能OA系统演示](https://img.youtube.com/vi/P-HBoCGqPfs/hqdefault.jpg)](https://youtube.com/shorts/P-HBoCGqPfs?feature=share)

> 🎥 点击上方视频缩略图可在YouTube观看完整演示

## 📖 项目介绍

这是量迹AI科技开源的ESP32智能餐饮系统，基于MIT许可证发布，允许任何人免费使用或用于商业用途。

我们致力于将前沿的AI技术与餐饮行业深度结合，通过语音交互、智能支付、MCP协议等技术，为餐厅提供完整的智能化解决方案。同时，我们还扩展了OA办公系统集成功能，通过MCP协议实现企业办公流程的智能化管理。

如果您有任何想法或建议，请随时提出Issues或联系贡献者爽吉QQ：1667911986

## 🙏 致谢与项目渊源

本项目基于虾哥（@78）的优秀开源项目 [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) 开发，在此向虾哥及其团队表示衷心感谢！

**原版小智 vs 小量餐饮版的区别：**

| 特性 | 原版小智 | 小量餐饮版 |
|------|----------|------------|
| **定位** | 通用AI聊天机器人 | 专业餐饮点餐系统 |
| **核心功能** | 语音对话、智能问答 | 语音点餐、菜单展示、支付集成 |
| **显示界面** | 简约对话界面 | 精美菜品展示、营业信息 |
| **业务逻辑** | 开放式对话 | 餐饮业务流程（点餐→支付→出餐） |
| **支付系统** | 无 | 支付宝/微信扫码支付 |
| **管理后台** | 基础配置 | 专业餐厅管理、数据分析 |
| **硬件优化** | 通用设备支持 | 餐饮场景定制（触摸屏、打印机） |
| **OA办公系统** | 无 | MCP协议任务管理、工作流集成 |

我们在虾哥项目的坚实基础上，专门针对餐饮行业的特殊需求进行了深度定制和优化，打造了这个专业的智能餐饮解决方案。

### 🚀 基于MCP协议的全栈餐饮生态

小量餐饮AI系统通过MCP（Model Control Protocol）协议连接硬件设备、后端服务与前端界面，实现从点餐到支付的全流程智能化管理。

**技术栈架构：**
- **硬件终端**：ESP32系列芯片 + 定制化显示屏
- **后端服务**：Django + REST API + MCP协议
- **前端界面**：React.js + Node.js + 响应式设计
- **支付系统**：支付宝/微信支付SDK + 二维码生成

![MCP餐饮生态架构图](docs/mcp-based-graph.jpg)

### ✨ 核心功能特性

#### 🍽️ 智能餐饮功能
- **语音点餐**：支持自然语言点餐，智能推荐菜品
- **菜单展示**：高清彩屏显示菜品图片、价格、营养信息
- **订单管理**：实时订单状态跟踪，支持修改和取消
- **支付集成**：支付宝/微信扫码支付，支持多种支付方式
- **二维码显示**：动态生成支付二维码，支持屏幕显示

#### 🏢 OA办公系统集成
- **任务日程管理**：通过MCP协议调用工具实现任务的创建、删除、修改和查询
- **智能任务分配**：基于AI算法的任务自动分配和优先级排序
- **本周任务总结**：自动生成周报和日报，任务完成情况统计
- **单人任务查询**：快速查询个人任务列表和进度状态
- **会议安排**：智能会议室预订和会议提醒功能
- **工作流审批**：集成企业审批流程，支持多级审批
- **数据同步**：与主流OA系统（钉钉、企业微信、飞书等）无缝对接

#### 🔧 技术能力
- **Wi-Fi / 4G连接**：ML307 Cat.1 4G模块，稳定的网络连接
- **离线语音唤醒**：基于ESP-SR的本地语音识别
- **多协议通信**：WebSocket实时通信 + MQTT消息队列
- **音频处理**：OPUS编解码 + 降噪算法
- **声纹识别**：用户身份识别，个性化服务推荐
- **多语言支持**：中文、英文、日文界面切换

#### 💻 MCP API集成
- **设备控制API**：音量调节、屏幕亮度、LED指示灯
- **支付API**：支付宝/微信支付接口，订单状态同步
- **餐厅管理API**：菜品管理、库存控制、营业数据统计
- **用户管理API**：会员系统、积分管理、消费记录
- **OA办公API**：任务管理、日程安排、工作流审批、报告生成

#### 🎨 定制化硬件显示
- **餐厅主题界面**：可定制的品牌色彩和Logo
- **动态菜品展示**：高分辨率图片轮播，诱人的视觉效果
- **实时信息显示**：等候时间、桌号信息、优惠活动
- **支付状态反馈**：支付进度、成功/失败动画效果

## 🛠️ 硬件平台

### 📱 面包板快速原型

新手学习可参考详细的搭建教程：

👉 [《小量餐饮AI系统搭建指南》](https://ccnphfhqs21z.feishu.cn/wiki/F5krwD16viZoF0kKkvDcrZNYnhb?from=from_copylink)

面包板原型展示：

![面包板原型](docs/v1/wiring2.jpg)

### 🏪 商用级硬件支持（精选推荐）

#### 餐饮专用设备
- **小量智能点餐台**：7寸高清触摸屏 + ESP32-S3 + 4G模块
- **小量桌面助手**：圆形OLED显示 + 360度拾音 + 无线充电
- **小量收银终端**：大屏显示 + 热敏打印 + 扫码枪支持

#### 兼容开发板（70+款）
- <a href="https://oshwhub.com/li-chuang-kai-fa-ban/li-chuang-shi-zhan-pai-esp32-s3-kai-fa-ban" target="_blank">立创·实战派 ESP32-S3 开发板</a>
- <a href="https://github.com/espressif/esp-box" target="_blank">乐鑫 ESP32-S3-BOX3</a>
- <a href="https://docs.m5stack.com/zh_CN/core/CoreS3" target="_blank">M5Stack CoreS3</a>
- <a href="https://docs.m5stack.com/en/atom/Atomic%20Echo%20Base" target="_blank">M5Stack AtomS3R + Echo Base</a>
- <a href="https://www.waveshare.net/shop/ESP32-S3-Touch-AMOLED-1.8.htm" target="_blank">微雪电子 ESP32-S3-Touch-AMOLED-1.8</a>
- <a href="https://github.com/Xinyuan-LilyGO/T-Circle-S3" target="_blank">LILYGO T-Circle-S3</a>
- <a href="https://www.seeedstudio.com/SenseCAP-Watcher-W1-A-p-5979.html" target="_blank">SenseCAP Watcher</a>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="docs/v1/lichuang-s3.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>立创ESP32-S3开发板</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/espbox3.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>乐鑫ESP32-S3-BOX3</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/m5cores3.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>M5Stack CoreS3</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/atoms3r.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>AtomS3R + Echo Base</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/waveshare.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>微雪AMOLED触摸屏</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/sensecap_watcher.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>SenseCAP Watcher</p>
  </div>
</div>

## 💻 软件系统

### ⚡ 快速部署

#### 固件烧录（硬件端）
新手推荐使用预编译固件，免去开发环境配置：

👉 [固件烧录教程](https://ccnphfhqs21z.feishu.cn/wiki/Zpz4wXBtdimBrLk25WdcXzxcnNS)

#### 后端部署（Django）
```bash
# 克隆项目
git clone https://github.com/liangjiai/xiaoliang-catering-backend.git
cd xiaoliang-catering-backend

# 安装依赖
pip install -r requirements.txt

# 数据库迁移
python manage.py migrate

# 启动服务
python manage.py runserver 0.0.0.0:8000
```

#### 前端部署（React + Node.js）
```bash
# 克隆前端项目
git clone https://github.com/liangjiai/xiaoliang-catering-frontend.git
cd xiaoliang-catering-frontend

# 安装依赖
npm install

# 开发模式启动
npm start

# 生产环境构建
npm run build
```

### 🔧 开发环境

**推荐开发工具：**
- **IDE**：Cursor 或 VSCode
- **ESP32开发**：ESP-IDF 插件（SDK 5.4+）
- **后端开发**：PyCharm + Django 4.2+
- **前端开发**：VSCode + React 18+ + Node.js 18+

**系统要求：**
- Linux 系统优于 Windows（编译速度更快）
- 内存：8GB+ 推荐
- 存储：至少20GB可用空间

### 📚 开发者文档

- [自定义硬件适配指南](main/boards/README.md) - 学习如何为小量餐饮系统适配新硬件
- [MCP协议餐饮应用指南](docs/mcp-usage.md) - 了解如何通过MCP协议控制餐饮设备
- [MCP协议技术规范](docs/mcp-protocol.md) - 设备端MCP协议的详细实现
- [WebSocket通信协议文档](docs/websocket.md) - 实时通信协议说明
- [Django后端API文档](docs/django-api.md) - 后端接口详细说明
- [React前端组件文档](docs/react-components.md) - 前端组件使用指南

## 🏪 餐厅配置管理

### 🎛️ 管理后台

如果您已经部署了小量餐饮AI系统，可以通过Web管理后台进行配置：

👉 **管理后台地址**：https://admin.xiaoliang-catering.com

**主要功能：**
- **菜品管理**：添加/编辑菜品信息、图片、价格
- **订单监控**：实时查看订单状态、营业数据
- **设备管理**：硬件设备状态监控、远程控制
- **支付配置**：支付宝/微信支付参数设置
- **用户管理**：会员信息、消费记录、积分管理

👉 [后台操作视频教程](https://www.bilibili.com/video/BV1jUCUY2EKM/)

### 📊 数据分析面板

- **实时营业数据**：今日订单量、营业额、热门菜品
- **顾客行为分析**：点餐偏好、消费习惯、回头客分析
- **设备运行状态**：硬件在线率、网络状态、故障预警
- **财务报表**：日/周/月营业报表，支付渠道分析

## 🔗 生态项目

### 🖥️ 服务端项目
在私有服务器上部署完整的餐饮管理系统：

- **[Django后端服务](https://github.com/liangjiai/xiaoliang-django-server)** - 核心业务逻辑与API
- **[React管理后台](https://github.com/liangjiai/xiaoliang-react-admin)** - 餐厅管理界面
- **[Node.js消息服务](https://github.com/liangjiai/xiaoliang-nodejs-gateway)** - 实时通信网关

### 📱 客户端应用
多平台客户端支持：

- **[小量点餐小程序](https://github.com/liangjiai/xiaoliang-miniprogram)** - 微信小程序版本
- **[小量Android客户端](https://github.com/liangjiai/xiaoliang-android)** - 安卓原生应用
- **[小量iOS客户端](https://github.com/liangjiai/xiaoliang-ios)** - iOS原生应用

### 🔌 硬件扩展
支持更多硬件平台：

- **[树莓派客户端](https://github.com/liangjiai/xiaoliang-raspberry)** - 大屏显示终端
- **[蓝牙模块支持](https://github.com/liangjiai/xiaoliang-bluetooth)** - 近场通信扩展
- **[热敏打印驱动](https://github.com/liangjiai/xiaoliang-printer)** - 小票打印支持

## 📈 项目发展

### 🌟 Star History
<a href="https://star-history.com/#liangjiai/xiaoliang-catering&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date" />
 </picture>
</a>

### 🏆 商用案例

已成功部署的餐厅案例：
- **海底捞智能门店**：北京/上海多家门店
- **星巴克概念店**：深圳南山科技园
- **小龙坎火锅**：成都春熙路旗舰店
- **喜茶新零售店**：广州天河城

---

## 📞 联系我们

**云南量迹科技有限公司**  
- 🟩 微信：a15186877707  
- 🏢 纳税人识别号：91530112MAEM9FJDXJ  
- 📍 注册地址：云南省昆明市西山区永昌街道办事处云纺国际商厦 B 座 1406 号  
- ☎️ 电话：18585164448  
- 🏦 开户行：富滇银行股份有限公司昆明新民支行  
- 💳 账号：120871127010000006722

---

*© 2024 云南量迹科技有限公司. 保留所有权利. | MIT License*
