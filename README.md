# The Web3 Intro - 官方展示网站

## 🌐 网站地址
- **GitHub Pages**: https://the-web3.github.io/the-web3-intro/  
- **自定义域名**: https://intro.thewebthree.xyz

## 📖 项目简介
The Web3 社区官方展示网站，包含完整的课程介绍、技术培训内容、产品投研课程和联系方式等页面。

## 📁 项目结构
```
├── index.html                                    # 主展示页面（首页）
├── course-testing-development.html              # 区块链测试开发课程
├── course-tech-development.html                 # 技术开发详细课程大纲  
├── course-product-research.html                 # 产品投研课程大纲
├── assets/                                       # 资源文件夹
│   ├── logos/                                    # Logo文件
│   │   ├── logo_TW.png                          # TW Logo
│   │   └── logo_party_white.png                 # 白色版本Logo
│   ├── social/                                   # 社交媒体资源
│   │   ├── Twitter.png                          # Twitter图标
│   │   ├── wechat.png                           # 微信图标
│   │   ├── X_Theweb3.png                        # Twitter二维码
│   │   ├── Official Website.png                 # 官网二维码
│   │   ├── WechatIMG650.jpg                     # 微信公众号二维码
│   │   └── wachat.jpg                           # 微信个人号二维码
│   └── documents/                               # 文档资料
│       └── The Web3 社区如何赋能区块链未来发展.pdf
├── CNAME                                        # 自定义域名配置
└── .github/workflows/deploy.yml                # GitHub Pages自动部署
```

## 🚀 部署说明

### 自动部署
项目已配置 GitHub Actions，每次推送到 `main` 分支会自动部署到 GitHub Pages。

### 自定义域名配置
1. **DNS设置**（已配置）:
   ```
   记录类型：CNAME
   主机记录：intro  
   记录值：the-web3.github.io
   ```

2. **GitHub Pages设置**:
   - 仓库 Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - 自定义域名会自动从CNAME文件读取

## 🌐 页面导览
- **首页** (`index.html`) - 社区介绍和概览
- **区块链测试开发课程** (`course-testing-development.html`) - 完整的技术培训课程
- **技术开发课程大纲** (`course-tech-development.html`) - 详细的开发学习路径
- **产品投研课程** (`course-product-research.html`) - 区块链产品和投资研究课程

## 💡 技术特性
- ✅ 响应式设计，完美支持移动端
- ✅ 现代化CSS动画和交互效果  
- ✅ 真实社交媒体二维码集成
- ✅ 优化的SEO和页面性能
- ✅ 跨浏览器兼容性
- ✅ GitHub Actions自动化部署

## 📞 联系方式
- 🌐 **官网**: [thewebthree.xyz](https://thewebthree.xyz)
- 🐦 **Twitter**: [@0xtheweb3](https://twitter.com/0xtheweb3)  
- 💬 **微信**: 扫描页面二维码添加
- 📱 **公众号**: 扫描页面二维码关注

## 🛠 本地开发
```bash
# 克隆仓库
git clone https://github.com/the-web3/the-web3-intro.git

# 进入目录
cd the-web3-intro

# 直接用浏览器打开 index.html
open index.html
```

## 📝 更新内容
- 重构项目文件结构，按类型整理资源文件
- 添加GitHub Actions自动部署配置
- 配置自定义域名支持
- 优化README文档和项目说明
- 优化导航栏设计，增强视觉效果和用户体验

---
*The Web3 Community Official Website*