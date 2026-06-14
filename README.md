# 中孜会计 — 企业官网

现代化专业企业官网，主打 **AI 智能审计** 与 **ERP 系统集成** 服务。

## 页面结构

| 页面 | 文件 | 说明 |
|------|------|------|
| 首页 | `index.html` | 品牌展示、核心服务概览、优势介绍 |
| 关于我们 | `about.html` | 企业简介、使命愿景、发展历程 |
| 服务项目 | `services.html` | AI 审计、ERP 集成、延伸服务详情 |
| 联系我们 | `contact.html` | 联系方式、在线咨询表单 |

## 设计特点

- 深蓝 + 金色配色，专业稳重
- 响应式布局，适配手机 / 平板 / 电脑
- 固定导航栏 + 移动端汉堡菜单
- 滚动渐入动画
- 无需构建，直接打开即可预览

## 本地预览

直接用浏览器打开 `index.html`，或使用本地服务器：

```bash
# Python 3
python -m http.server 8080

# 然后访问 http://localhost:8080
```

## 自定义

- **公司名称 / 文案**：编辑各 HTML 文件中的文字内容
- **配色**：修改 `css/style.css` 顶部 `:root` 变量
- **联系方式**：更新 `contact.html` 及页脚中的电话、邮箱、地址

## 技术栈

- HTML5
- CSS3（Flexbox + Grid）
- 原生 JavaScript
- Google Fonts（Noto Sans / Serif SC）
