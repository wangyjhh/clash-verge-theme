<h1 align="center">
  <a href="https://github.com/clash-verge-rev/clash-verge-rev">Clash Verge Rev</a> Black Theme
  <br>
</h1>

<br>
<div align="center">
    <img src="src/preview/clash-proxies.png" alt="代理" width="24%" />
    <img src="src/preview/clash-profiles.jpg" alt="订阅" width="24%" />
    <img src="src/preview/clash-connections.jpg" alt="连接" width="24%" />
    <img src="src/preview/clash-rules.png" alt="规则" width="24%" />
</div>
<div align="center">
    <img src="src/preview/clash-logs.png" alt="日志" width="25%" />
    <img src="src/preview/clash-test.png" alt="测试" width="25%" />
    <img src="src/preview/clash-settings.png" alt="设置" width="25%" />
</div>

## 图标

| 设置项             | 值                                                                   |
| ------------------ | -------------------------------------------------------------------- |
| 常规托盘图标：     | <img width="48px" src="./src/resource/common_tray_icon.png" />       |
| 系统代理托盘图标： | <img width="48px" src="./src/resource/system_prosy_tray_icon.png" /> |
| Tun 模式托盘图标： | <img width="48px" src="./src/resource/tun_tray_icon.png" />          |

## 主题设置

| 设置项         | 值                                                         |
| -------------- | ---------------------------------------------------------- |
| 主要颜色：     | ![#3aa675](/src/resource/primary_color.svg) #3aa675        |
| 次要颜色：     | ![#a67654](/src/resource/secondary_color.svg) #a67654      |
| 文本主要颜色： | ![#dbd7ca](/src/resource/primary_text_color.svg) #dbd7ca   |
| 文本次要颜色： | ![#a6a6a6](/src/resource/secondary_text_color.svg) #a6a6a6 |
| 信息颜色：     | ![#84c6ff](/src/resource/info_color.svg) #84c6ff           |
| 警告颜色：     | ![#ffb682](/src/resource/warning_color.svg) #ffb682        |
| 错误颜色：     | ![#ff9494](/src/resource/error_color.svg) #ff9494          |
| 成功颜色：     | ![#59ffb4](/src/resource/success_color.svg) #59ffb4        |
| 字体系列：     | [JetBrains Mono](https://www.jetbrains.com/lp/mono/)       |

## CSS 注入

```css
/* 主界面 */

.layout__left,
.layout__right {
    background-color: #303030 !important;
}

/* logo */

.the-logo svg,
.the-logo svg path {
    fill: var(--primary-main) !important;
}

/* 代理 */

.MuiButtonBase-root.MuiListItemButton-root.MuiListItemButton-dense.MuiListItemButton-gutters.MuiListItemButton-root.MuiListItemButton-dense.MuiListItemButton-gutters {
    background-color: #303030 !important;
}

.MuiButtonBase-root.MuiListItemButton-root.MuiListItemButton-dense.MuiListItemButton-gutters.MuiListItemButton-root.MuiListItemButton-dense.MuiListItemButton-gutters:hover {
    background-color: #404040 !important;
}

/* 订阅 */

.MuiGrid2-root.MuiGrid2-direction-xs-row.MuiGrid2-grid-xs-12.MuiGrid2-grid-sm-6.MuiGrid2-grid-md-4.MuiGrid2-grid-lg-3 > .MuiBox-root > .MuiBox-root,
.MuiGrid2-root.MuiGrid2-direction-xs-row.MuiGrid2-grid-xs-12.MuiGrid2-grid-sm-6.MuiGrid2-grid-md-6.MuiGrid2-grid-lg-6 > .MuiBox-root {
    background-color: #303030 !important;
}

.base-content > .MuiBox-root:nth-child(2):has(> .MuiBox-root) {
    background-color: #252525 !important;
}

/* 连接 */
.MuiDataGrid-virtualScroller.MuiDataGrid-virtualScroller--hasScrollX,
.MuiDataGrid-columnHeader,
.MuiDataGrid-cell {
    background-color: #303030 !important;
}

/* 规则 */

.base-content > .MuiBox-root:nth-child(2) {
    background-color: #303030 !important;
}

/* 日志 */

/* 测试 */

.MuiGrid2-root.MuiGrid2-direction-xs-row.MuiGrid2-grid-xs-6.MuiGrid2-grid-lg-2.MuiGrid2-grid-sm-4.MuiGrid2-grid-md-3 > .MuiBox-root > .MuiBox-root {
    background-color: #303030 !important;
}

/* 设置 */

section {
    background-color: #252525 !important;
}

.MuiPaper-root.MuiPaper-elevation.MuiPaper-rounded.MuiPaper-elevation2,
.MuiPaper-root.MuiPaper-elevation.MuiPaper-rounded.MuiPaper-elevation1.MuiTableContainer-root,
.MuiGrid-root.MuiGrid-item.MuiGrid-grid-xs-12.MuiGrid-grid-md-6 > .MuiBox-root {
    background-color: #303030 !important;
}

/* 弹窗 */

.MuiPaper-root.MuiPaper-elevation.MuiPaper-elevation6.MuiSnackbarContent-root {
    color: #dbd7ca !important;
    background-color: #303030 !important;
}

.MuiPaper-root.MuiPaper-elevation.MuiPaper-rounded.MuiPaper-elevation24.MuiDialog-paper.MuiDialog-paperScrollPaper.MuiDialog-paperWidthXl.MuiDialog-paperFullWidth,
.MuiPaper-root.MuiPaper-elevation.MuiPaper-rounded.MuiPaper-elevation24.MuiDialog-paper.MuiDialog-paperScrollPaper.MuiDialog-paperWidthSm {
    background-color: #303030 !important;
}

/* 右击菜单 */
.MuiPaper-root.MuiPaper-elevation.MuiPaper-rounded.MuiPaper-elevation8.MuiPopover-paper.MuiMenu-paper.MuiMenu-paper {
    background-color: #303030 !important;
}
```
