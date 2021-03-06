# Alfred Web Search Suggest
Alfred search suggest workflow for various popular websites. Inspired by the official Google Suggest workflow.

[**DOWNLOAD**](https://github.com/AkikoZ/alfred-web-search-suggest/releases)

## Supported Websites
* [Google](#google)
* [Wikipedia](#wikipedia)
* [Wolfram|Alpha](#wolframalpha)
* [Baidu (百度)](#baidu)
* [Zhihu (知乎)](#zhihu)
* [bilibili (哔哩哔哩)](#bilibili)
* [Sina Weibo (新浪微博)](#sina-weibo)
* [Taobao (淘宝)](#taobao)

## Details

### Google
Support basic suggestions. Proxy settings are available in the workflow environmant variables.

![google](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/google.png)

### Wikipedia
Support direct term suggestions and preview, language can be specified in the first arg. Proxy settings are available in the workflow environmant variables.

![wikipedia-en](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/wikipedia-en.png)

![wikipedia-zh](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/wikipedia-zh.png)

### Wolfram|Alpha
Support direct term suggestions. Proxy settings are available in the workflow environmant variables.

![wolframalpha](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/wolframalpha.png)

### Baidu
Support basic suggestions.

![baidu](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/baidu.png)

### Zhihu
Support direct term suggestions and preview.

![zhihu](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/zhihu.png)

### bilibili
Support basic suggestions.

![bilibili](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/bilibili.png)

### Sina Weibo
Support basic suggestions.

![sinaweibo](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/sinaweibo.png)

### Taobao
Support basic suggestions.

![taobao](https://github.com/AkikoZ/alfred-web-search-suggest/blob/master/screenshots/taobao.png)

## Additional Notes

### Direct Search
If you want an alternative to search exactly what you typed, you can add custom web searches in `Features → Web Search` of Alfred Preferences, here's a list of the search URLs above:
* Google: `built-in`
* Wikipedia: `built-in`
* Wolfram|Alpha: `built-in`
* Baidu: `https://www.baidu.com/s?wd={query}`
* Zhihu: `https://www.zhihu.com/search?q={query}`
* bilibili: `https://search.bilibili.com/all?keyword={query}`
* Sina Weibo: `http://s.weibo.com/weibo/{query}`
* Taobao: `https://s.taobao.com/search?q={query}`

### Proxy Settings
Proxy settings are avaliable in the workflow environmant variables, here's an example setting:
```
proxy_address: 127.0.0.1
proxy_port: 1087
proxy_type: CURLPROXY_HTTP // or CURLPROXY_SOCKS5 if you use a Socks5 proxy
```
