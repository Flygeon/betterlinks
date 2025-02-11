# betterlinks——链接净化器
# Ultimate Link Cleaner 用户脚本手册

![Tampermonkey](https://img.shields.io/badge/Tampermonkey-Supported-brightgreen) 
![Chrome](https://img.shields.io/badge/Chrome-Supported-brightgreen) 
![Firefox](https://img.shields.io/badge/Firefox-Supported-brightgreen)

> 智能清理网页中被干扰的URL，自动生成可点击链接 + 剪贴板净化

## 📜 功能概览

### 🌐 页面链接修复
- **动态锚点转换**  
  自动识别文本中的干扰链接，转换为可点击超链接
- **实时内容监控**  
  支持动态加载内容（如评论区、AJAX更新）
- **智能协议修复**  
  修复 `hXXtps://` `htTp_删://` 等变形协议
- **国际化处理**  
  自动过滤非ASCII字符，兼容标准域名规范

### 📋 剪贴板清理
- **白名单过滤**  
  仅保留 `a-zA-Z0-9-._~:/?#[]@!$&'()*+,;=` 合法字符
- **协议自动修复**  
  智能修复残缺协议头（http/https）
- **编码保留**  
  保留 `%20` 等合法URL编码
- **无缝集成**  
  不修改原始页面内容，仅在复制时生效

## 🛠️ 安装步骤

1. 安装用户脚本管理器：
   - Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Firefox: [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/)

2. [点击安装脚本](https://your-domain.com/link-cleaner.user.js)  
   （或手动复制代码到Tampermonkey）

## 🖥️ 使用示例

### 页面展示效果
```text
原始文本：
请访问 ht_tps://exa测mple.删com/路径

转换后：
请访问 https://example.com/" target="_blank" style="color:#06c;">https://example.com/路径">https://example.com/路径
