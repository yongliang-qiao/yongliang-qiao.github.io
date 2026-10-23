# 原风格主页小幅优化记录（2026-10）

本版本以用户上传的 **原始 Jekyll Academic Pages 主题**为基础，不采用重新设计的独立主题：

- 未修改网站主题 CSS、原头像、导航布局、原栏目及其排列顺序。
- 更新首页简介，匹配吉林大学教授、博士生导师身份；更正联系人邮箱与机构名称。
- 修正 Google Scholar 占位地址为已确认的公开主页。
- 新增 22 条 2024–2026 年论文/会议/预印本记录，更新 1 条已有的 ACM Transactions on the Web 论文年份；每条有出版社 DOI 或检索页面链接。
- 原论文列表中重复的 paper1–paper20 示例元数据不再在首页/论文页面重复展示，但 PDF 文件与历史页面仍保留；修正其 permalink 避免覆盖同名 PDF。
- 论文在首页保留原 h3 题目＋h4 灰色引用形式，先显示较新成果，后显示早期论文。

重要：会议论文、已发表期刊论文、仅预印本在每条引用中标明；2026 年《Plants》文章网页于 2025-12-22 在线发布，但属于 2026 年第15卷第1期。

## 部署
GitHub 仓库 yongliang-qiao/yongliang-qiao.github.io 中**上传本文件夹内容到根目录**，而不是将外层目录作为一个文件夹上传。静态资源、原有 `_includes`、Jekyll 模板与 `_publications` 已一并保留。选择 GitHub Pages 中适合您当前仓库的发布来源；此版依赖原站 Jekyll 构建。

论文条目可以在 `_publications/2026-*.md`、`2025-*.md`、`2024-*.md` 中直接修改。`_pages/about.md` 的列表循环负责展示顺序。

来源参考：吉林大学教师主页 https://cbae.jlu.edu.cn/info/1130/8619.htm ，DBLP https://dblp.org/pid/153/4711.html 及每条 DOI/出版社页面。
