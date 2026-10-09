# 《信息系统分析与设计》数字教材

苏州大学《信息系统分析与设计》（ISAD）课程配套资源，面向信息资源管理专业本科生。教材以信息系统分析与设计方法为主线，结合智能体与低代码（扣子 Coze）案例和实践。

> 在线站点：<https://dsdh-python.github.io/ISAD/>

## 内容

| 路径 | 内容 |
| --- | --- |
| [`html教材/`](html教材/) | 教材门户及第 1–9 章 |
| [`games/`](games/) | 对应各章的互动练习 |
| [`pages/appendix.html`](pages/appendix.html) | 课程附录正文（根目录 `appendix.html` 保留旧链接跳转） |
| [`style.css`](style.css)、[`app.js`](app.js) | 全站样式与交互 |
| [`images/`](images/)、[`media/`](media/) | 教材配图、操作截图与案例素材 |
| [`前沿文献_候选清单.md`](前沿文献_候选清单.md)、[`AI蓝皮书.md`](AI蓝皮书.md) | 补充阅读资料 |
| [`智能体创新实践汇编_案例提取.md`](智能体创新实践汇编_案例提取.md)、[`pages/智能体创新实践汇编_思维导图.html`](pages/智能体创新实践汇编_思维导图.html) | 智能体案例资料 |
| [`职业与资格速查表.docx`](职业与资格速查表.docx) | 职业与资格参考 |

## 使用

- 从 [`html教材/index.html`](html教材/index.html) 浏览教材。
- 在 [`games/`](games/) 中打开 `game_chNN.html` 体验对应章节练习。
- 根目录 [`index.html`](index.html) 会跳转到教材门户；根目录 `ch01.html` 至 `ch09.html` 保留旧链接并跳转至对应章节。
- 完整附录和思维导图收纳在 [`pages/`](pages/)；根目录 `appendix.html` 保留兼容跳转，旧链接无需更改。

教材章节位于 `html教材/`，通过相对路径引用根目录中的样式、脚本、图片、媒体和练习。请勿删除仍被页面引用的资源。

## 许可

- 课程材料的版权与使用限制见根目录 [`LICENSE`](LICENSE)。
- 教材中派生自 yeasy《智能体 AI 权威指南》v1.0.0 的内容按 CC BY-NC-SA 4.0 使用。再利用时须遵守署名、非商业使用和相同方式共享要求：<https://creativecommons.org/licenses/by-nc-sa/4.0/>。

## 维护

修改后检查网页资源路径和章节导航，并运行：

```bash
git status
git diff --check
```

推送到 `main` 后，GitHub Actions 会自动发布站点。
