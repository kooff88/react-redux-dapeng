# Zooming (d3-zoom)

变焦

```js
let svg = d3.select("body")
		.append("svg")
		.attr("width", "100%")
		.attr("height", "100%")
		.call(d3.zoom().on("zoom",(e) => {
			return svg.attr("transform", e.transform)
		}))

```

`zoom.scaleExtent` : 设置一个映射范围。

`zoom.translateExtend`: 设置 转换的 总范围。

`zoom.extent`: 设置 可视范围一个值。