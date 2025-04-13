# YouChat 网页聊天系统

YouChat是一个基于Web的聊天应用，支持多种交互方式，包括文字、表情、图片、音频和视频通信，并集成了AI助手功能。

## 功能特点

- **用户管理**
  - 用户注册和登录
  - 个人资料管理（头像、签名等）
  
- **即时通讯**
  - 文本消息发送与接收
  - 表情包支持
  - 图片、音频、视频文件分享
  - 加密消息传输

- **智能助手**
  - 集成AI聊天功能
  - 基于GPT模型的智能对话

- **多媒体功能**
  - 视频录制与分享
  - 音频录制与分享

## 系统要求

- Python 3.0及以上版本
- 现代Web浏览器（Chrome、Firefox、Edge等）

## 安装步骤

1. 克隆仓库到本地
   ```
   git clone https://github.com/your-username/YouChat.git
   cd YouChat
   ```

2. 安装依赖库
   ```
   pip install flask flask-socketio cryptography flask-cors
   ```

3. 配置AI功能（可选）
   - 获取OpenAI API密钥
   - 在系统环境变量中设置`OPENAI_API_KEY`

## 运行应用

1. 启动服务器
   ```
   python sever/sever.py
   ```

2. 启动聊天服务
   ```
   python sever/chat.py
   ```

3. 启动AI服务（可选）
   ```
   python sever/ai.py
   ```

4. 在浏览器中访问应用
   - 登录页面：打开`login/login.html`
   - 注册页面：打开`register/register.html`

## 目录结构

- `app/` - 主要聊天界面和功能
- `ai/` - AI助手功能
- `login/` - 用户登录相关
- `register/` - 用户注册相关
- `my_info/` - 用户信息管理
- `sever/` - 后端服务器代码
  - `sever.py` - 主要服务器
  - `chat.py` - 聊天功能服务
  - `ai.py` - AI功能服务
- `audio_info/` - 音频处理功能
- `video_info/` - 视频处理功能

## 安全特性

- 消息加密传输
- 用户认证与授权
- 安全的文件上传处理

## 注意事项

1. 该项目开源部分为最初版本，删减了数据库、安全校验和部分AI模块内容
2. 若需要完整版，请联系作者
3. 请勿将真实的API密钥提交到代码仓库中

## 技术栈

- 前端：HTML, CSS, JavaScript
- 后端：Python, Flask, SocketIO
- 加密：Cryptography库
- AI功能：OpenAI API

## 许可证

[添加您的许可证信息]

## 联系方式

若需要完整版或有任何问题，请联系作者。
