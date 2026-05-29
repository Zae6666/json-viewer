# JSON Viewer

一个轻量级的在线 JSON 可视化工具，纯前端实现，单文件无依赖。

**在线使用**: [https://zae6666.github.io/json-viewer](https://zae6666.github.io/json-viewer)

## 功能特性

- **树形可视化** — 折叠/展开的树状结构，清晰展示 JSON 层级
- **语法高亮** — key、string、number、boolean、null 不同颜色区分
- **搜索过滤** — 实时搜索 key 和 value，自动展开匹配节点
- **JSONPath 查询** — 支持 `$.store.book[0].author` 等路径跳转
- **内联编辑** — 双击即可修改 key 或 value，实时预览
- **撤销/重做** — Ctrl+Z / Ctrl+Y，最多 50 步历史记录
- **拖拽导入** — 直接拖入 .json 文件即可加载
- **CSV 导出** — 数组类型数据可一键导出为 CSV
- **JSON Diff** — 对比两个 JSON 的差异，高亮新增/删除/修改
- **暗色主题** — 一键切换亮色/暗色主题
- **键盘导航** — 方向键浏览节点，Enter 编辑，Ctrl+F 搜索
- **路径收藏** — 收藏常用路径，快速跳转
- **虚拟滚动** — 大文件也能流畅渲染
- **响应式布局** — 支持移动端使用

## 快速开始

直接打开 `index.html` 即可使用，无需安装任何依赖。

```bash
# 或者用本地服务器
npx serve .
```

## 技术栈

- 纯 HTML + CSS + JavaScript
- 零依赖，单文件约 1700 行
- 支持所有现代浏览器

## License

MIT
