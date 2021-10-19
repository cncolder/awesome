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
  - [UI Widget](#ui-widget)
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

- ⭐️ [vitejs/vite](https://github.com/vitejs/vite) Next generation frontend tooling. It's fast!

  http://vitejs.dev/

  快. 配置简单, 3~5 行配置就可以开始写 React 项目, 默认配置无需调整即可满足大部分需要.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vitejs/vite?style=social)](https://github.com/vitejs/vite/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vitejs/vite?style=social)](https://github.com/vitejs/vite/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vitejs/vite?style=social)](https://github.com/vitejs/vite/commits)

- ⭐️ [privatenumber/esbuild-loader](https://github.com/privatenumber/esbuild-loader) ⚡️ Speed up your Webpack build with esbuild

  Webpack esbuild loader. 当你的项目必须使用 webpack 构建时, 使用 esbuild-loader 可以显著提高性能, 尤其是代码压缩比 terser 快 10 倍以上.

  [![GitHub Repo stars](https://img.shields.io/github/stars/privatenumber/esbuild-loader?style=social)](https://github.com/privatenumber/esbuild-loader/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/privatenumber/esbuild-loader?style=social)](https://github.com/privatenumber/esbuild-loader/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/privatenumber/esbuild-loader?style=social)](https://github.com/privatenumber/esbuild-loader/commits)

- ⭐️ [welldone-software/why-did-you-render](https://github.com/welldone-software/why-did-you-render) why-did-you-render by Welldone Software monkey patches React to notify you about potentially avoidable re-renders. (Works with React Native as well.)

  https://medium.com/welldone-software

  排查组件渲染的 babel 插件. 作者的文章对优化性能有帮助.

  [![GitHub Repo stars](https://img.shields.io/github/stars/welldone-software/why-did-you-render?style=social)](https://github.com/welldone-software/why-did-you-render/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/welldone-software/why-did-you-render?style=social)](https://github.com/welldone-software/why-did-you-render/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/welldone-software/why-did-you-render?style=social)](https://github.com/welldone-software/why-did-you-render/commits)

- 👀 [evanw/esbuild](https://github.com/evanw/esbuild) An extremely fast JavaScript and CSS bundler and minifier

  https://esbuild.github.io/

  非常快的 js 编译打包压缩工具. 使用 Go 编写, vite 和 esbuild-loader 的基础, 一般不直接使用.

  [![GitHub Repo stars](https://img.shields.io/github/stars/evanw/esbuild?style=social)](https://github.com/evanw/esbuild/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/evanw/esbuild?style=social)](https://github.com/evanw/esbuild/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/evanw/esbuild?style=social)](https://github.com/evanw/esbuild/commits)

- 👀 [swc-project/swc](https://github.com/swc-project/swc) swc is a super-fast compiler written in rust; producing widely-supported javascript from modern standards and typescript.

  https://swc.rs/

  非常快的 js 编译工具. 使用 Rust 编写, 目标是替代 babel.

  [![GitHub Repo stars](https://img.shields.io/github/stars/swc-project/swc?style=social)](https://github.com/swc-project/swc/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/swc-project/swc?style=social)](https://github.com/swc-project/swc/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/swc-project/swc?style=social)](https://github.com/swc-project/swc/commits)

- [snowpackjs/snowpack](https://github.com/snowpackjs/snowpack) ESM-powered frontend build tool. Instant, lightweight, unbundled development. ✌️

  https://www.snowpack.dev/

  时髦轻量级的打包工具. 对标 vite.

  [![GitHub Repo stars](https://img.shields.io/github/stars/snowpackjs/snowpack?style=social)](https://github.com/snowpackjs/snowpack/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/snowpackjs/snowpack?style=social)](https://github.com/snowpackjs/snowpack/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/snowpackjs/snowpack?style=social)](https://github.com/snowpackjs/snowpack/commits)

- ⭐️ [developit/microbundle](https://github.com/developit/microbundle) 📦 Zero-configuration bundler for tiny modules.

  聪明小巧的包开发构建工具. 基于 rollup 2, 配置极简, 你在 package.json 里面写明包的入口 main/module/exports 路径, 它就知道该用什么格式生成这些对应的文件. 缺点也是极简, 定制选项少.

  [![GitHub Repo stars](https://img.shields.io/github/stars/developit/microbundle?style=social)](https://github.com/developit/microbundle/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/developit/microbundle?style=social)](https://github.com/developit/microbundle/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/developit/microbundle?style=social)](https://github.com/developit/microbundle/commits)

- [jaredpalmer/tsdx](https://github.com/jaredpalmer/tsdx) Zero-config CLI for TypeScript package development

  https://tsdx.io/

  TypeScript 包开发构建工具. 基于 rollup 1, 有些落伍 来自于 formik 作者. 输出的结果类似于 react, 会按环境分成 `.cjs.production.js` 和 `.cjs.development.js` 两份文件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/jaredpalmer/tsdx?style=social)](https://github.com/jaredpalmer/tsdx/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/jaredpalmer/tsdx?style=social)](https://github.com/jaredpalmer/tsdx/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/jaredpalmer/tsdx?style=social)](https://github.com/jaredpalmer/tsdx/commits)

### Component

- ⭐️ [bvaughn/react-window](https://github.com/bvaughn/react-window) React components for efficiently rendering large lists and tabular data

  https://react-window.now.sh/

  虚拟滚动列表. 高度抽象, 不提供 UI.

  [![GitHub Repo stars](https://img.shields.io/github/stars/bvaughn/react-window?style=social)](https://github.com/bvaughn/react-window/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/bvaughn/react-window?style=social)](https://github.com/bvaughn/react-window/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/bvaughn/react-window?style=social)](https://github.com/bvaughn/react-window/commits)

- ⭐️ [Lodin/react-vtree](https://github.com/Lodin/react-vtree) React component for efficiently rendering large tree structures

  https://lodin.github.io/react-vtree/

  基于 react-window 实现的虚拟滚动树形列表. 使用 generator function 作为数据源.

  [![GitHub Repo stars](https://img.shields.io/github/stars/Lodin/react-vtree?style=social)](https://github.com/Lodin/react-vtree/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/Lodin/react-vtree?style=social)](https://github.com/Lodin/react-vtree/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/Lodin/react-vtree?style=social)](https://github.com/Lodin/react-vtree/commits)

- ⭐️ [casesandberg/react-color](https://github.com/casesandberg/react-color) 🎨 Color Pickers from Sketch, Photoshop, Chrome, Github, Twitter & more

  http://casesandberg.github.io/react-color/

  颜色选择器. 外观上模拟常见的软件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/casesandberg/react-color?style=social)](https://github.com/casesandberg/react-color/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/casesandberg/react-color?style=social)](https://github.com/casesandberg/react-color/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/casesandberg/react-color?style=social)](https://github.com/casesandberg/react-color/commits)

- ⭐️ [uNmAnNeR/imaskjs](https://github.com/uNmAnNeR/imaskjs) vanilla javascript input mask

  https://imask.js.org/

  文字格式 mask. 用于需要把文字强制显示成某种格式, 例如千分位.

  [![GitHub Repo stars](https://img.shields.io/github/stars/uNmAnNeR/imaskjs?style=social)](https://github.com/uNmAnNeR/imaskjs/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/uNmAnNeR/imaskjs?style=social)](https://github.com/uNmAnNeR/imaskjs/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/uNmAnNeR/imaskjs?style=social)](https://github.com/uNmAnNeR/imaskjs/commits)

- ⭐️ [react-monaco-editor/react-monaco-editor](https://github.com/react-monaco-editor/react-monaco-editor) Monaco Editor for React.

  源代码编辑器. VSCode 的内核.

  [![GitHub Repo stars](https://img.shields.io/github/stars/react-monaco-editor/react-monaco-editor?style=social)](https://github.com/react-monaco-editor/react-monaco-editor/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/react-monaco-editor/react-monaco-editor?style=social)](https://github.com/react-monaco-editor/react-monaco-editor/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/react-monaco-editor/react-monaco-editor?style=social)](https://github.com/react-monaco-editor/react-monaco-editor/commits)

- ⭐️ [mac-s-g/react-json-view](https://github.com/mac-s-g/react-json-view) JSON viewer for react

  https://mac-s-g.github.io/react-json-view/demo/dist/

  显示 JSON 树形数据.

  [![GitHub Repo stars](https://img.shields.io/github/stars/mac-s-g/react-json-view?style=social)](https://github.com/mac-s-g/react-json-view/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/mac-s-g/react-json-view?style=social)](https://github.com/mac-s-g/react-json-view/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/mac-s-g/react-json-view?style=social)](https://github.com/mac-s-g/react-json-view/commits)

- 💵 [ag-grid/ag-grid](https://github.com/ag-grid/ag-grid) The best JavaScript Data Table for building Enterprise Applications. Supports React / Angular / Vue / Plain JavaScript.

  http://www.ag-grid.com/

  功能强大的商业化表格.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ag-grid/ag-grid?style=social)](https://github.com/ag-grid/ag-grid/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ag-grid/ag-grid?style=social)](https://github.com/ag-grid/ag-grid/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ag-grid/ag-grid?style=social)](https://github.com/ag-grid/ag-grid/commits)

- [Autodesk/react-base-table](https://github.com/Autodesk/react-base-table) Autodesk 出品的表格组件. 不推荐使用, 只是让你体会一下大厂的代码是如何写的.

  [![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/react-base-table?style=social)](https://github.com/Autodesk/react-base-table/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/Autodesk/react-base-table?style=social)](https://github.com/Autodesk/react-base-table/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/Autodesk/react-base-table?style=social)](https://github.com/Autodesk/react-base-table/commits)

### DnD

- ⭐️ [atlassian/react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) Beautiful and accessible drag and drop for lists with React

  https://react-beautiful-dnd.netlify.com/

  开箱即用的拖拽组件库, 适用于 Todo/Kanban 这类应用场景. 由大名鼎鼎的 Jira 东家 Atlassian 开发.

  [![GitHub Repo stars](https://img.shields.io/github/stars/atlassian/react-beautiful-dnd?style=social)](https://github.com/atlassian/react-beautiful-dnd/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/atlassian/react-beautiful-dnd?style=social)](https://github.com/atlassian/react-beautiful-dnd/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/atlassian/react-beautiful-dnd?style=social)](https://github.com/atlassian/react-beautiful-dnd/commits)

- 👀 [clauderic/dnd-kit](https://github.com/clauderic/dnd-kit) A modern, lightweight, performant, accessible and extensible drag & drop toolkit for React.

  http://dndkit.com/

  React DnD 家族后起之秀, 刻意规避 [HTML5 Drag and drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API) 来绕开浏览器自身限制, 这个决定导致不支持拖拽上传这类操作, 但是性能收益很明显. 注意作者坚称现在是 beta 版, 即使版本号已经是 4.0 了.

  [![GitHub Repo stars](https://img.shields.io/github/stars/clauderic/dnd-kit?style=social)](https://github.com/clauderic/dnd-kit/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/clauderic/dnd-kit?style=social)](https://github.com/clauderic/dnd-kit/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/clauderic/dnd-kit?style=social)](https://github.com/clauderic/dnd-kit/commits)

- [react-dnd/react-dnd](https://github.com/react-dnd/react-dnd) Drag and Drop for React

  http://react-dnd.github.io/react-dnd

  老牌拖拽库, 当以上不能满足需求时, 可以尝试用这个实现拖拽的各种细节效果.

  [![GitHub Repo stars](https://img.shields.io/github/stars/react-dnd/react-dnd?style=social)](https://github.com/react-dnd/react-dnd/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/react-dnd/react-dnd?style=social)](https://github.com/react-dnd/react-dnd/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/react-dnd/react-dnd?style=social)](https://github.com/react-dnd/react-dnd/commits)

### Form

- 👀 [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) 📋 React Hooks for forms validation (Web + React Native)

  https://react-hook-form.com/

  反传统 hook form 状态管理. 大量使用 ref 接管用户输入, 绕过 react 状态管理, 以达到减少 render, 提高性能的目的. 对 UI 组件要求苛刻.

  [![GitHub Repo stars](https://img.shields.io/github/stars/react-hook-form/react-hook-form?style=social)](https://github.com/react-hook-form/react-hook-form/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/react-hook-form/react-hook-form?style=social)](https://github.com/react-hook-form/react-hook-form/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/react-hook-form/react-hook-form?style=social)](https://github.com/react-hook-form/react-hook-form/commits)

- 👀 [alibaba/formily](https://github.com/alibaba/formily) Alibaba Group Unified Form Solution -- Support React/ReactNative/Vue2/Vue3

  https://v2.formilyjs.org/

  Form 可序列化解决方案. 包含 form 设计器和渲染器两部分, 功能十分复杂.

  [![GitHub Repo stars](https://img.shields.io/github/stars/alibaba/formily?style=social)](https://github.com/alibaba/formily/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/alibaba/formily?style=social)](https://github.com/alibaba/formily/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/alibaba/formily?style=social)](https://github.com/alibaba/formily/commits)

### Hook

- ⭐️ [streamich/react-use](https://github.com/streamich/react-use) React Hooks — 👍

  http://streamich.github.io/react-use

  React hooks 百宝箱, 准备写 hook 前先查一下是不是已经有了.

  [![GitHub Repo stars](https://img.shields.io/github/stars/streamich/react-use?style=social)](https://github.com/streamich/react-use/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/streamich/react-use?style=social)](https://github.com/streamich/react-use/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/streamich/react-use?style=social)](https://github.com/streamich/react-use/commits)

- ⭐️ [pmndrs/use-gesture](https://github.com/pmndrs/use-gesture) 👇Bread n butter utility for component-tied mouse/touch gestures in React and Vanilla Javascript.

  https://use-gesture.netlify.app/

  鼠标和触摸手势 hook.

  [![GitHub Repo stars](https://img.shields.io/github/stars/pmndrs/use-gesture?style=social)](https://github.com/pmndrs/use-gesture/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/pmndrs/use-gesture?style=social)](https://github.com/pmndrs/use-gesture/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/pmndrs/use-gesture?style=social)](https://github.com/pmndrs/use-gesture/commits)

- [immerjs/use-immer](https://github.com/immerjs/use-immer) Use immer to drive state with a React hooks

  基于 immer 的 useState.

  [![GitHub Repo stars](https://img.shields.io/github/stars/immerjs/use-immer?style=social)](https://github.com/immerjs/use-immer/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/immerjs/use-immer?style=social)](https://github.com/immerjs/use-immer/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/immerjs/use-immer?style=social)](https://github.com/immerjs/use-immer/commits)

### State Management

- ⭐️ [mobxjs/mobx](https://github.com/mobxjs/mobx) Simple, scalable state management.

  http://mobx.js.org/

  简单可伸缩的状态管理. React 一直不肯承认响应式数据流比单向数据流更实用, Proxy 出现后响应式数据的性能得到很大提升. 用 react 的方式渲染, 用 vue 的思维管理数据, 就是 mobx. 一个前端数据建模框架.

  [![GitHub Repo stars](https://img.shields.io/github/stars/mobxjs/mobx?style=social)](https://github.com/mobxjs/mobx/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/mobxjs/mobx?style=social)](https://github.com/mobxjs/mobx/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/mobxjs/mobx?style=social)](https://github.com/mobxjs/mobx/commits)

- [reduxjs/redux](https://github.com/reduxjs/redux) Predictable state container for JavaScript apps

  https://redux.js.org/

  这个不用介绍了吧. 很多时候你没的选.

  [![GitHub Repo stars](https://img.shields.io/github/stars/reduxjs/redux?style=social)](https://github.com/reduxjs/redux/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/reduxjs/redux?style=social)](https://github.com/reduxjs/redux/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/reduxjs/redux?style=social)](https://github.com/reduxjs/redux/commits)

- 👀 [pmndrs/zustand](https://github.com/pmndrs/zustand) 🐻 Bear necessities for state management in React

  https://zustand.surge.sh/

  思路上与 Redux 相似, 但从 `create` 到 `useStore` 显得很自然, 没有太多模板代码, 也没有那么多概念, 你可以渐进式的使用新功能.

  [![GitHub Repo stars](https://img.shields.io/github/stars/pmndrs/zustand?style=social)](https://github.com/pmndrs/zustand/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/pmndrs/zustand?style=social)](https://github.com/pmndrs/zustand/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/pmndrs/zustand?style=social)](https://github.com/pmndrs/zustand/commits)

- ⭐️ [tannerlinsley/react-query](https://github.com/tannerlinsley/react-query) ⚛️ Hooks for fetching, caching and updating asynchronous data in React

  https://react-query.tanstack.com/

  React 加载/缓存/更新 hook. 数据加载以 query key 加以区分, 相同的 key 并发时会自动去重, 数据默认有个“新鲜度”的概念, 组件重新 mount 或窗口重新 focus 时根据“新鲜度”决定是否重新加载. 一般把它看作分布式数据管理, 在组件中调用 API, 而不必过度关心数据的形状.

  [![GitHub Repo stars](https://img.shields.io/github/stars/tannerlinsley/react-query?style=social)](https://github.com/tannerlinsley/react-query/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/tannerlinsley/react-query?style=social)](https://github.com/tannerlinsley/react-query/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/tannerlinsley/react-query?style=social)](https://github.com/tannerlinsley/react-query/commits)

- [vercel/swr](https://github.com/vercel/swr) React Hooks for data fetching

  https://swr.vercel.app/

  与 react-query 同时期理念相近的作品. 名称取自于 `stale-while-revalidate`, 一个关于缓存失效策略的标准 [HTTP RFC 5861](https://tools.ietf.org/html/rfc5861).

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/swr?style=social)](https://github.com/vercel/swr/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/swr?style=social)](https://github.com/vercel/swr/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/swr?style=social)](https://github.com/vercel/swr/commits)

- [umijs/hox](https://github.com/umijs/hox) The next-generation state manager for React.

  建个 model, 写个 hook, 全局共享.

  [![GitHub Repo stars](https://img.shields.io/github/stars/umijs/hox?style=social)](https://github.com/umijs/hox/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/umijs/hox?style=social)](https://github.com/umijs/hox/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/umijs/hox?style=social)](https://github.com/umijs/hox/commits)

### Style

- ⭐️ [windicss/windicss](https://github.com/windicss/windicss) Next generation utility-first CSS framework.

  https://windicss.org/

  一个像 Tailwind CSS 一样的 CSS 工具框架. 快 10 倍.

  [![GitHub Repo stars](https://img.shields.io/github/stars/windicss/windicss?style=social)](https://github.com/windicss/windicss/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/windicss/windicss?style=social)](https://github.com/windicss/windicss/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/windicss/windicss?style=social)](https://github.com/windicss/windicss/commits)

### UI library

- ⭐️ [ant-design/ant-design](https://github.com/ant-design/ant-design) An enterprise-class UI design language and React UI library

  https://ant.design/

  蚂蚁出品, 曾经的 React 组件库榜首(被删库前). 几乎可以满足任何需求, 组件 API 设计上同时考虑前端和后端使用, 一些 API 有独到见解. 样式上使用 less 是个败笔, 现已积重难返. 国内项目可以盲选, 国外项目想办法说服客户.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ant-design/ant-design?style=social)](https://github.com/ant-design/ant-design/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ant-design/ant-design?style=social)](https://github.com/ant-design/ant-design/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ant-design/ant-design?style=social)](https://github.com/ant-design/ant-design/commits)

- [mui-org/material-ui](https://github.com/mui-org/material-ui) MUI (formerly Material-UI) is the React UI library you always wanted. Follow your own design system, or start with Material Design.

  https://mui.com/

  以 Google material design 为参照实现的第三方前端组件库. 口质和口碑极高, 样式使用自研的 css in js, 与其他技术不好搭配. 是否选择取决于设计稿.

  [![GitHub Repo stars](https://img.shields.io/github/stars/mui-org/material-ui?style=social)](https://github.com/mui-org/material-ui/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/mui-org/material-ui?style=social)](https://github.com/mui-org/material-ui/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/mui-org/material-ui?style=social)](https://github.com/mui-org/material-ui/commits)

- 👀 [reach/reach-ui](https://github.com/reach/reach-ui) The Accessible Foundation for React Apps and Design Systems

  https://reacttraining.com/reach-ui/

  A11y 基础框架. A11y 之所以难以实现是因为与 HTML 标准之间的代沟, 学习这里面的代码能帮你更好的理解 A11y 有多少细节需要考虑.

  [![GitHub Repo stars](https://img.shields.io/github/stars/reach/reach-ui?style=social)](https://github.com/reach/reach-ui/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/reach/reach-ui?style=social)](https://github.com/reach/reach-ui/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/reach/reach-ui?style=social)](https://github.com/reach/reach-ui/commits)

- 👀 [snackui/snackui](https://github.com/snackui/snackui) Write once React Native + Web UI kit. Optimizing compiler that flattens views, reduces bundle size and greatly improves performance 🏎. Normalizes media queries and themes between native and web so they work optimally in both environments.

  一个试图复刻 SwiftUI 的组件库. 许多坑还没有填平.

  [![GitHub Repo stars](https://img.shields.io/github/stars/snackui/snackui?style=social)](https://github.com/snackui/snackui/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/snackui/snackui?style=social)](https://github.com/snackui/snackui/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/snackui/snackui?style=social)](https://github.com/snackui/snackui/commits)

- [facebook/docusaurus](https://github.com/facebook/docusaurus) Easy to maintain open source documentation websites.

  https://docusaurus.io/

  Facebook 出品的文档站点生成器.

  [![GitHub Repo stars](https://img.shields.io/github/stars/facebook/docusaurus?style=social)](https://github.com/facebook/docusaurus/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/facebook/docusaurus?style=social)](https://github.com/facebook/docusaurus/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/facebook/docusaurus?style=social)](https://github.com/facebook/docusaurus/commits)

---

## JavaScript

### Data

- ⭐️ [ai/nanoid](https://github.com/ai/nanoid) A tiny (108 bytes), secure, URL-friendly, unique string ID generator for JavaScript

  https://zelark.github.io/nano-id-cc/

  ID 生成器. 小, 快, 短, 支持自定义字母表和长度.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ai/nanoid?style=social)](https://github.com/ai/nanoid/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ai/nanoid?style=social)](https://github.com/ai/nanoid/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ai/nanoid?style=social)](https://github.com/ai/nanoid/commits)

- ⭐️ [localForage/localForage](https://github.com/localForage/localForage) 💾 Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.

  https://localforage.github.io/localForage

  浏览器离线存储. 让你放心的操作 IndexedDB, WebSQL, localStorage, sessionStorage, 而不必在意浏览器的版本差异.

  [![GitHub Repo stars](https://img.shields.io/github/stars/localForage/localForage?style=social)](https://github.com/localForage/localForage/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/localForage/localForage?style=social)](https://github.com/localForage/localForage/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/localForage/localForage?style=social)](https://github.com/localForage/localForage/commits)

- ⭐️ [isaacs/node-lru-cache](https://github.com/isaacs/node-lru-cache) A cache object that deletes the least-recently-used items.

  基于 LRU(最近最少使用)算法实现的缓存库. 接口类似于 Map, 但是允许你设置容量, 容量不足时会自动清理最近最少使用的项目.

  [![GitHub Repo stars](https://img.shields.io/github/stars/isaacs/node-lru-cache?style=social)](https://github.com/isaacs/node-lru-cache/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/isaacs/node-lru-cache?style=social)](https://github.com/isaacs/node-lru-cache/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/isaacs/node-lru-cache?style=social)](https://github.com/isaacs/node-lru-cache/commits)

- ⭐️ [Stuk/jszip](https://github.com/Stuk/jszip) Create, read and edit .zip files with Javascript

  https://stuk.github.io/jszip/

  读写 zip 文件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/Stuk/jszip?style=social)](https://github.com/Stuk/jszip/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/Stuk/jszip?style=social)](https://github.com/Stuk/jszip/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/Stuk/jszip?style=social)](https://github.com/Stuk/jszip/commits)

- 👀 [inversify/InversifyJS](https://github.com/inversify/InversifyJS) A powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript.

  http://inversify.io/

  基于 decorator 的 loC([控制反转](https://zh.wikipedia.org/wiki/%E6%8E%A7%E5%88%B6%E5%8F%8D%E8%BD%AC))容器.

  [![GitHub Repo stars](https://img.shields.io/github/stars/inversify/InversifyJS?style=social)](https://github.com/inversify/InversifyJS/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/inversify/InversifyJS?style=social)](https://github.com/inversify/InversifyJS/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/inversify/InversifyJS?style=social)](https://github.com/inversify/InversifyJS/commits)

- [SheetJS/js-crc32](https://github.com/SheetJS/js-crc32) 🌀 JS standard CRC-32 implementation

  http://oss.sheetjs.com/js-crc32/

  CRC32 算法.

  [![GitHub Repo stars](https://img.shields.io/github/stars/SheetJS/js-crc32?style=social)](https://github.com/SheetJS/js-crc32/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/SheetJS/js-crc32?style=social)](https://github.com/SheetJS/js-crc32/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/SheetJS/js-crc32?style=social)](https://github.com/SheetJS/js-crc32/commits)

- [Jam3/math-as-code](https://github.com/Jam3/math-as-code) a cheat-sheet for mathematical notation in code form

  常见数学符号在代码中的表示法.

  [![GitHub Repo stars](https://img.shields.io/github/stars/Jam3/math-as-code?style=social)](https://github.com/Jam3/math-as-code/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/Jam3/math-as-code?style=social)](https://github.com/Jam3/math-as-code/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/Jam3/math-as-code?style=social)](https://github.com/Jam3/math-as-code/commits)

- 👀 [yjs/yjs](https://github.com/yjs/yjs) Shared data types for building collaborative software

  https://docs.yjs.dev/

  基于 CRDT 的协作数据管理. 主打富文本多人协作.

  [![GitHub Repo stars](https://img.shields.io/github/stars/yjs/yjs?style=social)](https://github.com/yjs/yjs/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/yjs/yjs?style=social)](https://github.com/yjs/yjs/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/yjs/yjs?style=social)](https://github.com/yjs/yjs/commits)

- [amark/gun](https://github.com/amark/gun) An open source cybersecurity protocol for syncing decentralized graph data.

  https://gun.eco/docs

  去中心化协同图形数据库.

  [![GitHub Repo stars](https://img.shields.io/github/stars/amark/gun?style=social)](https://github.com/amark/gun/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/amark/gun?style=social)](https://github.com/amark/gun/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/amark/gun?style=social)](https://github.com/amark/gun/commits)

- [faisalman/ua-parser-js](https://github.com/faisalman/ua-parser-js) UAParser.js - Detect Browser, Engine, OS, CPU, and Device type/model from User-Agent data. Supports browser & node.js environment.

  http://faisalman.github.io/ua-parser-js

  浏览器 User-Agent 检测工具.

  [![GitHub Repo stars](https://img.shields.io/github/stars/faisalman/ua-parser-js?style=social)](https://github.com/faisalman/ua-parser-js/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/faisalman/ua-parser-js?style=social)](https://github.com/faisalman/ua-parser-js/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/faisalman/ua-parser-js?style=social)](https://github.com/faisalman/ua-parser-js/commits)

- [hotoo/pinyin](https://github.com/hotoo/pinyin) 🇨🇳 汉字拼音 ➜ hàn zì pīn yīn

  https://hotoo.github.io/pinyin/

  [![GitHub Repo stars](https://img.shields.io/github/stars/hotoo/pinyin?style=social)](https://github.com/hotoo/pinyin/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/hotoo/pinyin?style=social)](https://github.com/hotoo/pinyin/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/hotoo/pinyin?style=social)](https://github.com/hotoo/pinyin/commits)

### Datetime

- ⭐️ [iamkun/dayjs](https://github.com/iamkun/dayjs) ⏰ Day.js 2kB immutable date-time library alternative to Moment.js with the same modern API

  https://day.js.org/

  日期时间库的最后胜出者.

  [![GitHub Repo stars](https://img.shields.io/github/stars/iamkun/dayjs?style=social)](https://github.com/iamkun/dayjs/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/iamkun/dayjs?style=social)](https://github.com/iamkun/dayjs/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/iamkun/dayjs?style=social)](https://github.com/iamkun/dayjs/commits)

### Frontend Framework

- 👀 [alpinejs/alpine](https://github.com/alpinejs/alpine) A rugged, minimal framework for composing JavaScript behavior in your markup.

  https://alpinejs.dev/

  一个精巧的前端框架. 一个 html 文件就够了.

  [![GitHub Repo stars](https://img.shields.io/github/stars/alpinejs/alpine?style=social)](https://github.com/alpinejs/alpine/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/alpinejs/alpine?style=social)](https://github.com/alpinejs/alpine/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/alpinejs/alpine?style=social)](https://github.com/alpinejs/alpine/commits)

### Micro Frontend

- 👀 [micro-zoe/micro-app](https://github.com/micro-zoe/micro-app) A minimalist solution for building micro front-end applications. 一种用于构建微前端应用的极简方案

  https://micro-zoe.github.io/micro-app/

  京东微前端解决方案. 特点是采用类似 WebComponent 这样的 Shadow DOM 技术实现, 尽可能减少对 host 和 app 进行改动.

  [![GitHub Repo stars](https://img.shields.io/github/stars/micro-zoe/micro-app?style=social)](https://github.com/micro-zoe/micro-app/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/micro-zoe/micro-app?style=social)](https://github.com/micro-zoe/micro-app/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/micro-zoe/micro-app?style=social)](https://github.com/micro-zoe/micro-app/commits)

- [umijs/qiankun](https://github.com/umijs/qiankun) 📦 🚀 Blazing fast, simple and complete solution for micro frontends.

  https://qiankun.umijs.org/

  蚂蚁微前端解决方案. 不是 iframe.

  [![GitHub Repo stars](https://img.shields.io/github/stars/umijs/qiankun?style=social)](https://github.com/umijs/qiankun/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/umijs/qiankun?style=social)](https://github.com/umijs/qiankun/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/umijs/qiankun?style=social)](https://github.com/umijs/qiankun/commits)

### Rich Text Editor

- ⭐️ [ueberdosis/tiptap](https://github.com/ueberdosis/tiptap) The headless editor framework for web artisans.

  https://tiptap.dev/

  基于 ProseMirror 的编辑器. 提供很多易用的功能, Schema 高度可定制, 你可以配置如何保存 json, 如何解析 html, 以及如何渲染到 DOM. 对于用户交互方面处理比较方面, 如果要继续深入, 则必须先掌握 ProseMirror.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ueberdosis/tiptap?style=social)](https://github.com/ueberdosis/tiptap/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ueberdosis/tiptap?style=social)](https://github.com/ueberdosis/tiptap/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ueberdosis/tiptap?style=social)](https://github.com/ueberdosis/tiptap/commits)

- [ianstormtaylor/slate](https://github.com/ianstormtaylor/slate) A completely customizable framework for building rich text editors. (Currently in beta.)

  http://slatejs.org/

  一个完全可定制的富文本框架.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ianstormtaylor/slate?style=social)](https://github.com/ianstormtaylor/slate/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ianstormtaylor/slate?style=social)](https://github.com/ianstormtaylor/slate/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ianstormtaylor/slate?style=social)](https://github.com/ianstormtaylor/slate/commits)

- ~~[quilljs/quill](https://github.com/quilljs/quill)~~ Quill is a modern WYSIWYG editor built for compatibility and extensibility.

  https://quilljs.com/

  🚫 不推荐. 放在这里是提醒大家 quill 作者已弃坑.

  [![GitHub Repo stars](https://img.shields.io/github/stars/quilljs/quill?style=social)](https://github.com/quilljs/quill/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/quilljs/quill?style=social)](https://github.com/quilljs/quill/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/quilljs/quill?style=social)](https://github.com/quilljs/quill/commits)

### Toolkit

- ⭐️ [axios/axios](https://github.com/axios/axios) Promise based HTTP client for the browser and node.js

  https://axios-http.com/

  基于 Promise 的 http 客户端.

  [![GitHub Repo stars](https://img.shields.io/github/stars/axios/axios?style=social)](https://github.com/axios/axios/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/axios/axios?style=social)](https://github.com/axios/axios/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/axios/axios?style=social)](https://github.com/axios/axios/commits)

- ⭐️ [visionmedia/debug](https://github.com/visionmedia/debug) A tiny JavaScript debugging utility modelled after Node.js core's debugging technique. Works in Node.js and web browsers

  小巧的 debug log 实用工具. 自动为每个 namespace 分配不同的颜色.

  [![GitHub Repo stars](https://img.shields.io/github/stars/visionmedia/debug?style=social)](https://github.com/visionmedia/debug/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/visionmedia/debug?style=social)](https://github.com/visionmedia/debug/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/visionmedia/debug?style=social)](https://github.com/visionmedia/debug/commits)

- ⭐️ [sindresorhus/promise-fun](https://github.com/sindresorhus/promise-fun) Promise packages, patterns, chat, and tutorials

  Promise 工具集.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/promise-fun?style=social)](https://github.com/sindresorhus/promise-fun/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/promise-fun?style=social)](https://github.com/sindresorhus/promise-fun/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/promise-fun?style=social)](https://github.com/sindresorhus/promise-fun/commits)

- [developit/greenlet](https://github.com/developit/greenlet) 🦎 Move an async function into its own thread.

  在单独线程里运行 async function. 基于 web worker.

  [![GitHub Repo stars](https://img.shields.io/github/stars/developit/greenlet?style=social)](https://github.com/developit/greenlet/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/developit/greenlet?style=social)](https://github.com/developit/greenlet/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/developit/greenlet?style=social)](https://github.com/developit/greenlet/commits)

### UI Widget

- ⭐️ [eligrey/FileSaver.js](https://github.com/eligrey/FileSaver.js) An HTML5 saveAs() FileSaver implementation

  前端保存文件. 弹出下载对话框, 支持二进制, 例如把 canvas 画布保存为图片, 使用 jszip 压缩文件并保存.

  [![GitHub Repo stars](https://img.shields.io/github/stars/eligrey/FileSaver.js?style=social)](https://github.com/eligrey/FileSaver.js/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/eligrey/FileSaver.js?style=social)](https://github.com/eligrey/FileSaver.js/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/eligrey/FileSaver.js?style=social)](https://github.com/eligrey/FileSaver.js/commits)

- ⭐️ [usablica/intro.js](https://github.com/usablica/intro.js) Lightweight, user-friendly onboarding tour library

  http://introjs.com/

  页面向导式 onboarding 指引.

  [![GitHub Repo stars](https://img.shields.io/github/stars/usablica/intro.js?style=social)](https://github.com/usablica/intro.js/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/usablica/intro.js?style=social)](https://github.com/usablica/intro.js/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/usablica/intro.js?style=social)](https://github.com/usablica/intro.js/commits)

- ⭐️ [popperjs/popper-core](https://github.com/popperjs/popper-core) 🍿Positioning tooltips and popovers is difficult. Popper is here to help!

  https://popper.js.org/

  Tooltip & Popover. 用于解决 Tooltip 和 Popover 定位困难的问题.

  [![GitHub Repo stars](https://img.shields.io/github/stars/popperjs/popper-core?style=social)](https://github.com/popperjs/popper-core/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/popperjs/popper-core?style=social)](https://github.com/popperjs/popper-core/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/popperjs/popper-core?style=social)](https://github.com/popperjs/popper-core/commits)

- [atomiks/tippyjs](https://github.com/atomiks/tippyjs) Tooltip, popover, dropdown, and menu library

  https://atomiks.github.io/tippyjs/

  基于 popperjs 的更易用的实现.

  [![GitHub Repo stars](https://img.shields.io/github/stars/atomiks/tippyjs?style=social)](https://github.com/atomiks/tippyjs/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/atomiks/tippyjs?style=social)](https://github.com/atomiks/tippyjs/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/atomiks/tippyjs?style=social)](https://github.com/atomiks/tippyjs/commits)

- [pqina/filepond](https://github.com/pqina/filepond) 🌊 A flexible and fun JavaScript file upload library

  https://pqina.nl/filepond

  又漂亮又好玩的文件上传组件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/pqina/filepond?style=social)](https://github.com/pqina/filepond/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/pqina/filepond?style=social)](https://github.com/pqina/filepond/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/pqina/filepond?style=social)](https://github.com/pqina/filepond/commits)

- [PrismJS/prism](https://github.com/PrismJS/prism) Lightweight, robust, elegant syntax highlighting.

  https://prismjs.com/

  代码语法高亮.

  [![GitHub Repo stars](https://img.shields.io/github/stars/PrismJS/prism?style=social)](https://github.com/PrismJS/prism/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/PrismJS/prism?style=social)](https://github.com/PrismJS/prism/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/PrismJS/prism?style=social)](https://github.com/PrismJS/prism/commits)

- [mathjax/MathJax](https://github.com/mathjax/MathJax) Beautiful and accessible math in all browsers

  http://www.mathjax.org/

  渲染漂亮的数学公式.

  [![GitHub Repo stars](https://img.shields.io/github/stars/mathjax/MathJax?style=social)](https://github.com/mathjax/MathJax/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/mathjax/MathJax?style=social)](https://github.com/mathjax/MathJax/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/mathjax/MathJax?style=social)](https://github.com/mathjax/MathJax/commits)

- [airbnb/lottie-web](https://github.com/airbnb/lottie-web) Render After Effects animations natively on Web, Android and iOS, and React Native.

  http://airbnb.io/lottie

  渲染 AE([Adobe After Effects](http://www.adobe.com/products/aftereffects.html))动画. 不必为如何实现设计师设计的动画而头疼.

  [![GitHub Repo stars](https://img.shields.io/github/stars/airbnb/lottie-web?style=social)](https://github.com/airbnb/lottie-web/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/airbnb/lottie-web?style=social)](https://github.com/airbnb/lottie-web/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/airbnb/lottie-web?style=social)](https://github.com/airbnb/lottie-web/commits)

- [szimek/signature_pad](https://github.com/szimek/signature_pad) HTML5 canvas based smooth signature drawing

  http://szimek.github.io/signature_pad/

  基于 Canvas 实现的手写板效果.

  [![GitHub Repo stars](https://img.shields.io/github/stars/szimek/signature_pad?style=social)](https://github.com/szimek/signature_pad/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/szimek/signature_pad?style=social)](https://github.com/szimek/signature_pad/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/szimek/signature_pad?style=social)](https://github.com/szimek/signature_pad/commits)

- [futurepress/epub.js](https://github.com/futurepress/epub.js) Enhanced eBooks in the browser.

  http://futurepress.org/

  浏览器中查看 epub 电子书文件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/futurepress/epub.js?style=social)](https://github.com/futurepress/epub.js/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/futurepress/epub.js?style=social)](https://github.com/futurepress/epub.js/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/futurepress/epub.js?style=social)](https://github.com/futurepress/epub.js/commits)

---

## TypeScript

- ⭐️ [adriengibrat/ts-custom-error](https://github.com/adriengibrat/ts-custom-error) Extend native Error to create custom errors

  Custom Error 父类

  [![GitHub Repo stars](https://img.shields.io/github/stars/adriengibrat/ts-custom-error?style=social)](https://github.com/adriengibrat/ts-custom-error/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/adriengibrat/ts-custom-error?style=social)](https://github.com/adriengibrat/ts-custom-error/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/adriengibrat/ts-custom-error?style=social)](https://github.com/adriengibrat/ts-custom-error/commits)

- 👀 [gcanti/fp-ts](https://github.com/gcanti/fp-ts) Functional programming in TypeScript

  https://gcanti.github.io/fp-ts/

  当 FP 遇到 Type. 在 JS 中实现 FP, 不仅仅是如何把功能做对, 把语法弄漂亮, 还要考虑如何让[类型推导更合理](https://dev.to/gcanti/series/680).

  [![GitHub Repo stars](https://img.shields.io/github/stars/gcanti/fp-ts?style=social)](https://github.com/gcanti/fp-ts/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/gcanti/fp-ts?style=social)](https://github.com/gcanti/fp-ts/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/gcanti/fp-ts?style=social)](https://github.com/gcanti/fp-ts/commits)

---

## WebAssembly

- [AssemblyScript/assemblyscript](https://github.com/AssemblyScript/assemblyscript) A TypeScript-like language for WebAssembly.

  https://assemblyscript.org/

  一种语法类似于 typescript 的 WebAssembly 编程语言.

  [![GitHub Repo stars](https://img.shields.io/github/stars/AssemblyScript/assemblyscript?style=social)](https://github.com/AssemblyScript/assemblyscript/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/AssemblyScript/assemblyscript?style=social)](https://github.com/AssemblyScript/assemblyscript/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/AssemblyScript/assemblyscript?style=social)](https://github.com/AssemblyScript/assemblyscript/commits)

---

## Node.js

### Algorithm

- 👀 [yanyiwu/nodejieba](https://github.com/yanyiwu/nodejieba) "结巴"中文分词的 Node.js 版本

  [![GitHub Repo stars](https://img.shields.io/github/stars/yanyiwu/nodejieba?style=social)](https://github.com/yanyiwu/nodejieba/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/yanyiwu/nodejieba?style=social)](https://github.com/yanyiwu/nodejieba/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/yanyiwu/nodejieba?style=social)](https://github.com/yanyiwu/nodejieba/commits)

### Build

- 👀 [vercel/ncc](https://github.com/vercel/ncc) Compile a Node.js project into a single file. Supports TypeScript, binary addons, dynamic requires.

  把 node 项目编译成单文件. 像 go 一样, 注意是连 node_modules 都编译进去. 适用于微服务, 或不方便安装 npm 的环境.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/ncc?style=social)](https://github.com/vercel/ncc/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/ncc?style=social)](https://github.com/vercel/ncc/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/ncc?style=social)](https://github.com/vercel/ncc/commits)

- 👀 [vercel/pkg](https://github.com/vercel/pkg) Package your Node.js project into an executable

  把 node 项目编译成可执行文件. 像 go 一样, 注意是连 node 都编译进去. 适用于不方便安装 node 的环境.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/pkg?style=social)](https://github.com/vercel/pkg/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/pkg?style=social)](https://github.com/vercel/pkg/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/pkg?style=social)](https://github.com/vercel/pkg/commits)

### Code Generator

- ⭐️ [dotansimha/graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) A tool for generating code based on a GraphQL schema and GraphQL operations (query/mutation/subscription), with flexible support for custom plugins.

  https://graphql-code-generator.com/

  基于 GraphQL 产生代码. 主要用于产生 typescript.

  [![GitHub Repo stars](https://img.shields.io/github/stars/dotansimha/graphql-code-generator?style=social)](https://github.com/dotansimha/graphql-code-generator/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/dotansimha/graphql-code-generator?style=social)](https://github.com/dotansimha/graphql-code-generator/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/dotansimha/graphql-code-generator?style=social)](https://github.com/dotansimha/graphql-code-generator/commits)

- [quicktype/quicktype](https://github.com/quicktype/quicktype) Generate types and converters from JSON, Schema, and GraphQL

  https://app.quicktype.io/

  基于 JSON/GraphQL 产生数据模型. 用于快速建模.

  [![GitHub Repo stars](https://img.shields.io/github/stars/quicktype/quicktype?style=social)](https://github.com/quicktype/quicktype/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/quicktype/quicktype?style=social)](https://github.com/quicktype/quicktype/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/quicktype/quicktype?style=social)](https://github.com/quicktype/quicktype/commits)

### Database

- ⭐️ [Automattic/mongoose](https://github.com/Automattic/mongoose) MongoDB object modeling designed to work in an asynchronous environment.

  https://mongoosejs.com/

  MongoDB 官方 ORM.

  [![GitHub Repo stars](https://img.shields.io/github/stars/Automattic/mongoose?style=social)](https://github.com/Automattic/mongoose/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/Automattic/mongoose?style=social)](https://github.com/Automattic/mongoose/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/Automattic/mongoose?style=social)](https://github.com/Automattic/mongoose/commits)

- ⭐️ [typeorm/typeorm](https://github.com/typeorm/typeorm) ORM for TypeScript and JavaScript (ES7, ES6, ES5). Supports MySQL, PostgreSQL, MariaDB, SQLite, MS SQL Server, Oracle, SAP Hana, WebSQL databases. Works in NodeJS, Browser, Ionic, Cordova and Electron platforms.

  http://typeorm.io/

  基于 decorator 建模的 ORM. 支持 MySQL, PostgreSQL, MariaDB, SQLite, MS SQL Server, Oracle, SAP Hana, WebSQL.

  [![GitHub Repo stars](https://img.shields.io/github/stars/typeorm/typeorm?style=social)](https://github.com/typeorm/typeorm/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/typeorm/typeorm?style=social)](https://github.com/typeorm/typeorm/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/typeorm/typeorm?style=social)](https://github.com/typeorm/typeorm/commits)

- 👀 [graphile/postgraphile](https://github.com/graphile/postgraphile) Execute one command (or mount one Node.js middleware) and get an instant high-performance GraphQL API for your PostgreSQL database!

  https://graphile.org/postgraphile

  基于 PostgreSQL 的 GraphQL api server. 如果你是一名 DBA 或者对 PostgreSQL 十分熟悉, 当你想快速的搭建一个 GraphQL api server 时, 可以尝试这个. 它允许你使用数据库中的用户权限来完成注册和登录, 并且把一些逻辑代码写在 PostgreSQL functions 里.

  [![GitHub Repo stars](https://img.shields.io/github/stars/graphile/postgraphile?style=social)](https://github.com/graphile/postgraphile/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/graphile/postgraphile?style=social)](https://github.com/graphile/postgraphile/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/graphile/postgraphile?style=social)](https://github.com/graphile/postgraphile/commits)

- [agenda/agenda](https://github.com/agenda/agenda) Lightweight job scheduling for Node.js

  http://agendajs.com/

  基于 MongoDB 的 轻量级计划任务.

  [![GitHub Repo stars](https://img.shields.io/github/stars/agenda/agenda?style=social)](https://github.com/agenda/agenda/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/agenda/agenda?style=social)](https://github.com/agenda/agenda/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/agenda/agenda?style=social)](https://github.com/agenda/agenda/commits)

### Model

- ⭐️ [typestack/class-validator](https://github.com/typestack/class-validator) Decorator-based property validation for classes.

  基于 decorator 的数据验证.

  [![GitHub Repo stars](https://img.shields.io/github/stars/typestack/class-validator?style=social)](https://github.com/typestack/class-validator/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/typestack/class-validator?style=social)](https://github.com/typestack/class-validator/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/typestack/class-validator?style=social)](https://github.com/typestack/class-validator/commits)

- ⭐️ [typestack/class-transformer](https://github.com/typestack/class-transformer) Decorator-based transformation, serialization, and deserialization between objects and classes.

  https://docs.typestack.community/class-transformer/v/develop/01-getting-started

  基于 decorator 的数据转换. plain -> class, class -> plain, class -> class.

  [![GitHub Repo stars](https://img.shields.io/github/stars/typestack/class-transformer?style=social)](https://github.com/typestack/class-transformer/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/typestack/class-transformer?style=social)](https://github.com/typestack/class-transformer/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/typestack/class-transformer?style=social)](https://github.com/typestack/class-transformer/commits)

- ⭐️ [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) Fast, flexible, and lean implementation of core jQuery designed specifically for the server.

  https://cheerio.js.org/

  类似于 jQuery 的后端 html 解析维护工具. 用于从网页中抓取有用的信息.

  [![GitHub Repo stars](https://img.shields.io/github/stars/cheeriojs/cheerio?style=social)](https://github.com/cheeriojs/cheerio/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/cheeriojs/cheerio?style=social)](https://github.com/cheeriojs/cheerio/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/cheeriojs/cheerio?style=social)](https://github.com/cheeriojs/cheerio/commits)

### Server

- ⭐️ [nestjs/nest](https://github.com/nestjs/nest) A progressive Node.js framework for building efficient, scalable, and enterprise-grade server-side applications on top of TypeScript & JavaScript (ES6, ES7, ES8) 🚀

  https://nestjs.com/

  渐进式企业级服务器框架. 随着需求增加可以不断安装新的模块, 基本上你能碰到的问题官网上都有对应的解决方案, 是同类产品中功能最强大的.

  [![GitHub Repo stars](https://img.shields.io/github/stars/nestjs/nest?style=social)](https://github.com/nestjs/nest/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/nestjs/nest?style=social)](https://github.com/nestjs/nest/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/nestjs/nest?style=social)](https://github.com/nestjs/nest/commits)

- ⭐️ [vercel/serve](https://github.com/vercel/serve) Static file serving and directory listing

  简单的静态文件服务器, 支持前端单页应用. 用于测试前端构建结果是否符合预期, 也可以直接用于生产服务器.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/serve?style=social)](https://github.com/vercel/serve/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/serve?style=social)](https://github.com/vercel/serve/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/serve?style=social)](https://github.com/vercel/serve/commits)

- [vercel/next.js](https://github.com/vercel/next.js) The React Framework

  https://nextjs.org/

  React SSR 服务器. 对组件的 SSR 支持有一定要求, 适合 React 项目需要一些简单的后端 API.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/next.js?style=social)](https://github.com/vercel/next.js/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/next.js?style=social)](https://github.com/vercel/next.js/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/next.js?style=social)](https://github.com/vercel/next.js/commits)

- [typicode/json-server](https://github.com/typicode/json-server) Get a full fake REST API with zero coding in less than 30 seconds (seriously)

  使用 json 作为数据库的增删改查服务器. 新建 `db.json`, 启动 `json-server`. 现在你拥有一个 REST API 了.

  [![GitHub Repo stars](https://img.shields.io/github/stars/typicode/json-server?style=social)](https://github.com/typicode/json-server/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/typicode/json-server?style=social)](https://github.com/typicode/json-server/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/typicode/json-server?style=social)](https://github.com/typicode/json-server/commits)

- [davewasmer/devcert](https://github.com/davewasmer/devcert) Local HTTPS development made easy

  本地开发时对任意域名启用 https.

  [![GitHub Repo stars](https://img.shields.io/github/stars/davewasmer/devcert?style=social)](https://github.com/davewasmer/devcert/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/davewasmer/devcert?style=social)](https://github.com/davewasmer/devcert/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/davewasmer/devcert?style=social)](https://github.com/davewasmer/devcert/commits)

### Terminal

- ⭐️ [open-cli-tools/concurrently](https://github.com/open-cli-tools/concurrently) Run commands concurrently. Like `npm run watch-js & npm run watch-less` but better.

  并行执行命令.

  [![GitHub Repo stars](https://img.shields.io/github/stars/open-cli-tools/concurrently?style=social)](https://github.com/open-cli-tools/concurrently/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/open-cli-tools/concurrently?style=social)](https://github.com/open-cli-tools/concurrently/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/open-cli-tools/concurrently?style=social)](https://github.com/open-cli-tools/concurrently/commits)

- ⭐️ [sindresorhus/execa](https://github.com/sindresorhus/execa) Process execution for humans

  人性化的进程调用工具. 比 `child_process.spawn()` 简便, 支持 async.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/execa?style=social)](https://github.com/sindresorhus/execa/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/execa?style=social)](https://github.com/sindresorhus/execa/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/execa?style=social)](https://github.com/sindresorhus/execa/commits)

- ⭐️ [chalk/chalk](https://github.com/chalk/chalk) 🖍 Terminal string styling done right

  命令行 ANSI 颜色样式. 蜡笔, 不言而喻.

  [![GitHub Repo stars](https://img.shields.io/github/stars/chalk/chalk?style=social)](https://github.com/chalk/chalk/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/chalk/chalk?style=social)](https://github.com/chalk/chalk/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/chalk/chalk?style=social)](https://github.com/chalk/chalk/commits)

- ⭐️ [isaacs/node-glob](https://github.com/isaacs/node-glob) glob functionality for node.js

  Glob 字符串解析器. 我们经常写的 `**/*.js` 就是由这个库解析匹配的, 来自于 Npm 作者.

  [![GitHub Repo stars](https://img.shields.io/github/stars/isaacs/node-glob?style=social)](https://github.com/isaacs/node-glob/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/isaacs/node-glob?style=social)](https://github.com/isaacs/node-glob/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/isaacs/node-glob?style=social)](https://github.com/isaacs/node-glob/commits)

- ⭐️ [sindresorhus/del-cli](https://github.com/sindresorhus/del-cli) Delete files and directories

  删除文件和目录. 会检测并防止意外删除项目之外的文件, 一般用于构建和自动化等场景.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/del-cli?style=social)](https://github.com/sindresorhus/del-cli/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/del-cli?style=social)](https://github.com/sindresorhus/del-cli/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/del-cli?style=social)](https://github.com/sindresorhus/del-cli/commits)

- ⭐️ [sindresorhus/get-port](https://github.com/sindresorhus/get-port) Get an available TCP port

  获取可用端口号. 如果你的程序不需要固定的端口号, 可以用这个库. 例如 vite 默认使用 3000 端口, 不可用时会尝试 3001 3002.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/get-port?style=social)](https://github.com/sindresorhus/get-port/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/get-port?style=social)](https://github.com/sindresorhus/get-port/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/get-port?style=social)](https://github.com/sindresorhus/get-port/commits)

- ⭐️ [tiaanduplessis/kill-port](https://github.com/tiaanduplessis/kill-port) ❌ Kill the process running on given port

  杀掉占用端口的进程. 纯 js 跨平台, 用于必须运行在指定端口的场景, 多半是你自己的上一个进程没有正确退出.

  [![GitHub Repo stars](https://img.shields.io/github/stars/tiaanduplessis/kill-port?style=social)](https://github.com/tiaanduplessis/kill-port/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/tiaanduplessis/kill-port?style=social)](https://github.com/tiaanduplessis/kill-port/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/tiaanduplessis/kill-port?style=social)](https://github.com/tiaanduplessis/kill-port/commits)

- ⭐️ [davidtheclark/cosmiconfig](https://github.com/davidtheclark/cosmiconfig) Find and load configuration from a package.json property, rc file, or CommonJS module

  配置搜索加载工具. 有没有好奇为什么知名工具的配置可以支持那么多种格式 `package.json` `.json` `.yaml` `*rc` `.config.js`? cosmiconfig 就是专门解决这个问题的.

  [![GitHub Repo stars](https://img.shields.io/github/stars/davidtheclark/cosmiconfig?style=social)](https://github.com/davidtheclark/cosmiconfig/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/davidtheclark/cosmiconfig?style=social)](https://github.com/davidtheclark/cosmiconfig/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/davidtheclark/cosmiconfig?style=social)](https://github.com/davidtheclark/cosmiconfig/commits)

- ⭐️ [evanshortiss/env-var](https://github.com/evanshortiss/env-var) Verification, sanitization, and type coercion for environment variables in Node.js

  获取 ENV 并转化为确定的类型, 支持验证, 默认值, 和 typescript.

  [![GitHub Repo stars](https://img.shields.io/github/stars/evanshortiss/env-var?style=social)](https://github.com/evanshortiss/env-var/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/evanshortiss/env-var?style=social)](https://github.com/evanshortiss/env-var/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/evanshortiss/env-var?style=social)](https://github.com/evanshortiss/env-var/commits)

- [facebook/jscodeshift](https://github.com/facebook/jscodeshift) A JavaScript codemod toolkit.

  代码修改工具. Facebook 为了让 react 升级更平滑而推出的迁移工具, Antd MobX 都曾在大版本升级时基于 jscodeshift 实现迁移.

  [![GitHub Repo stars](https://img.shields.io/github/stars/facebook/jscodeshift?style=social)](https://github.com/facebook/jscodeshift/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/facebook/jscodeshift?style=social)](https://github.com/facebook/jscodeshift/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/facebook/jscodeshift?style=social)](https://github.com/facebook/jscodeshift/commits)

### Test

- ⭐️ [nock/nock](https://github.com/nock/nock) HTTP server mocking and expectations library for Node.js

  HTTP server mocking. 老牌 network mock 库, 持续更新.

  [![GitHub Repo stars](https://img.shields.io/github/stars/nock/nock?style=social)](https://github.com/nock/nock/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/nock/nock?style=social)](https://github.com/nock/nock/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/nock/nock?style=social)](https://github.com/nock/nock/commits)

- [vercel/test-listen](https://github.com/vercel/test-listen) Quick ephemeral URLs for your tests

  启动 http server 并获取 url 用于后续测试.

  [![GitHub Repo stars](https://img.shields.io/github/stars/vercel/test-listen?style=social)](https://github.com/vercel/test-listen/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/vercel/test-listen?style=social)](https://github.com/vercel/test-listen/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/vercel/test-listen?style=social)](https://github.com/vercel/test-listen/commits)

- 😝 [auchenberg/volkswagen](https://github.com/auchenberg/volkswagen) 🙈 Volkswagen detects when your tests are being run in a CI server, and makes them pass.

  检测当前环境, 如果是 CI 则所有测试全部通过.

  [![GitHub Repo stars](https://img.shields.io/github/stars/auchenberg/volkswagen?style=social)](https://github.com/auchenberg/volkswagen/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/auchenberg/volkswagen?style=social)](https://github.com/auchenberg/volkswagen/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/auchenberg/volkswagen?style=social)](https://github.com/auchenberg/volkswagen/commits)

---

## CSS

- ⭐️ [cognitom/paper-css](https://github.com/cognitom/paper-css) Paper CSS for happy printing

  一比一还原页面打印时的效果. 例如 A4 纸的打印效果, 可用于实现包含纸张概念的页面样式.

  [![GitHub Repo stars](https://img.shields.io/github/stars/cognitom/paper-css?style=social)](https://github.com/cognitom/paper-css/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/cognitom/paper-css?style=social)](https://github.com/cognitom/paper-css/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/cognitom/paper-css?style=social)](https://github.com/cognitom/paper-css/commits)

- [marvelapp/devices.css](https://github.com/marvelapp/devices.css) Pure CSS phones and tablets

  绘制各种手机/平板.

  [![GitHub Repo stars](https://img.shields.io/github/stars/marvelapp/devices.css?style=social)](https://github.com/marvelapp/devices.css/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/marvelapp/devices.css?style=social)](https://github.com/marvelapp/devices.css/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/marvelapp/devices.css?style=social)](https://github.com/marvelapp/devices.css/commits)

---

## Serverless

- ⭐️ [serverless/serverless](https://github.com/serverless/serverless) ⚡ Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more! –

  https://serverless.com/

  支持众多云服务的 serverless 框架. AWS Lambda, Azure Functions, Tencent SCF, Google Cloud Functions, Knative Serving, Alibaba FC, Cloudflare Workers, Fn, Kubeless, Apache OpenWhisk, Spotinst Functions.

  [![GitHub Repo stars](https://img.shields.io/github/stars/serverless/serverless?style=social)](https://github.com/serverless/serverless/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/serverless/serverless?style=social)](https://github.com/serverless/serverless/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/serverless/serverless?style=social)](https://github.com/serverless/serverless/commits)

---

## Shell

- ⭐️ [nvm-sh/nvm](https://github.com/nvm-sh/nvm) Node Version Manager - POSIX-compliant bash script to manage multiple active node.js versions

  Node 版本管理工具. 允许多个版本共存, 可以用 `.nvmrc` 文件指定当前目录用哪个版本的 node.

  [![GitHub Repo stars](https://img.shields.io/github/stars/nvm-sh/nvm?style=social)](https://github.com/nvm-sh/nvm/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/nvm-sh/nvm?style=social)](https://github.com/nvm-sh/nvm/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/nvm-sh/nvm?style=social)](https://github.com/nvm-sh/nvm/commits)

- ⭐️ [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) 🙃 A delightful community-driven (with 1900+ contributors) framework for managing your zsh configuration. Includes 300+ optional plugins (rails, git, OSX, hub, docker, homebrew, node, php, python, etc), 140+ themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community.

  https://ohmyz.sh/

  ZSH 配置管理.

  [![GitHub Repo stars](https://img.shields.io/github/stars/ohmyzsh/ohmyzsh?style=social)](https://github.com/ohmyzsh/ohmyzsh/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/ohmyzsh/ohmyzsh?style=social)](https://github.com/ohmyzsh/ohmyzsh/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/ohmyzsh/ohmyzsh?style=social)](https://github.com/ohmyzsh/ohmyzsh/commits)

- ⭐️ [sindresorhus/pure](https://github.com/sindresorhus/pure) Pretty, minimal and fast ZSH prompt

  ZSH 轻量快速提示符. 支持显示 git status 和 command 执行时间.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/pure?style=social)](https://github.com/sindresorhus/pure/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/pure?style=social)](https://github.com/sindresorhus/pure/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/pure?style=social)](https://github.com/sindresorhus/pure/commits)

- ⭐️ [sindresorhus/np](https://github.com/sindresorhus/np) A better `npm publish`

  一个更好的 `npm publish` 命令. 用于 release 项目, 自动构建, 判断分支, 提交到 git, 提交到 npm, 发布 github release.

  [![GitHub Repo stars](https://img.shields.io/github/stars/sindresorhus/np?style=social)](https://github.com/sindresorhus/np/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sindresorhus/np?style=social)](https://github.com/sindresorhus/np/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sindresorhus/np?style=social)](https://github.com/sindresorhus/np/commits)

---

## Book

- ⭐️ [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) A book series on JavaScript. @YDKJS on twitter.

  你不懂 JS. 这本书不是标题党, 作者不会跟你讲 0.1 + 0.2 != 0.3 这种问题, 而是讲实实在在的有用的细节.

  [![GitHub Repo stars](https://img.shields.io/github/stars/getify/You-Dont-Know-JS?style=social)](https://github.com/getify/You-Dont-Know-JS/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/getify/You-Dont-Know-JS?style=social)](https://github.com/getify/You-Dont-Know-JS/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/getify/You-Dont-Know-JS?style=social)](https://github.com/getify/You-Dont-Know-JS/commits)

---

## Design

- 👀 [airbnb/react-sketchapp](https://github.com/airbnb/react-sketchapp) render React components to Sketch ⚛️💎

  http://airbnb.io/react-sketchapp/

  使用 react 组件写 sketch. 为什么? Sketch 文件不好管理, 新旧版本不兼容. 改成 react 组件写法, 需要时输出到 sketch 文件.

  [![GitHub Repo stars](https://img.shields.io/github/stars/airbnb/react-sketchapp?style=social)](https://github.com/airbnb/react-sketchapp/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/airbnb/react-sketchapp?style=social)](https://github.com/airbnb/react-sketchapp/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/airbnb/react-sketchapp?style=social)](https://github.com/airbnb/react-sketchapp/commits)

- [lllyasviel/style2paints](https://github.com/lllyasviel/style2paints) sketch + style = paints 🎨 (TOG2018/SIGGRAPH2018ASIA)

  AI 填色.

  [![GitHub Repo stars](https://img.shields.io/github/stars/lllyasviel/style2paints?style=social)](https://github.com/lllyasviel/style2paints/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/lllyasviel/style2paints?style=social)](https://github.com/lllyasviel/style2paints/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/lllyasviel/style2paints?style=social)](https://github.com/lllyasviel/style2paints/commits)

---

## Misc

- ⭐️ [github/gitignore](https://github.com/github/gitignore) A collection of useful .gitignore templates

  常见 `.gitignore` 模板. 在 github 上新建 repo 时选择的模板来源于这里.

  [![GitHub Repo stars](https://img.shields.io/github/stars/github/gitignore?style=social)](https://github.com/github/gitignore/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/github/gitignore?style=social)](https://github.com/github/gitignore/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/github/gitignore?style=social)](https://github.com/github/gitignore/commits)

- ⭐️ [sparanoid/chinese-copywriting-guidelines](https://github.com/sparanoid/chinese-copywriting-guidelines) Chinese copywriting guidelines for better written communication／中文文案排版指北

  [![GitHub Repo stars](https://img.shields.io/github/stars/sparanoid/chinese-copywriting-guidelines?style=social)](https://github.com/sparanoid/chinese-copywriting-guidelines/stargazers)
  [![GitHub release](https://img.shields.io/github/v/release/sparanoid/chinese-copywriting-guidelines?style=social)](https://github.com/sparanoid/chinese-copywriting-guidelines/releases)
  [![GitHub last commit](https://img.shields.io/github/last-commit/sparanoid/chinese-copywriting-guidelines?style=social)](https://github.com/sparanoid/chinese-copywriting-guidelines/commits)

---

## RIP

> 曾经的辉煌

- [browserify/browserify](https://github.com/browserify/browserify) browser-side require() the node.js way. 前端打包工具的鼻祖.
- [gulpjs/gulp](https://github.com/gulpjs/gulp) A toolkit to automate & enhance your workflow. 流式自动化编排.
- [google/traceur-compiler](https://github.com/google/traceur-compiler) Traceur is a JavaScript.next-to-JavaScript-of-today compiler. 因巨大的 runtime 和丑陋的生成结果而输给了 babel.
- [ractivejs/ractive](https://github.com/ractivejs/ractive) Next-generation DOM manipulation. 已经变成上一代.
- [assaf/zombie](https://github.com/assaf/zombie) Insanely fast, full-stack, headless browser testing using node.js. 早期 e2e 框架, 不需要安装浏览器.
