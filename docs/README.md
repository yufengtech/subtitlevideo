# 即幕视频 - 技术支持网站

这是即幕视频（SubtitleVideo）应用的官方技术支持网站。

## 网站功能

- **多语言支持**：中文/英文自由切换
- **常见问题解答**：详细的问题解决方案
- **联系我们**：多种联系方式和反馈表单
- **隐私政策**：完整的隐私保护说明
- **使用教程**：详细的应用使用指南

## 部署说明

### GitHub Pages 部署

1. 将 `docs` 文件夹推送到您的 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 `docs` 文件夹作为源
4. 访问 `https://yourusername.github.io/FTKVideo/` 查看网站

### 自定义配置

1. 修改 `contact.html` 中的 GitHub 链接为您的实际仓库地址
2. 更新邮箱地址为您的真实联系邮箱
3. 在 `Info.plist` 中更新 `ITSSupportURL` 为您的实际网站地址

## 文件结构

```
docs/
├── index.html          # 主页
├── faq.html           # 常见问题
├── contact.html       # 联系我们
├── privacy.html       # 隐私政策
├── tutorial.html      # 使用教程
└── README.md         # 说明文档
```

## App Store 配置

在 App Store Connect 中：

1. 在应用信息页面填写技术支持网址
2. 确保网址与 `Info.plist` 中的 `ITSSupportURL` 一致
3. 审核期间苹果会检查网站内容的完整性

## 维护建议

- 定期更新常见问题解答
- 及时回复用户反馈邮件
- 保持网站内容与应用功能同步
- 监控网站访问情况和用户需求

## 技术支持

如需修改网站内容或功能，请：

1. 编辑对应的 HTML 文件
2. 测试中英文切换功能
3. 确保移动端显示正常
4. 重新部署到 GitHub Pages 