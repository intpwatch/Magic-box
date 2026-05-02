# 项目源代码

这是一个多端应用项目，包含以下模块：

## 项目结构

### APP后端
- 后端服务器代码
- 管理后台界面

### APP手机端
- 基于 uni-app 开发的移动端应用
- 支持多平台（iOS/Android）
- 包含多个功能模块：激活、功能详情、扫雷游戏、个人中心等

### PC版客户端
- Windows 桌面客户端
- 使用 Python 开发
- 集成 WebView2 组件

### PC版本服务器
- PC 端配套服务器
- 提供 API 接口和插件支持

## 使用说明

### APP手机端
```bash
# 安装依赖
npm install

# 运行开发环境
npm run dev
```

### 后端服务
```bash
# 安装 Python 依赖
pip install -r requirements.txt

# 运行服务器
python app_server.py
```

### PC客户端
```bash
# 安装依赖
pip install -r requirements.txt

# 运行客户端
python 百宝箱客户端4.1正式版.py
```

## 注意事项

- 本仓库不包含编译后的二进制文件
- 数据库文件和密钥文件已排除
- node_modules 等依赖包需要自行安装
