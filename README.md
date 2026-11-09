# 个人简历与摄影预约页

王莺璇 Yingxuan Wang

使用原生 HTML、CSS 与 JavaScript 实现的个人展示网页，包含中英双语简历和独立摄影预约页。

| 页面 | 内容 | 入口 |
| --- | --- | --- |
| `index.html` | 中文简历、英文切换及 A4 打印样式 | [在线简历](https://wangxy009.github.io) |
| `yuepai.html` | 摄影预约流程与客户需求单页面 | [摄影预约页](https://wangxy009.github.io/yuepai.html) |

简历内容沿用仓库所记录的《简历 1019.pdf》（2026-10-19）版本。本次作品集整理未改动个人履历页面。

## 本地查看

在仓库根目录运行：

```bash
python3 -m http.server 8000
```

访问 `http://localhost:8000`，或直接打开相应 HTML 文件。无需构建和安装前端依赖。

## 更新与打印

`index.html` 的 `#cv-zh` 与 `#cv-en` 分别保存中文、英文内容，更新履历时应同步核对。页面右上角“打印 / 导出 PDF”调用浏览器打印，提供 A4 样式。

仓库由 GitHub Pages 托管。摄影页面按当前静态页面实现展示，实际预约接收方式以页面配置为准。完整项目导航见 [GitHub 个人主页](https://github.com/Wangxy009)。
