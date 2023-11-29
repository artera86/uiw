<p align="center">
  <a href="https://uiwjs.github.io">
    <img alt="uiw LOGO" width="150" src="https://raw.githubusercontent.com/uiwjs/uiw/92f189f53312f1177466f48991736f95f86da0a6/src/assets/logo-README.svg?sanitize=true">
  </a>
</p>
<p align="center">
  <a href="https://jaywcjlove.github.io/#/sponsor">
    <img alt="Buy me a coffee" src="https://img.shields.io/badge/Buy%20me%20a%20coffee-048754?logo=buymeacoffee">
  </a>
  <a href="https://github.com/uiwjs/uiw/actions">
    <img alt="Github Actions" src="https://github.com/uiwjs/uiw/workflows/Build%20uiw/badge.svg">
  </a>
  <a href="https://github.com/uiwjs/uiw">
    <img alt="License MIT" src="https://img.shields.io/dub/l/vibe-d.svg">
  </a>
  <a href="https://github.com/facebook/jest">
    <img alt="jest" src="https://jestjs.io/img/jest-badge.svg">
  </a>
  <a href="https://gitpod.io/#https://github.com/uiwjs/uiw">
    <img alt="Open in Gitpod" src="https://shields.io/badge/Open%20in-Gitpod-green?logo=Gitpod">
  </a>
  <br>
  <a href="https://github.com/uiwjs/uiw/releases">
    <img alt="Github Releases" src="https://img.shields.io/github/release/uiwjs/uiw.svg">
  </a>
  <a href="https://www.npmjs.com/package/uiw">
    <img alt="npm version" src="https://img.shields.io/npm/v/uiw.svg">
  </a>
  <a href="https://github.com/uiwjs/uiw/stargazers">
    <img alt="Github Stars" src="https://img.shields.io/github/stars/uiwjs/uiw.svg">
  </a>
</p>

<p align="center">
  <a href="https://uiwjs.github.io"><img alt="uiw document website" src="https://raw.githubusercontent.com/uiwjs/uiw/92f189f53312f1177466f48991736f95f86da0a6/src/assets/uiw-doc.png" /></a>
</p>

## uiw

一个高质量的 UI 工具包，一个 React 16+ 的组件库。 💘

### 安装

```bash
npm install uiw --save
```

你可以使用 [`kkt`](https://github.com/kktjs/kkt) 快速创建一个 react + uiw 的项目。

```bash
npx create-kkt my-app -e uiw
# or npm
$ npm create kkt my-app -e uiw
# or yarn
$ yarn create kkt my-app -e uiw
```

您可以使用 [uiw v1.x](https://github.com/uiwjs/uiw/tree/v1) 版本。 [请在此处查看文档](https://github.com/uiwjs/uiw/tree/v1)。([**`npx`**](https://github.com/npm/npm/releases/tag/v5.2.0) 需要 `npm 5.2+` 及更高版本。）

### 基本使用

```js
import React from "react";
import ReactDOM from "react-dom";
import { Button } from "uiw";

ReactDOM.render(
  <Button type="primary">Hello</Button>,
  document.getElementById("app")
);
```

### 文档

有关更多信息，请访问 [uiwjs.github.io](https://uiwjs.github.io) 网站。

或者在 VSCode 使用 [`vscode-uiw`](https://github.com/uiwjs/vscode-uiw) 插件预览中打开：

[![Open in VSCode](https://jaywcjlove.github.io/sb/open/open-in-vscode.svg)](https://marketplace.visualstudio.com/items?itemName=uiw.uiw)

### 依赖包

这个 `git` 仓库是一个使用 [`Lerna`](https://github.com/lerna/lerna) 构建的仓库。它包含以下一些软件包：

Package | Downloads | Version | Description
----- | ----- | ----- | -----
[`uiw`](/packages/uiw) | [![npm downloads](https://badgen.net/npm/dw/uiw?label=npm&color=dd4e4c)](https://www.npmjs.com/package/uiw) | [![npm version](https://img.shields.io/npm/v/uiw.svg?maxAge=3600)](https://www.npmjs.com/package/uiw) | - 
[`@uiw/react-affix`](/packages/react-affix) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-affix?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-affix) | [![npm version](https://img.shields.io/npm/v/@uiw/react-affix.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-affix) | -
[`@uiw/react-alert`](/packages/react-alert) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-alert?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-alert) | [![npm version](https://img.shields.io/npm/v/@uiw/react-alert.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-alert) | -
[`@uiw/react-avatar`](/packages/react-avatar) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-avatar?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-avatar) | [![npm version](https://img.shields.io/npm/v/@uiw/react-avatar.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-avatar)                       | -
[`@uiw/react-back-top`](/packages/react-back-top) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-back-top?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-back-top) | [![npm version](https://img.shields.io/npm/v/@uiw/react-back-top.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-back-top)                   | -
[`@uiw/react-badge`](/packages/react-badge) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-badge?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-badge) | [![npm version](https://img.shields.io/npm/v/@uiw/react-badge.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-badge)                         | -
[`@uiw/react-breadcrumb`](/packages/react-breadcrumb) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-breadcrumb?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-breadcrumb) | [![npm version](https://img.shields.io/npm/v/@uiw/react-breadcrumb.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-breadcrumb)               | -
[`@uiw/react-button`](/packages/react-button) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-button?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-button) | [![npm version](https://img.shields.io/npm/v/@uiw/react-button.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-button)                       | -
[`@uiw/react-button-group`](/packages/react-button-group) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-button-group?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-button-group) | [![npm version](https://img.shields.io/npm/v/@uiw/react-button-group.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-button-group)           | -
[`@uiw/react-calendar`](/packages/react-calendar) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-calendar?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-calendar) | [![npm version](https://img.shields.io/npm/v/@uiw/react-calendar.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-calendar)                   | -
[`@uiw/react-card`](/packages/react-card) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-card?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-card) | [![npm version](https://img.shields.io/npm/v/@uiw/react-card.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-card)                           | -
[`@uiw/react-checkbox`](/packages/react-checkbox) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-checkbox?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-checkbox) | [![npm version](https://img.shields.io/npm/v/@uiw/react-checkbox.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-checkbox)                   | -
[`@uiw/react-collapse`](/packages/react-collapse) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-collapse?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-collapse) | [![npm version](https://img.shields.io/npm/v/@uiw/react-collapse.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-collapse)                   | -
[`@uiw/react-copy-to-clipboard`](/packages/react-copy-to-clipboard) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-copy-to-clipboard?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-copy-to-clipboard) | [![npm version](https://img.shields.io/npm/v/@uiw/react-copy-to-clipboard.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-copy-to-clipboard) | -
[`@uiw/react-date-input`](/packages/react-date-input) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-date-input?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-date-input) | [![npm version](https://img.shields.io/npm/v/@uiw/react-date-input.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-date-input)               | -
[`@uiw/react-date-picker`](/packages/react-date-picker) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-date-picker?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-date-picker) | [![npm version](https://img.shields.io/npm/v/@uiw/react-date-picker.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-date-picker)             | -
[`@uiw/react-descriptions`](/packages/react-descriptions) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-descriptions?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-descriptions) | [![npm version](https://img.shields.io/npm/v/@uiw/react-descriptions.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-descriptions)           | -
[`@uiw/react-divider`](/packages/react-divider) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-divider?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-divider) | [![npm version](https://img.shields.io/npm/v/@uiw/react-divider.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-divider)                     | -
[`@uiw/react-drawer`](/packages/react-drawer) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-drawer?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-drawer) | [![npm version](https://img.shields.io/npm/v/@uiw/react-drawer.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-drawer)                       | -
[`@uiw/react-dropdown`](/packages/react-dropdown) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-dropdown?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-dropdown) | [![npm version](https://img.shields.io/npm/v/@uiw/react-dropdown.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-dropdown) 
[`@uiw/react-empty`](/packages/react-empty) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-empty?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-empty) | [![npm version](https://img.shields.io/npm/v/@uiw/react-empty.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-empty)                   | -
[`@uiw/react-file-input`](/packages/react-file-input) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-file-input?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-file-input) | [![npm version](https://img.shields.io/npm/v/@uiw/react-file-input.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-file-input)               | -
[`@uiw/react-form`](/packages/react-form) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-form?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-form) | [![npm version](https://img.shields.io/npm/v/@uiw/react-form.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-form)                           | -
[`@uiw/react-grid`](/packages/react-grid) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-grid?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-grid) | [![npm version](https://img.shields.io/npm/v/@uiw/react-grid.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-grid)                           | -
[`@uiw/react-icon`](/packages/react-icon) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-icon?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-icon) | [![npm version](https://img.shields.io/npm/v/@uiw/react-icon.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-icon)                           | -
[`@uiw/react-input`](/packages/react-input) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-input?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-input) | [![npm version](https://img.shields.io/npm/v/@uiw/react-input.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-input)                         | -
[`@uiw/react-list`](/packages/react-list) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-list?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-list) | [![npm version](https://img.shields.io/npm/v/@uiw/react-list.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-list)                           | -
[`@uiw/react-loader`](/packages/react-loader) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-loader?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-loader) | [![npm version](https://img.shields.io/npm/v/@uiw/react-loader.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-loader)                       | -
[`@uiw/react-menu`](/packages/react-menu) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-menu?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-menu) | [![npm version](https://img.shields.io/npm/v/@uiw/react-menu.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-menu)                           | -
[`@uiw/react-message`](/packages/react-message) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-message?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-message) | [![npm version](https://img.shields.io/npm/v/@uiw/react-message.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-message)                     | -
[`@uiw/react-modal`](/packages/react-modal) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-modal?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-modal) | [![npm version](https://img.shields.io/npm/v/@uiw/react-modal.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-modal)                         | -
[`@uiw/react-month-picker`](/packages/react-month-picker) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-month-picker?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-month-picker) | [![npm version](https://img.shields.io/npm/v/@uiw/react-month-picker.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-month-picker)           | -
[`@uiw/react-notify`](/packages/react-notify) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-notify?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-notify) | [![npm version](https://img.shields.io/npm/v/@uiw/react-notify.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-notify)                       | -
[`@uiw/react-overlay`](/packages/react-overlay) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-overlay?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-overlay) | [![npm version](https://img.shields.io/npm/v/@uiw/react-overlay.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-overlay)                     | -
[`@uiw/react-overlay-trigger`](/packages/react-overlay-trigger) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-overlay-trigger?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-overlay-trigger) | [![npm version](https://img.shields.io/npm/v/@uiw/react-overlay-trigger.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-overlay-trigger)     | -
[`@uiw/react-pagination`](/packages/react-pagination) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-pagination?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-pagination) | [![npm version](https://img.shields.io/npm/v/@uiw/react-pagination.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-pagination)               | -
[`@uiw/react-pin-code`](/packages/react-pin-code) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-pin-code?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-pin-code) | [![npm version](https://img.shields.io/npm/v/@uiw/react-pin-code.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-pin-code)               | -
[`@uiw/react-popover`](/packages/react-popover) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-popover?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-popover) | [![npm version](https://img.shields.io/npm/v/@uiw/react-popover.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-popover)                     | -
[`@uiw/react-portal`](/packages/react-portal) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-portal?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-portal) | [![npm version](https://img.shields.io/npm/v/@uiw/react-portal.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-portal)                       | -
[`@uiw/react-progress`](/packages/react-progress) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-progress?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-progress) | [![npm version](https://img.shields.io/npm/v/@uiw/react-progress.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-progress)                   | -
[`@uiw/react-radio`](/packages/react-radio) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-radio?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-radio) | [![npm version](https://img.shields.io/npm/v/@uiw/react-radio.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-radio)                         | -
[`@uiw/react-rate`](/packages/react-rate) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-rate?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-rate) | [![npm version](https://img.shields.io/npm/v/@uiw/react-rate.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-rate)                           | -
[`@uiw/react-search-select`](/packages/react-search-select) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-search-select?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-search-select) | [![npm version](https://img.shields.io/npm/v/@uiw/react-search-select.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-search-select) | -
[`@uiw/react-search-tree`](/packages/react-search-tree) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-search-tree?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-search-tree) | [![npm version](https://img.shields.io/npm/v/@uiw/react-search-tree.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-search-tree) | -
[`@uiw/react-select`](/packages/react-select) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-select?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-select) | [![npm version](https://img.shields.io/npm/v/@uiw/react-select.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-select)                       | -
[`@uiw/react-slider`](/packages/react-slider) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-slider?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-slider) | [![npm version](https://img.shields.io/npm/v/@uiw/react-slider.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-slider)                       | -
[`@uiw/react-steps`](/packages/react-steps) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-steps?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-steps) | [![npm version](https://img.shields.io/npm/v/@uiw/react-steps.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-steps)                         | -
[`@uiw/react-switch`](/packages/react-switch) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-switch?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-switch) | [![npm version](https://img.shields.io/npm/v/@uiw/react-switch.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-switch)                       | -
[`@uiw/react-table`](/packages/react-table) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-table?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-table) | [![npm version](https://img.shields.io/npm/v/@uiw/react-table.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-table)                         | -
[`@uiw/react-tabs`](/packages/react-tabs) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-tabs?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-tabs) | [![npm version](https://img.shields.io/npm/v/@uiw/react-tabs.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-tabs)                           | -
[`@uiw/react-tag`](/packages/react-tag) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-tag?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-tag) | [![npm version](https://img.shields.io/npm/v/@uiw/react-tag.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-tag)                             | -
[`@uiw/react-textarea`](/packages/react-textarea) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-textarea?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-textarea) | [![npm version](https://img.shields.io/npm/v/@uiw/react-textarea.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-textarea)                   | -
[`@uiw/react-time-picker`](/packages/react-time-picker) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-time-picker?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-time-picker) | [![npm version](https://img.shields.io/npm/v/@uiw/react-time-picker.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-time-picker)             | -
[`@uiw/react-tooltip`](/packages/react-tooltip) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-tooltip?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-tooltip) | [![npm version](https://img.shields.io/npm/v/@uiw/react-tooltip.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-tooltip)                     | -
[`@uiw/react-tree`](/packages/react-tree) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-tree?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-tree) | [![npm version](https://img.shields.io/npm/v/@uiw/react-tree.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-tree)                           | -
[`@uiw/react-tree-checked`](/packages/react-tree-checked) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-tree-checked?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-tree-checked) | [![npm version](https://img.shields.io/npm/v/@uiw/react-tree-checked.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-tree-checked)           | -
[`@uiw/utils`](/packages/utils) | [![npm downloads](https://badgen.net/npm/dw/@uiw/utils?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/utils) | [![npm version](https://img.shields.io/npm/v/@uiw/utils.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/utils)                                     | -
[`@uiw/react-split`](https://github.com/uiwjs/react-split) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-split?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-split) | [![npm version](https://img.shields.io/npm/v/@uiw/react-split.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-split) | -
[`@uiw/react-layout`](https://github.com/uiwjs/react-layout) | [![npm downloads](https://badgen.net/npm/dw/@uiw/react-layout?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/react-layout) | [![npm version](https://img.shields.io/npm/v/@uiw/react-layout.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/react-layout) | -
[`@uiw/formatter`](https://github.com/uiwjs/date-formatter) | [![npm downloads](https://badgen.net/npm/dw/@uiw/formatter?label=npm&color=dd4e4c)](https://www.npmjs.com/package/@uiw/formatter) | [![npm version](https://img.shields.io/npm/v/@uiw/formatter.svg?maxAge=3600)](https://www.npmjs.com/package/@uiw/formatter) | - 

### 开发

使用 `Gitpod`，`GitHub` 的免费在线开发环境。

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/uiwjs/uiw)

或者在本地克隆：

```bash
$ git clone git@github.com:uiwjs/uiw.git
```

安装依赖 & 编译组件代码

```bash
$ npm install # Install dependencies

$ npm run hoist
$ npm run build
```

要开发，运行自动加载编译命令：

```bash
# Run the app
# Restart the app automatically every time code changes.
# Useful during development.
$ npm run lib:watch
$ npm run start
$ lerna run --scope uiw watch --stream
$ lerna exec --scope @uiw/button -- tsbb types --outDir lib/esm --target ESNEXT --watch
$ lerna exec --scope @uiw/button -- tsbb watch --target react --env-name esm:dev --env-name cjs
```

文件夹说明：

```bash
├── LICENSE
├── README.md
├── package.json
├── website
│   ├── uiw        # Documentation website source code
└── packages
    ├── uiw        # Component library source code
    ├── react-alert
    ├── react-tree
    ├── ...
    └── react-affix
```

### 发布版本

当前工程目前通过 `git tag` 触发 [GitHub Workflow](https://github.com/uiwjs/uiw/blob/3e5ae42a7b4f6b8ea2f2c331be61048d7e5c3e9e/.github/workflows/deploy.yml#L54-L57) 自动发布到 [npm](https://www.npmjs.com/package/uiw) 包管理平台中

### Contributors

<a href="https://github.com/uiwjs/uiw/graphs/contributors">
  <img src="https://uiwjs.github.io/uiw/CONTRIBUTORS.svg" />
</a>

### License

Licensed under the MIT License.
