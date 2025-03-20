# Mahjong 在线游戏网站

这是一个响应式的麻将在线游戏网站，针对SEO优化，提供了优雅的用户界面和麻将游戏的嵌入式体验。网站使用了现代的HTML和CSS技术，包括Tailwind CSS框架，确保在各种设备上都能提供出色的用户体验。

## 功能

- 响应式设计，适配桌面和移动设备
- 苹果风格的界面设计，使用优雅的色彩方案
- 嵌入式麻将游戏iframe
- SEO优化的HTML结构，包含适当的元标记
- 快速加载性能
- 无障碍设计元素
- 可打印的内容样式
- 支持深色模式偏好
- 详细的麻将游戏介绍和历史背景

## 文件结构

- `index.html` - 主HTML文件，包含网站结构和Tailwind内联样式
- `style.css` - 附加CSS样式文件，提供特殊效果和增强功能
- `favicon.svg` - 网站图标文件

## 技术栈

- HTML5
- CSS3 (含动画和媒体查询)
- Tailwind CSS (通过CDN加载)
- 原生JavaScript (用于移动菜单交互)

## 如何部署

### 方法一：直接部署到网络服务器

1. 将所有文件上传到您的网络服务器
2. 确保域名 `pixelnostalgia.online` 指向您的服务器
3. 确保服务器配置正确处理HTML文件

### 方法二：使用GitHub Pages

1. 创建一个GitHub仓库
2. 将所有文件上传到仓库
3. 启用GitHub Pages功能
4. 可选：配置自定义域名 `pixelnostalgia.online`

### 方法三：使用Netlify或Vercel

1. 创建一个GitHub/GitLab仓库并上传所有文件
2. 连接您的Netlify或Vercel账户到该仓库
3. 部署网站
4. 配置自定义域名

## SEO优化

本网站已经包含了以下SEO元素：

- 优化的标题和元描述
- 语义化HTML结构
- 适当的标题标签层次结构 (H1, H2, H3)
- 规范链接(canonical URL)
- 响应式设计(移动友好)
- 关键词优化

## 自定义

### 更改游戏

如果您想更改嵌入的游戏，只需修改iframe的src属性：

```html
<iframe src="您的新游戏URL" frameborder="0" width="100%" height="100%" allowfullscreen></iframe>
```

### 更改配色方案

您可以通过修改Tailwind配置中的颜色来更改网站的配色方案：

```javascript
theme: {
    extend: {
        colors: {
            apple: {
                light: '#您的颜色代码',
                gray: '#您的颜色代码',
                dark: '#您的颜色代码',
                blue: '#您的颜色代码',
                pink: '#您的颜色代码',
                purple: '#您的颜色代码',
                orange: '#您的颜色代码'
            }
        }
    }
}
```

## 许可

本项目代码可自由使用于个人和商业项目。请注意，嵌入的游戏内容可能受第三方许可条款约束。

## 联系

如有问题或建议，请联系网站管理员。 