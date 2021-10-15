# Awesome

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

我的 Github 常购清单.

- ⭐️ 推荐
- 👀 关注
- 💵 付费
- 😝 恶搞

> 唯星主义者, 排名分先后.

- [React](#react)
  - [Build](#build)
  - [Component](#component)
  - [DnD](#dnd)
  - [Form](#form)
  - [Hook](#hook)
  - [State Management](#state-management)
  - [Style](#style)
  - [UI library](#ui-library)
- [JavaScript](#javascript)
  - [Data](#data)
  - [Datetime](#datetime)
  - [Frontend Framework](#frontend-framework)
  - [Micro Frontend](#micro-frontend)
  - [Rich Text Editor](#rich-text-editor)
  - [Toolkit](#toolkit)
  - [UI Library](#ui-library-1)
- [TypeScript](#typescript)
- [WebAssembly](#webassembly)
- [Node.js](#nodejs)
  - [Algorithm](#algorithm)
  - [Build](#build-1)
  - [Code Generator](#code-generator)
  - [Database](#database)
  - [Model](#model)
  - [Server](#server)
  - [Terminal](#terminal)
  - [Test](#test)
- [CSS](#css)
- [Serverless](#serverless)
- [Shell](#shell)
- [Book](#book)
- [Design](#design)
- [Misc](#misc)
- [RIP](#rip)

---

## React

### Build

- ⭐️ [vitejs/vite](https://github.com/vitejs/vite) 快. 配置简单, 3~5 行配置就可以开始写 React 项目, 默认配置无需调整即可满足大部分需要.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vitejs/vite?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vitejs/vite?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vitejs/vite?style=social)

- ⭐️ [privatenumber/esbuild-loader](https://github.com/privatenumber/esbuild-loader) Webpack esbuild loader. 当你的项目必须使用 webpack 构建时, 使用 esbuild-loader 可以显著提高性能, 尤其是代码压缩比 terser 快 10 倍以上.

  ![GitHub Repo stars](https://img.shields.io/github/stars/privatenumber/esbuild-loader?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/privatenumber/esbuild-loader?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/privatenumber/esbuild-loader?style=social)

- ⭐️ [welldone-software/why-did-you-render](https://github.com/welldone-software/why-did-you-render) 排查组件渲染的 babel 插件. 作者的文章对优化性能有帮助.

  ![GitHub Repo stars](https://img.shields.io/github/stars/welldone-software/why-did-you-render?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/welldone-software/why-did-you-render?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/welldone-software/why-did-you-render?style=social)

- 👀 [evanw/esbuild](https://github.com/evanw/esbuild) 非常快的 js 编译打包压缩工具. 使用 Go 编写, vite 和 esbuild-loader 的基础, 一般不直接使用.

  ![GitHub Repo stars](https://img.shields.io/github/stars/evanw/esbuild?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/evanw/esbuild?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/evanw/esbuild?style=social)

- 👀 [swc-project/swc](https://github.com/swc-project/swc) 非常快的 js 编译工具. 使用 Rust 编写, 目标是替代 babel.

  ![GitHub Repo stars](https://img.shields.io/github/stars/swc-project/swc?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/swc-project/swc?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/swc-project/swc?style=social)

- [snowpackjs/snowpack](https://github.com/snowpackjs/snowpack) 时髦轻量级的打包工具. 对标 vite.

  ![GitHub Repo stars](https://img.shields.io/github/stars/snowpackjs/snowpack?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/snowpackjs/snowpack?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/snowpackjs/snowpack?style=social)

- [jaredpalmer/tsdx](https://github.com/jaredpalmer/tsdx) TypeScript 包开发构建工具. 基于 rollup1, 来自于 formik 作者.

  ![GitHub Repo stars](https://img.shields.io/github/stars/jaredpalmer/tsdx?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/jaredpalmer/tsdx?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/jaredpalmer/tsdx?style=social)

### Component

- ⭐️ [bvaughn/react-window](https://github.com/bvaughn/react-window) 虚拟滚动列表. 高度抽象, 不提供 UI.

  ![GitHub Repo stars](https://img.shields.io/github/stars/bvaughn/react-window?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/bvaughn/react-window?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/bvaughn/react-window?style=social)

- ⭐️ [Lodin/react-vtree](https://github.com/Lodin/react-vtree) 基于 react-window 实现的虚拟滚动树形列表. 使用 generator function 作为数据源.

  ![GitHub Repo stars](https://img.shields.io/github/stars/Lodin/react-vtree?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/Lodin/react-vtree?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/Lodin/react-vtree?style=social)

- ⭐️ [casesandberg/react-color](https://github.com/casesandberg/react-color) 颜色选择器. 外观上模拟常见的软件.

  ![GitHub Repo stars](https://img.shields.io/github/stars/casesandberg/react-color?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/casesandberg/react-color?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/casesandberg/react-color?style=social)

- ⭐️ [uNmAnNeR/imaskjs](https://github.com/uNmAnNeR/imaskjs) 文字格式 mask. 用于需要把文字强制显示成某种格式, 例如千分位.

  ![GitHub Repo stars](https://img.shields.io/github/stars/uNmAnNeR/imaskjs?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/uNmAnNeR/imaskjs?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/uNmAnNeR/imaskjs?style=social)

- ⭐️ [react-monaco-editor/react-monaco-editor](https://github.com/react-monaco-editor/react-monaco-editor) 源代码编辑器. VSCode 的内核.

  ![GitHub Repo stars](https://img.shields.io/github/stars/react-monaco-editor/react-monaco-editor?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/react-monaco-editor/react-monaco-editor?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/react-monaco-editor/react-monaco-editor?style=social)

- ⭐️ [mac-s-g/react-json-view](https://github.com/mac-s-g/react-json-view) 显示 JSON 树形数据.

  ![GitHub Repo stars](https://img.shields.io/github/stars/mac-s-g/react-json-view?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/mac-s-g/react-json-view?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/mac-s-g/react-json-view?style=social)

- 💵 [ag-grid/ag-grid](https://github.com/ag-grid/ag-grid) 功能强大的商业化表格.

  ![GitHub Repo stars](https://img.shields.io/github/stars/ag-grid/ag-grid?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/ag-grid/ag-grid?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/ag-grid/ag-grid?style=social)

- [Autodesk/react-base-table](https://github.com/Autodesk/react-base-table) Autodesk 出品的表格组件. 不推荐使用, 只是让你体会一下大厂的代码是如何写的.

  ![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/react-base-table?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/Autodesk/react-base-table?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/Autodesk/react-base-table?style=social)

### DnD

- ⭐️ [atlassian/react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) 开箱即用的拖拽组件库, 适用于 Todo/Kanban 这类应用场景. 由大名鼎鼎的 Jira 东家 Atlassian 开发.

  ![GitHub Repo stars](https://img.shields.io/github/stars/atlassian/react-beautiful-dnd?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/atlassian/react-beautiful-dnd?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/atlassian/react-beautiful-dnd?style=social)

- 👀 [clauderic/dnd-kit](https://github.com/clauderic/dnd-kit) React DnD 家族后起之秀, 刻意规避 [HTML5 Drag and drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) 来绕开浏览器自身限制, 这个决定导致不支持拖拽上传这类操作, 但是性能收益很明显. 注意作者坚称现在是 beta 版, 即使版本号已经是 4.0 了.

  ![GitHub Repo stars](https://img.shields.io/github/stars/clauderic/dnd-kit?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/clauderic/dnd-kit?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/clauderic/dnd-kit?style=social)

- [react-dnd/react-dnd](https://github.com/react-dnd/react-dnd) 老牌拖拽库, 当以上不能满足需求时, 可以尝试用这个实现拖拽的各种细节效果.

  ![GitHub Repo stars](https://img.shields.io/github/stars/react-dnd/react-dnd?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/react-dnd/react-dnd?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/react-dnd/react-dnd?style=social)

### Form

- 👀 [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) 反传统 hook form 状态管理. 大量使用 ref 接管用户输入, 绕过 react 状态管理, 以达到减少 render, 提高性能的目的. 对 UI 组件要求苛刻.

  ![GitHub Repo stars](https://img.shields.io/github/stars/react-hook-form/react-hook-form?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/react-hook-form/react-hook-form?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/react-hook-form/react-hook-form?style=social)

- 👀 [alibaba/formily](https://github.com/alibaba/formily) Form 可序列化解决方案. 包含 form 设计器和渲染器两部分, 功能十分复杂.

  ![GitHub Repo stars](https://img.shields.io/github/stars/alibaba/formily?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/alibaba/formily?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/alibaba/formily?style=social)

### Hook

- ⭐️ [streamich/react-use](https://github.com/streamich/react-use) React hooks 百宝箱, 准备写 hook 前先查一下是不是已经有了.

  ![GitHub Repo stars](https://img.shields.io/github/stars/streamich/react-use?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/streamich/react-use?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/streamich/react-use?style=social)

- ⭐️ [pmndrs/use-gesture](https://github.com/pmndrs/use-gesture) 鼠标和触摸手势 hook.

  ![GitHub Repo stars](https://img.shields.io/github/stars/pmndrs/use-gesture?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/pmndrs/use-gesture?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pmndrs/use-gesture?style=social)

- [immerjs/use-immer](https://github.com/immerjs/use-immer) 基于 immer 的 useState.

  ![GitHub Repo stars](https://img.shields.io/github/stars/immerjs/use-immer?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/immerjs/use-immer?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/immerjs/use-immer?style=social)

### State Management

- ⭐️ [mobxjs/mobx](https://github.com/mobxjs/mobx) 简单可伸缩的状态管理. React 一直不肯承认响应式数据流比单向数据流更实用, Proxy 出现后响应式数据的性能得到很大提升. 用 react 的方式渲染, 用 vue 的思维管理数据, 就是 mobx. 一个前端数据建模框架.

  ![GitHub Repo stars](https://img.shields.io/github/stars/mobxjs/mobx?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/mobxjs/mobx?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/mobxjs/mobx?style=social)

- ⭐️ [tannerlinsley/react-query](https://github.com/tannerlinsley/react-query) React 加载/缓存/更新 hook. 数据加载以 query key 加以区分, 相同的 key 并发时会自动去重, 数据默认有个“新鲜度”的概念, 组件重新 mount 或窗口重新 focus 时根据“新鲜度”决定是否重新加载. 一般把它看作分布式数据管理, 在组件中调用 API, 而不必过度关心数据的形状.

  ![GitHub Repo stars](https://img.shields.io/github/stars/tannerlinsley/react-query?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/tannerlinsley/react-query?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/tannerlinsley/react-query?style=social)

- [vercel/swr](https://github.com/vercel/swr) 与 react-query 同时期理念相近的作品. 名称取自于 `stale-while-revalidate`, 一个关于缓存失效策略的标准 [HTTP RFC 5861](https://tools.ietf.org/html/rfc5861).

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/swr?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/swr?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/swr?style=social)

- [umijs/hox](https://github.com/umijs/hox) 建个 model, 写个 hook, 全局共享.

  ![GitHub Repo stars](https://img.shields.io/github/stars/umijs/hox?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/umijs/hox?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/umijs/hox?style=social)

### Style

- ⭐️ [windicss/windicss](https://github.com/windicss/windicss) 一个像 Tailwind CSS 一样的 CSS 工具框架. 快 10 倍.

  ![GitHub Repo stars](https://img.shields.io/github/stars/windicss/windicss?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/windicss/windicss?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/windicss/windicss?style=social)

### UI library

- ⭐️ [ant-design/ant-design](https://github.com/ant-design/ant-design) 蚂蚁出品, 曾经的 React 组件库榜首(被删库前). 几乎可以满足任何需求, 组件 API 设计上同时考虑前端和后端使用, 一些 API 有独到见解. 样式上使用 less 是个败笔, 现已积重难返. 国内项目可以盲选, 国外项目想办法说服客户.

  ![GitHub Repo stars](https://img.shields.io/github/stars/ant-design/ant-design?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/ant-design/ant-design?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/ant-design/ant-design?style=social)

- [mui-org/material-ui](https://github.com/mui-org/material-ui) Google material design, 口质和口碑极高. 样式使用自研的 css in js, 与其他技术不好搭配. 是否选择取决于设计稿.

  ![GitHub Repo stars](https://img.shields.io/github/stars/mui-org/material-ui?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/mui-org/material-ui?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/mui-org/material-ui?style=social)

- 👀 [reach/reach-ui](https://github.com/reach/reach-ui) A11y 基础框架. A11y 之所以难以实现是因为与 HTML 标准之间的代沟, 学习这里面的代码能帮你更好的理解 A11y 有多少细节需要考虑.

  ![GitHub Repo stars](https://img.shields.io/github/stars/reach/reach-ui?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/reach/reach-ui?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/reach/reach-ui?style=social)

- 👀 [snackui/snackui](https://github.com/snackui/snackui) 一个试图复刻 SwiftUI 的组件库. 许多坑还没有填平.

  ![GitHub Repo stars](https://img.shields.io/github/stars/snackui/snackui?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/snackui/snackui?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/snackui/snackui?style=social)

- [facebook/docusaurus](https://github.com/facebook/docusaurus) Facebook 出品的文档站点生成器.

  ![GitHub Repo stars](https://img.shields.io/github/stars/facebook/docusaurus?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/facebook/docusaurus?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/facebook/docusaurus?style=social)

---

## JavaScript

### Data

- ⭐️ [ai/nanoid](https://github.com/ai/nanoid) ID 生成器. 小, 快, 短, 支持自定义字母表和长度.

  ![GitHub Repo stars](https://img.shields.io/github/stars/ai/nanoid?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/ai/nanoid?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/ai/nanoid?style=social)

- ⭐️ [localForage/localForage](https://github.com/localForage/localForage) 浏览器离线存储. 让你放心的操作 IndexedDB, WebSQL, localStorage, sessionStorage, 而不必在意浏览器的版本差异.

  ![GitHub Repo stars](https://img.shields.io/github/stars/localForage/localForage?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/localForage/localForage?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/localForage/localForage?style=social)

- ⭐️ [isaacs/node-lru-cache](https://github.com/isaacs/node-lru-cache) 基于 LRU(最近最少使用)算法实现的缓存库. 接口类似于 Map, 但是允许你设置容量, 容量不足时会自动清理最近最少使用的项目.

  ![GitHub Repo stars](https://img.shields.io/github/stars/isaacs/node-lru-cache?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/isaacs/node-lru-cache?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/isaacs/node-lru-cache?style=social)

- ⭐️ [Stuk/jszip](https://github.com/Stuk/jszip) 读写 zip 文件.

  ![GitHub Repo stars](https://img.shields.io/github/stars/Stuk/jszip?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/Stuk/jszip?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/Stuk/jszip?style=social)

- 👀 [inversify/InversifyJS](https://github.com/inversify/InversifyJS) 基于 decorator 的 loC([控制反转](https://zh.wikipedia.org/wiki/%E6%8E%A7%E5%88%B6%E5%8F%8D%E8%BD%AC))容器.

  ![GitHub Repo stars](https://img.shields.io/github/stars/inversify/InversifyJS?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/inversify/InversifyJS?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/inversify/InversifyJS?style=social)

- [SheetJS/js-crc32](https://github.com/SheetJS/js-crc32) CRC32 算法.

  ![GitHub Repo stars](https://img.shields.io/github/stars/SheetJS/js-crc32?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/SheetJS/js-crc32?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/SheetJS/js-crc32?style=social)

- [Jam3/math-as-code](https://github.com/Jam3/math-as-code) 常见数学符号在代码中的表示法.

  ![GitHub Repo stars](https://img.shields.io/github/stars/Jam3/math-as-code?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/Jam3/math-as-code?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/Jam3/math-as-code?style=social)

- 👀 [yjs/yjs](https://github.com/yjs/yjs) 基于 CRDT 的协作数据管理. 主打富文本多人协作.

  ![GitHub Repo stars](https://img.shields.io/github/stars/yjs/yjs?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/yjs/yjs?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/yjs/yjs?style=social)

- [amark/gun](https://github.com/amark/gun) 去中心化协同图形数据库.

  ![GitHub Repo stars](https://img.shields.io/github/stars/amark/gun?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/amark/gun?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/amark/gun?style=social)

- [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) 浏览器 User-Agent 检测工具.

  ![GitHub Repo stars](https://img.shields.io/github/stars/faisalman/ua-parser-js?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/faisalman/ua-parser-js?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/faisalman/ua-parser-js?style=social)

- [hotoo/pinyin](https://github.com/hotoo/pinyin) 汉字拼音 ➜ hàn zì pīn yīn.

  ![GitHub Repo stars](https://img.shields.io/github/stars/hotoo/pinyin?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/hotoo/pinyin?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/hotoo/pinyin?style=social)

### Datetime

- ⭐️ [iamkun/dayjs](https://github.com/iamkun/dayjs) 日期时间库的最后胜出者.

  ![GitHub Repo stars](https://img.shields.io/github/stars/iamkun/dayjs?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/iamkun/dayjs?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/iamkun/dayjs?style=social)

### Frontend Framework

- 👀 [alpinejs/alpine](https://github.com/alpinejs/alpine) 一个精巧的前端框架. 一个 html 文件就够了.

  ![GitHub Repo stars](https://img.shields.io/github/stars/alpinejs/alpine?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/alpinejs/alpine?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/alpinejs/alpine?style=social)

### Micro Frontend

- 👀 [micro-zoe/micro-app](https://github.com/micro-zoe/micro-app) 京东微前端解决方案. 特点是采用类似 WebComponent 这样的 Shadow DOM 技术实现, 尽可能减少对 host 和 app 进行改动.

  ![GitHub Repo stars](https://img.shields.io/github/stars/micro-zoe/micro-app?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/micro-zoe/micro-app?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/micro-zoe/micro-app?style=social)

- [umijs/qiankun](https://github.com/umijs/qiankun) 蚂蚁微前端解决方案. 不是 iframe.

  ![GitHub Repo stars](https://img.shields.io/github/stars/umijs/qiankun?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/umijs/qiankun?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/umijs/qiankun?style=social)

### Rich Text Editor

- [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) 一个完全可定制的富文本框架.

  ![GitHub Repo stars](https://img.shields.io/github/stars/ianstormtaylor/slate?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/ianstormtaylor/slate?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/ianstormtaylor/slate?style=social)

- ~~[quilljs/quill](https://github.com/quilljs/quill)~~ 不推荐. 放在这里是提醒大家 quill 作者已弃坑.

  ![GitHub Repo stars](https://img.shields.io/github/stars/quilljs/quill?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/quilljs/quill?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/quilljs/quill?style=social)

### Toolkit

- ⭐️ [axios/axios](https://github.com/axios/axios) 基于 Promise 的 http 客户端.

  ![GitHub Repo stars](https://img.shields.io/github/stars/axios/axios?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/axios/axios?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/axios/axios?style=social)

- ⭐️ [visionmedia/debug](https://github.com/visionmedia/debug) 小巧的 debug log 实用工具. 自动为每个 namespace 分配不同的颜色.

  ![GitHub Repo stars](https://img.shields.io/github/stars/visionmedia/debug?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/visionmedia/debug?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/visionmedia/debug?style=social)

- ⭐️ [sindresorhus/promise-fun](https://github.com/sindresorhus/promise-fun) Promise 工具集.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/promise-fun?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/promise-fun?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/promise-fun?style=social)

- [developit/greenlet](https://github.com/developit/greenlet) 在单独线程里运行 async function. 基于 web worker.

  ![GitHub Repo stars](https://img.shields.io/github/stars/developit/greenlet?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/developit/greenlet?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/developit/greenlet?style=social)

### UI Library

- ⭐️ [eligrey/FileSaver.js](https://github.com/eligrey/FileSaver.js) 前端保存文件. 弹出下载对话框, 支持二进制, 例如把 canvas 画布保存为图片, 使用 jszip 压缩文件并保存.

  ![GitHub Repo stars](https://img.shields.io/github/stars/eligrey/FileSaver.js?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/eligrey/FileSaver.js?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/eligrey/FileSaver.js?style=social)

- ⭐️ [usablica/intro.js](https://github.com/usablica/intro.js) 页面向导式 onboarding 指引.

  ![GitHub Repo stars](https://img.shields.io/github/stars/usablica/intro.js?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/usablica/intro.js?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/usablica/intro.js?style=social)

- ⭐️ [popperjs/popper-core](https://github.com/popperjs/popper-core) Tooltip & Popover. 用于解决 Tooltip 和 Popover 定位困难的问题.

  ![GitHub Repo stars](https://img.shields.io/github/stars/popperjs/popper-core?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/popperjs/popper-core?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/popperjs/popper-core?style=social)

- [atomiks/tippyjs](https://github.com/atomiks/tippyjs) 基于 popperjs 的更易用的实现.

  ![GitHub Repo stars](https://img.shields.io/github/stars/atomiks/tippyjs?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/atomiks/tippyjs?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/atomiks/tippyjs?style=social)

- [pqina/filepond](https://github.com/pqina/filepond) 又漂亮又好玩的文件上传组件.

  ![GitHub Repo stars](https://img.shields.io/github/stars/pqina/filepond?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/pqina/filepond?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/pqina/filepond?style=social)

- [PrismJS/prism](https://github.com/PrismJS/prism) 代码语法高亮.

  ![GitHub Repo stars](https://img.shields.io/github/stars/PrismJS/prism?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/PrismJS/prism?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/PrismJS/prism?style=social)

- [mathjax/MathJax](https://github.com/mathjax/MathJax) 渲染漂亮的数学公式.

  ![GitHub Repo stars](https://img.shields.io/github/stars/mathjax/MathJax?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/mathjax/MathJax?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/mathjax/MathJax?style=social)

- [airbnb/lottie-web](https://github.com/airbnb/lottie-web) 渲染 AE([Adobe After Effects](http://www.adobe.com/products/aftereffects.html))动画. 不必为如何实现设计师设计的动画而头疼.

  ![GitHub Repo stars](https://img.shields.io/github/stars/airbnb/lottie-web?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/airbnb/lottie-web?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/airbnb/lottie-web?style=social)

- [szimek/signature_pad](https://github.com/szimek/signature_pad) 基于 Canvas 实现的手写板效果.

  ![GitHub Repo stars](https://img.shields.io/github/stars/szimek/signature_pad?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/szimek/signature_pad?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/szimek/signature_pad?style=social)

- [futurepress/epub.js](https://github.com/futurepress/epub.js) 浏览器中查看 epub 电子书文件.

  ![GitHub Repo stars](https://img.shields.io/github/stars/futurepress/epub.js?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/futurepress/epub.js?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/futurepress/epub.js?style=social)

---

## TypeScript

- [adriengibrat/ts-custom-error](https://github.com/adriengibrat/ts-custom-error) Custom Error 父类

  ![GitHub Repo stars](https://img.shields.io/github/stars/adriengibrat/ts-custom-error?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/adriengibrat/ts-custom-error?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/adriengibrat/ts-custom-error?style=social)

---

## WebAssembly

- [AssemblyScript/assemblyscript](https://github.com/AssemblyScript/assemblyscript) 一种语法类似于 typescript 的 WebAssembly 编程语言.

  ![GitHub Repo stars](https://img.shields.io/github/stars/AssemblyScript/assemblyscript?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/AssemblyScript/assemblyscript?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/AssemblyScript/assemblyscript?style=social)

---

## Node.js

### Algorithm

- 👀 [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) 中文分词.

  ![GitHub Repo stars](https://img.shields.io/github/stars/yanyiwu/nodejieba?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/yanyiwu/nodejieba?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/yanyiwu/nodejieba?style=social)

### Build

- 👀 [vercel/ncc](https://github.com/vercel/ncc) 把 node 项目编译成单文件. 像 go 一样, 注意是连 node_modules 都编译进去. 适用于微服务, 或不方便安装 npm 的环境.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/ncc?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/ncc?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/ncc?style=social)

- 👀 [vercel/pkg](https://github.com/vercel/pkg) 把 node 项目编译成可执行文件. 像 go 一样, 注意是连 node 都编译进去. 适用于不方便安装 node 的环境.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/pkg?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/pkg?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/pkg?style=social)

### Code Generator

- ⭐️ [dotansimha/graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) 基于 GraphQL 产生代码. 主要用于产生 typescript.

  ![GitHub Repo stars](https://img.shields.io/github/stars/dotansimha/graphql-code-generator?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/dotansimha/graphql-code-generator?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/dotansimha/graphql-code-generator?style=social)

- [quicktype/quicktype](https://github.com/quicktype/quicktype) 基于 JSON/GraphQL 产生数据模型. 用于快速建模.

  ![GitHub Repo stars](https://img.shields.io/github/stars/quicktype/quicktype?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/quicktype/quicktype?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/quicktype/quicktype?style=social)

### Database

- ⭐️ [Automattic/mongoose](https://github.com/Automattic/mongoose) MongoDB 官方 ORM.

  ![GitHub Repo stars](https://img.shields.io/github/stars/Automattic/mongoose?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/Automattic/mongoose?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/Automattic/mongoose?style=social)

- ⭐️ [typeorm/typeorm](https://github.com/typeorm/typeorm) 基于 decorator 建模的 ORM. 支持 MySQL, PostgreSQL, MariaDB, SQLite, MS SQL Server, Oracle, SAP Hana, WebSQL.

  ![GitHub Repo stars](https://img.shields.io/github/stars/typeorm/typeorm?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/typeorm/typeorm?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/typeorm/typeorm?style=social)

- 👀 [graphile/postgraphile](https://github.com/graphile/postgraphile) 基于 PostgreSQL 的 GraphQL api server. 如果你是一名 DBA 或者对 PostgreSQL 十分熟悉, 当你想快速的搭建一个 GraphQL api server 时, 可以尝试这个. 它允许你使用数据库中的用户权限来完成注册和登录, 并且把一些逻辑代码写在 PostgreSQL functions 里.

  ![GitHub Repo stars](https://img.shields.io/github/stars/graphile/postgraphile?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/graphile/postgraphile?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/graphile/postgraphile?style=social)

- [agenda/agenda](https://github.com/agenda/agenda) 基于 MongoDB 的 轻量级计划任务.

  ![GitHub Repo stars](https://img.shields.io/github/stars/agenda/agenda?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/agenda/agenda?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/agenda/agenda?style=social)

### Model

- ⭐️ [typestack/class-validator](https://github.com/typestack/class-validator) 基于 decorator 的数据验证.

  ![GitHub Repo stars](https://img.shields.io/github/stars/typestack/class-validator?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/typestack/class-validator?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/typestack/class-validator?style=social)

- ⭐️ [typestack/class-transformer](https://github.com/typestack/class-transformer) 基于 decorator 的数据转换. plain -> class, class -> plain, class -> class.

  ![GitHub Repo stars](https://img.shields.io/github/stars/typestack/class-transformer?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/typestack/class-transformer?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/typestack/class-transformer?style=social)

- ⭐️ [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) 类似于 jQuery 的后端 html 解析维护工具. 用于从网页中抓取有用的信息.

  ![GitHub Repo stars](https://img.shields.io/github/stars/cheeriojs/cheerio?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/cheeriojs/cheerio?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/cheeriojs/cheerio?style=social)

### Server

- ⭐️ [nestjs/nest](https://github.com/nestjs/nest) 渐进式企业级服务器框架. 随着需求增加可以不断安装新的模块, 基本上你能碰到的问题官网上都有对应的解决方案, 是同类产品中功能最强大的.

  ![GitHub Repo stars](https://img.shields.io/github/stars/nestjs/nest?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/nestjs/nest?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/nestjs/nest?style=social)

- ⭐️ [vercel/serve](https://github.com/vercel/serve) 简单的静态文件服务器, 支持前端单页应用. 用于测试前端构建结果是否符合预期, 也可以直接用于生产服务器.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/serve?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/serve?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/serve?style=social)

- [vercel/next.js](https://github.com/vercel/next.js) React SSR 服务器. 对组件的 SSR 支持有一定要求, 适合 React 项目需要一些简单的后端 API.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/next.js?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/next.js?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/next.js?style=social)

- [typicode/json-server](https://github.com/typicode/json-server) 使用 json 作为数据库的增删改查服务器. 新建 `db.json`, 启动 `json-server`. 现在你拥有一个 REST API 了.

  ![GitHub Repo stars](https://img.shields.io/github/stars/typicode/json-server?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/typicode/json-server?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/typicode/json-server?style=social)

- [davewasmer/devcert](https://github.com/davewasmer/devcert) 本地开发时对任意域名启用 https.

  ![GitHub Repo stars](https://img.shields.io/github/stars/davewasmer/devcert?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/davewasmer/devcert?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/davewasmer/devcert?style=social)

### Terminal

- ⭐️ [open-cli-tools/concurrently](https://github.com/open-cli-tools/concurrently) 并行执行命令.

  ![GitHub Repo stars](https://img.shields.io/github/stars/open-cli-tools/concurrently?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/open-cli-tools/concurrently?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/open-cli-tools/concurrently?style=social)

- ⭐️ [sindresorhus/execa](https://github.com/sindresorhus/execa) 人性化的进程调用工具. 比 `child_process.spawn()` 简便, 支持 async.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/execa?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/execa?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/execa?style=social)

- ⭐️ [chalk/chalk](https://github.com/chalk/chalk) 命令行 ANSI 颜色样式. 蜡笔, 不言而喻.

  ![GitHub Repo stars](https://img.shields.io/github/stars/chalk/chalk?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/chalk/chalk?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/chalk/chalk?style=social)

- ⭐️ [isaacs/node-glob](https://github.com/isaacs/node-glob) Glob 字符串解析器. 我们经常写的 `**/*.js` 就是由这个库解析匹配的, 来自于 Npm 作者.

  ![GitHub Repo stars](https://img.shields.io/github/stars/isaacs/node-glob?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/isaacs/node-glob?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/isaacs/node-glob?style=social)

- ⭐️ [sindresorhus/del-cli](https://github.com/sindresorhus/del-cli) 删除文件和目录. 会检测并防止意外删除项目之外的文件, 一般用于构建和自动化等场景.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/del-cli?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/del-cli?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/del-cli?style=social)

- ⭐️ [sindresorhus/get-port](https://github.com/sindresorhus/get-port) 获取可用端口号. 如果你的程序不需要固定的端口号, 可以用这个库. 例如 vite 默认使用 3000 端口, 不可用时会尝试 3001 3002.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/get-port?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/get-port?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/get-port?style=social)

- ⭐️ [tiaanduplessis/kill-port](https://github.com/tiaanduplessis/kill-port) 杀掉占用端口的进程. 纯 js 跨平台, 用于必须运行在指定端口的场景, 多半是你自己的上一个进程没有正确退出.

  ![GitHub Repo stars](https://img.shields.io/github/stars/tiaanduplessis/kill-port?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/tiaanduplessis/kill-port?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/tiaanduplessis/kill-port?style=social)

- ⭐️ [davidtheclark/cosmiconfig](https://github.com/davidtheclark/cosmiconfig) 配置搜索加载工具. 有没有好奇为什么知名工具的配置可以支持那么多种格式 `package.json` `.json` `.yaml` `*rc` `.config.js`? cosmiconfig 就是专门解决这个问题的.

  ![GitHub Repo stars](https://img.shields.io/github/stars/davidtheclark/cosmiconfig?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/davidtheclark/cosmiconfig?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/davidtheclark/cosmiconfig?style=social)

- ⭐️ [evanshortiss/env-var](https://github.com/evanshortiss/env-var) 获取 ENV 并转化为确定的类型, 支持验证, 默认值, 和 typescript.

  ![GitHub Repo stars](https://img.shields.io/github/stars/evanshortiss/env-var?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/evanshortiss/env-var?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/evanshortiss/env-var?style=social)

- [facebook/jscodeshift](https://github.com/facebook/jscodeshift) 代码修改工具. Facebook 为了让 react 升级更平滑而推出的迁移工具, Antd MobX 都曾在大版本升级时基于 jscodeshift 实现迁移.

  ![GitHub Repo stars](https://img.shields.io/github/stars/facebook/jscodeshift?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/facebook/jscodeshift?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/facebook/jscodeshift?style=social)

### Test

- ⭐️ [nock/nock](https://github.com/nock/nock) HTTP server mocking. 老牌 network mock 库, 持续更新.

  ![GitHub Repo stars](https://img.shields.io/github/stars/nock/nock?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/nock/nock?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/nock/nock?style=social)

- [vercel/test-listen](https://github.com/vercel/test-listen) 启动 http server 并获取 url 用于后续测试.

  ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/test-listen?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/vercel/test-listen?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/vercel/test-listen?style=social)

- 😝 [auchenberg/volkswagen](https://github.com/auchenberg/volkswagen) 检测当前环境, 如果是 CI 则所有测试全部通过.

  ![GitHub Repo stars](https://img.shields.io/github/stars/auchenberg/volkswagen?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/auchenberg/volkswagen?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/auchenberg/volkswagen?style=social)

---

## CSS

- ⭐️ [cognitom/paper-css](https://github.com/marvelapp/devices.css) 一比一还原页面打印时的效果. 例如 A4 纸的打印效果, 可用于实现包含纸张概念的页面样式.

  ![GitHub Repo stars](https://img.shields.io/github/stars/marvelapp/devices.css?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/marvelapp/devices.css?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/marvelapp/devices.css?style=social)

- [marvelapp/devices.css](https://github.com/marvelapp/devices.css) 绘制各种手机/平板.

  ![GitHub Repo stars](https://img.shields.io/github/stars/marvelapp/devices.css?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/marvelapp/devices.css?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/marvelapp/devices.css?style=social)

---

## Serverless

- ⭐️ [serverless/serverless](https://github.com/serverless/serverless) 支持众多云服务的 serverless 框架. AWS Lambda, Azure Functions, Tencent SCF, Google Cloud Functions, Knative Serving, Alibaba FC, Cloudflare Workers, Fn, Kubeless, Apache OpenWhisk, Spotinst Functions.

  ![GitHub Repo stars](https://img.shields.io/github/stars/serverless/serverless?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/serverless/serverless?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/serverless/serverless?style=social)

---

## Shell

- ⭐️ [nvm-sh/nvm](https://github.com/nvm-sh/nvm) Node 版本管理工具. 允许多个版本共存, 可以用 `.nvmrc` 文件指定当前目录用哪个版本的 node.

  ![GitHub Repo stars](https://img.shields.io/github/stars/nvm-sh/nvm?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/nvm-sh/nvm?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/nvm-sh/nvm?style=social)

- ⭐️ [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) ZSH 配置管理.

  ![GitHub Repo stars](https://img.shields.io/github/stars/ohmyzsh/ohmyzsh?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/ohmyzsh/ohmyzsh?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/ohmyzsh/ohmyzsh?style=social)

- ⭐️ [sindresorhus/pure](https://github.com/sindresorhus/pure) ZSH 轻量快速提示符. 支持显示 git status 和 command 执行时间.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/pure?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/pure?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/pure?style=social)

- ⭐️ [sindresorhus/np](https://github.com/sindresorhus/np) 一个更好的 `npm publish` 命令. 用于 release 项目, 自动构建, 判断分支, 提交到 git, 提交到 npm, 发布 github release.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/np?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sindresorhus/np?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/np?style=social)

---

## Book

- ⭐️ [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) 你不懂 JS. 这本书不是标题党, 作者不会跟你讲 0.1 + 0.2 != 0.3 这种问题, 而是讲实实在在的有用的细节.

  ![GitHub Repo stars](https://img.shields.io/github/stars/getify/You-Dont-Know-JS?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/getify/You-Dont-Know-JS?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/getify/You-Dont-Know-JS?style=social)

---

## Design

- 👀 [airbnb/react-sketchapp](https://github.com/airbnb/react-sketchapp) 使用 react 组件写 sketch. 为什么? Sketch 文件不好管理, 新旧版本不兼容. 改成 react 组件写法, 需要时输出到 sketch 文件.

  ![GitHub Repo stars](https://img.shields.io/github/stars/airbnb/react-sketchapp?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/airbnb/react-sketchapp?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/airbnb/react-sketchapp?style=social)

- [lllyasviel/style2paints](https://github.com/lllyasviel/style2paints) AI 填色.

  ![GitHub Repo stars](https://img.shields.io/github/stars/lllyasviel/style2paints?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/lllyasviel/style2paints?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/lllyasviel/style2paints?style=social)

---

## Misc

- ⭐️ [github/gitignore](https://github.com/github/gitignore) 常见 `.gitignore` 模板. 在 github 上新建 repo 时选择的模板来源于这里.

  ![GitHub Repo stars](https://img.shields.io/github/stars/github/gitignore?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/github/gitignore?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/github/gitignore?style=social)

- ⭐️ [sparanoid/chinese-copywriting-guidelines](https://github.com/sparanoid/chinese-copywriting-guidelines) 中文文案排版指北.

  ![GitHub Repo stars](https://img.shields.io/github/stars/sparanoid/chinese-copywriting-guidelines?style=social)
  ![GitHub release](https://img.shields.io/github/v/release/sparanoid/chinese-copywriting-guidelines?style=social)
  ![GitHub last commit](https://img.shields.io/github/last-commit/sparanoid/chinese-copywriting-guidelines?style=social)

---

## RIP

> 曾经的辉煌

- [browserify/browserify](https://github.com/browserify/browserify) browser-side require() the node.js way. 前端打包工具的鼻祖.
- [gulpjs/gulp](https://github.com/gulpjs/gulp) A toolkit to automate & enhance your workflow. 流式自动化编排.
- [google/traceur-compiler](https://github.com/google/traceur-compiler) Traceur is a JavaScript.next-to-JavaScript-of-today compiler. 因巨大的 runtime 和丑陋的生成结果而输给了 babel.
- [ractivejs/ractive](https://github.com/ractivejs/ractive) Next-generation DOM manipulation. 已经变成上一代.
- [assaf/zombie](https://github.com/assaf/zombie) Insanely fast, full-stack, headless browser testing using node.js. 早期 e2e 框架, 不需要安装浏览器.
