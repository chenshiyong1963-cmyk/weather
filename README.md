# weather

世界天气时钟：在网页上输入或选择世界上的任意城市，显示：

- 当地时区（IANA 名称 + UTC 偏移，以及与你所在时区的时差）
- 当地时间（实时走秒）
- 当地天气（当前温度、体感、湿度、风速，以及未来 5 天预报）

## 使用

纯静态单页面，无需构建、无需 API Key。直接用浏览器打开 `index.html` 即可。

### 发布到 GitHub Pages

仓库 Settings → Pages → Source 选 `Deploy from a branch`，Branch 选 `main` / `(root)`，保存。
几分钟后访问：https://chenshiyong1963-cmyk.github.io/weather/

## 数据来源

- 城市搜索：[Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
- 天气：[Open-Meteo Forecast API](https://open-meteo.com/en/docs)
- 当地时间：浏览器内置 `Intl.DateTimeFormat`
