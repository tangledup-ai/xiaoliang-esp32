# LiangJi AI XiaoLiang Catering Edition | MCP-based Smart Restaurant System

(English | [中文](README.md) | [日本語](README_ja.md))

## 🎬 Demo Videos

**🍽️ XiaoLiang Catering AI: Smart Voice Ordering & Payment System**

[![XiaoLiang Catering AI Demo](https://img.youtube.com/vi/9rN328GPnCM/hqdefault.jpg)](https://youtu.be/9rN328GPnCM)

**🏢 XiaoLiang Smart OA: Integrate Any OA System with MCP Tool Calls for Task Management**

[![XiaoLiang Smart OA Demo](https://img.youtube.com/vi/P-HBoCGqPfs/hqdefault.jpg)](https://youtube.com/shorts/P-HBoCGqPfs?feature=share)

> 🎥 Click the video thumbnails above to watch full demos on YouTube

## 📖 Introduction

This is an open-source ESP32 smart restaurant system by LiangJi AI Technology, released under the MIT license, allowing free use for commercial or personal purposes.

We are committed to deeply integrating cutting-edge AI technology with the catering industry, providing complete intelligent solutions for restaurants through voice interaction, smart payment, and MCP protocol technologies. Additionally, we have extended OA office system integration capabilities, enabling intelligent management of enterprise office workflows through MCP protocols.

If you have any ideas or suggestions, please feel free to raise Issues or contact contributor ShuangJi QQ: 1667911986

## 🙏 Acknowledgments & Project Origins

This project is based on the excellent open-source project [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) by Xiage (@78). We extend our heartfelt gratitude to Xiage and his team!

**Original XiaoZhi vs XiaoLiang Catering Edition Comparison:**

| Feature | Original XiaoZhi | XiaoLiang Catering Edition |
|---------|------------------|----------------------------|
| **Positioning** | General AI Chatbot | Professional Restaurant Ordering System |
| **Core Functions** | Voice conversation, Smart Q&A | Voice ordering, Menu display, Payment integration |
| **Display Interface** | Simple conversation UI | Beautiful dish showcase, Business information |
| **Business Logic** | Open-ended conversations | Restaurant workflow (Order→Pay→Serve) |
| **Payment System** | None | Alipay/WeChat QR code payment |
| **Management Panel** | Basic configuration | Professional restaurant management, Data analytics |
| **Hardware Optimization** | General device support | Catering-specific customization (Touchscreen, Printer) |
| **OA Office System** | None | MCP protocol task management, Workflow integration |

Building upon Xiage's solid foundation, we have deeply customized and optimized the system specifically for the unique needs of the catering industry, creating this professional smart restaurant solution.

### 🚀 Full-Stack Catering Ecosystem Based on MCP Protocol

The XiaoLiang Catering AI system connects hardware devices, backend services, and frontend interfaces through the MCP (Model Control Protocol), enabling end-to-end intelligent management from ordering to payment.

**Technology Stack:**
- **Hardware Terminal**: ESP32 series chips + customized displays
- **Backend Service**: Django + REST API + MCP protocol
- **Frontend Interface**: React.js + Node.js + responsive design
- **Payment System**: Alipay/WeChat Pay SDK + QR code generation

![MCP Catering Ecosystem Architecture](docs/mcp-based-graph.jpg)

### ✨ Core Features

#### 🍽️ Smart Restaurant Functions
- **Voice Ordering**: Natural language ordering with intelligent dish recommendations
- **Menu Display**: HD color screen showing dish images, prices, and nutritional information
- **Order Management**: Real-time order status tracking with modification and cancellation support
- **Payment Integration**: Alipay/WeChat QR code payment with multiple payment methods
- **QR Code Display**: Dynamic payment QR code generation with screen display support

#### 🏢 OA Office System Integration
- **Task & Schedule Management**: Create, delete, modify, and query tasks through MCP protocol tool calls
- **Intelligent Task Assignment**: AI-based automatic task allocation and priority sorting
- **Weekly Task Summary**: Auto-generate weekly and daily reports with task completion statistics
- **Individual Task Query**: Quick personal task list and progress status queries
- **Meeting Arrangement**: Smart meeting room booking and reminder functions
- **Workflow Approval**: Integrated enterprise approval processes with multi-level approval support
- **Data Synchronization**: Seamless integration with mainstream OA systems (DingTalk, WeChat Work, Feishu, etc.)

#### 🔧 Technical Capabilities
- **Wi-Fi / 4G Connectivity**: ML307 Cat.1 4G module for stable network connection
- **Offline Voice Wake-up**: Local voice recognition based on ESP-SR
- **Multi-protocol Communication**: WebSocket real-time communication + MQTT message queue
- **Audio Processing**: OPUS codec + noise reduction algorithms
- **Speaker Recognition**: User identity recognition for personalized service recommendations
- **Multi-language Support**: Chinese, English, Japanese interface switching

#### 💻 MCP API Integration
- **Device Control API**: Volume adjustment, screen brightness, LED indicators
- **Payment API**: Alipay/WeChat payment interfaces, order status synchronization
- **Restaurant Management API**: Dish management, inventory control, business data statistics
- **User Management API**: Membership system, points management, consumption records
- **OA Office API**: Task management, scheduling, workflow approval, report generation

#### 🎨 Customized Hardware Display
- **Restaurant Theme Interface**: Customizable brand colors and logos
- **Dynamic Dish Display**: High-resolution image carousel with appetizing visual effects
- **Real-time Information Display**: Waiting time, table numbers, promotional activities
- **Payment Status Feedback**: Payment progress, success/failure animation effects

## 🛠️ Hardware Platform

### 📱 Breadboard Rapid Prototyping

Beginners can refer to the detailed setup tutorial:

👉 ["XiaoLiang Catering AI System Setup Guide"](https://ccnphfhqs21z.feishu.cn/wiki/F5krwD16viZoF0kKkvDcrZNYnhb?from=from_copylink)

Breadboard prototype demonstration:

![Breadboard Prototype](docs/v1/wiring2.jpg)

### 🏪 Commercial-Grade Hardware Support (Selected Recommendations)

#### Restaurant-Specific Devices
- **XiaoLiang Smart Ordering Station**: 7-inch HD touchscreen + ESP32-S3 + 4G module
- **XiaoLiang Desktop Assistant**: Circular OLED display + 360-degree microphone + wireless charging
- **XiaoLiang POS Terminal**: Large screen display + thermal printer + barcode scanner support

#### Compatible Development Boards (70+ models)
- <a href="https://oshwhub.com/li-chuang-kai-fa-ban/li-chuang-shi-zhan-pai-esp32-s3-kai-fa-ban" target="_blank">LiChuang ESP32-S3 Development Board</a>
- <a href="https://github.com/espressif/esp-box" target="_blank">Espressif ESP32-S3-BOX3</a>
- <a href="https://docs.m5stack.com/zh_CN/core/CoreS3" target="_blank">M5Stack CoreS3</a>
- <a href="https://docs.m5stack.com/en/atom/Atomic%20Echo%20Base" target="_blank">M5Stack AtomS3R + Echo Base</a>
- <a href="https://www.waveshare.net/shop/ESP32-S3-Touch-AMOLED-1.8.htm" target="_blank">Waveshare ESP32-S3-Touch-AMOLED-1.8</a>
- <a href="https://github.com/Xinyuan-LilyGO/T-Circle-S3" target="_blank">LILYGO T-Circle-S3</a>
- <a href="https://www.seeedstudio.com/SenseCAP-Watcher-W1-A-p-5979.html" target="_blank">SenseCAP Watcher</a>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="docs/v1/lichuang-s3.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>LiChuang ESP32-S3 Dev Board</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/espbox3.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>Espressif ESP32-S3-BOX3</p>
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
    <p>Waveshare AMOLED Touch</p>
  </div>
  <div style="text-align: center;">
    <img src="docs/v1/sensecap_watcher.jpg" style="width: 100%; max-width: 200px; border-radius: 8px;" />
    <p>SenseCAP Watcher</p>
  </div>
</div>

## 💻 Software System

### ⚡ Quick Deployment

#### Firmware Flashing (Hardware)
Beginners are recommended to use pre-compiled firmware to avoid development environment setup:

👉 [Firmware Flashing Tutorial](https://ccnphfhqs21z.feishu.cn/wiki/Zpz4wXBtdimBrLk25WdcXzxcnNS)

#### Backend Deployment (Django)
```bash
# Clone project
git clone https://github.com/liangjiai/xiaoliang-catering-backend.git
cd xiaoliang-catering-backend

# Install dependencies
pip install -r requirements.txt

# Database migration
python manage.py migrate

# Start service
python manage.py runserver 0.0.0.0:8000
```

#### Frontend Deployment (React + Node.js)
```bash
# Clone frontend project
git clone https://github.com/liangjiai/xiaoliang-catering-frontend.git
cd xiaoliang-catering-frontend

# Install dependencies
npm install

# Development mode
npm start

# Production build
npm run build
```

### 🔧 Development Environment

**Recommended Development Tools:**
- **IDE**: Cursor or VSCode
- **ESP32 Development**: ESP-IDF plugin (SDK 5.4+)
- **Backend Development**: PyCharm + Django 4.2+
- **Frontend Development**: VSCode + React 18+ + Node.js 18+

**System Requirements:**
- Linux system preferred over Windows (faster compilation)
- Memory: 8GB+ recommended
- Storage: At least 20GB available space

### 📚 Developer Documentation

- [Custom Hardware Adaptation Guide](main/boards/README.md) - Learn how to adapt new hardware for XiaoLiang catering system
- [MCP Protocol Catering Application Guide](docs/mcp-usage.md) - Learn how to control catering devices via MCP protocol
- [MCP Protocol Technical Specification](docs/mcp-protocol.md) - Detailed implementation of device-side MCP protocol
- [WebSocket Communication Protocol Documentation](docs/websocket.md) - Real-time communication protocol specification
- [Django Backend API Documentation](docs/django-api.md) - Detailed backend interface documentation
- [React Frontend Component Documentation](docs/react-components.md) - Frontend component usage guide

## 🏪 Restaurant Configuration Management

### 🎛️ Management Dashboard

If you have deployed the XiaoLiang Catering AI system, you can configure it through the web management dashboard:

👉 **Management Dashboard**: https://admin.xiaoliang-catering.com

**Main Features:**
- **Dish Management**: Add/edit dish information, images, prices
- **Order Monitoring**: Real-time order status viewing, business data
- **Device Management**: Hardware device status monitoring, remote control
- **Payment Configuration**: Alipay/WeChat payment parameter settings
- **User Management**: Member information, consumption records, points management

👉 [Backend Operation Video Tutorial](https://www.bilibili.com/video/BV1jUCUY2EKM/)

### 📊 Data Analytics Dashboard

- **Real-time Business Data**: Daily orders, revenue, popular dishes
- **Customer Behavior Analysis**: Ordering preferences, consumption habits, returning customer analysis
- **Device Operation Status**: Hardware online rate, network status, fault warnings
- **Financial Reports**: Daily/weekly/monthly business reports, payment channel analysis

## 🔗 Ecosystem Projects

### 🖥️ Server-side Projects
Deploy complete restaurant management system on private servers:

- **[Django Backend Service](https://github.com/liangjiai/xiaoliang-django-server)** - Core business logic and APIs
- **[React Management Dashboard](https://github.com/liangjiai/xiaoliang-react-admin)** - Restaurant management interface
- **[Node.js Message Service](https://github.com/liangjiai/xiaoliang-nodejs-gateway)** - Real-time communication gateway

### 📱 Client Applications
Multi-platform client support:

- **[XiaoLiang Ordering Mini Program](https://github.com/liangjiai/xiaoliang-miniprogram)** - WeChat Mini Program version
- **[XiaoLiang Android Client](https://github.com/liangjiai/xiaoliang-android)** - Native Android application
- **[XiaoLiang iOS Client](https://github.com/liangjiai/xiaoliang-ios)** - Native iOS application

### 🔌 Hardware Extensions
Support for more hardware platforms:

- **[Raspberry Pi Client](https://github.com/liangjiai/xiaoliang-raspberry)** - Large screen display terminal
- **[Bluetooth Module Support](https://github.com/liangjiai/xiaoliang-bluetooth)** - Near-field communication extension
- **[Thermal Printer Driver](https://github.com/liangjiai/xiaoliang-printer)** - Receipt printing support

## 📈 Project Development

### 🌟 Star History
<a href="https://star-history.com/#liangjiai/xiaoliang-catering&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=liangjiai/xiaoliang-catering&type=Date" />
 </picture>
</a>

### 🏆 Commercial Cases

Successfully deployed restaurant cases:
- **Haidilao Smart Stores**: Multiple locations in Beijing/Shanghai
- **Starbucks Concept Store**: Shenzhen Nanshan Technology Park
- **Xiaolongkan Hotpot**: Chengdu Chunxi Road flagship store
- **Hey Tea New Retail Store**: Guangzhou Tianhe City

---

## 📞 Contact Us

**Yunnan Liangji Technology Co., Ltd.**
- 🌐 Website: https://www.liangjiai.com
- 📧 Email: contact@liangjiai.com
- 📱 Phone: +86 18585164448
- 🏢 Registered Address: Room 1406, Block B, Yunfang International Building, Yongchang Subdistrict Office, Xishan District, Kunming, Yunnan, China
- 🏦 Bank: Fudian Bank Co., Ltd., Kunming Xinmin Branch
- 💳 Account Number: 120871127010000006722
- 🧾 Taxpayer Identification Number: 91530112MAEM9FJDXJ

**Technical Support Hours:** Weekdays 9:00-18:00 (China Standard Time)

---

*© 2024 Yunnan Liangji Technology Co., Ltd. All rights reserved | MIT License* 
