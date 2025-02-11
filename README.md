# betterlinks——链接净化器

[![GitHub license](https://img.shields.io/github/license/Flygeon/betterlinks.svg?style=flat-square&color=4285dd&logo=github)](https://github.com/Flygeon/betterlinks/)
[![GitHub Star](https://img.shields.io/github/stars/Flygeon/betterlinks.svg?style=flat-square&label=Star&color=4285dd&logo=github)](https://github.com/Flygeon/betterlinks/)
[![GitHub Fork](https://img.shields.io/github/forks/Flygeon/betterlinks.svg?style=flat-square&label=Fork&color=4285dd&logo=github)](https://github.com/Flygeon/betterlinks/)

> 智能清理网页中被干扰的URL，自动生成可点击链接。
> 去除复制链接的干扰文本

## 📜 功能概览

### 🌐 页面链接修复
- **动态锚点转换**  
  自动识别网页中的链接，转换为超链接
- **实时内容监控**  
  支持动态加载内容（如评论区、AJAX更新）
- **国际化处理**  
  自动过滤非ASCII字符，兼容标准域名规范

### 📋 剪贴板清理
- **白名单过滤**  
  仅保留 `a-zA-Z0-9-._~:/?#[]@!$&'()*+,;=` 合法字符
- **编码保留**  
  保留 `%20` 等合法URL编码
- **无缝集成**  
  不修改原始页面内容，仅在复制时生效

## 🛠️ 安装步骤

1.[点击安装脚本](https://your-domain.com/link-cleaner.user.js)  
   （或手动复制代码到Tampermonkey）
