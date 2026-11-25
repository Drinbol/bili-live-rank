# bili-live-rank

B站直播"在线金榜"单页查看器：浏览器直接请求接口并渲染榜单。

## 使用

浏览器打开 `rank.html` 即可。接口地址在 `makeAjaxInventoryList()` 中
（走自建代理 `bili.drinbol.com`，可改成 B站官方接口 + 自行处理跨域）。

## 说明

单文件 HTML + 原生 XMLHttpRequest，无构建。早期练手作品，存档留念。

## 许可证

MIT
