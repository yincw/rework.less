# rework.less

> 一种面向浏览器用户代理样式（user agent stylesheet）兼容的解决方案

## 特色

- 支持 [Less](http://lesscss.org/)，使你更出色。
- 从 User Agent Style Sheets 视角出发，让你更懂 CSS。
- 集成了常用 CSS 工具集，使用更舒心。
- 全面的浏览器支持，基于 [autoprefixer](https://github.com/postcss/autoprefixer) 开发，可使用 [clean-css](https://github.com/jakubpawlowicz/clean-css#how-to-set-a-compatibility-mode)，让你的 CSS 更灵活。

## 安装

```less
npm install --save rework.less
```

## 使用

```less
@import "/rework.less/rework.less";
```

## 浏览器支持

IE(Trident) | Firefox(Gecko) | Chrome/Opera(Blink) | Safari/Edge(WebKit)
---|---|---|---
6+ | Latest | Latest| Latest

注意：集成 CSS 工具具体兼容性查阅具体模块内部说明。
