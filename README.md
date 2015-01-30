# search-engine-bot-list
A list of all common search engine bots's User Agent strings, matched by regular expression:

**Search engines:**
```js
{
  google: /Googlebot/i,
  yahoo: /Yahoo!\s+Slurp|YahooSeeker/i,
  bing: /Bingbot/i,
  facebook: /facebookexternalhit/i,
  alexa: /ia_archiver/i,
  twitter: /Twitterbot/i,
  yandex: /YandexBot/i,
  duckduckgo: /DuckDuckBot/i,
  entireweb: /Speedy Spider/i,
  msn: /msnbot/i,
  baidu: /Baiduspider/i,
  360: /360(Spider|User-agent)/i,
  sogou: /Sogou(\s|spider)|/i,
  soso: /Soso[ a-z\-]*?spider/i,
  youdao: /YodaoBot/i,
  iask: /iaskspider/i,
  unknown: /robot|crawler|spider|[a-z]bot(\s|$)/i
}
```

**Feed aggregators:**
```js
{
  feedburner: /FeedBurner/i,
  feedly: /Feedly/i,
  xfruits: /xFruits/i,
  feedsky: /Feedsky crawler/i,
  youdaofeed: /YoudaoFeedFetcher/i,
  xianguo: /Xianguo\.com/i,
  simplepie: /SimplePie/i
}
```

**Tools:**
```js
{
  curl: /curl\//,
  wget: /Wget\//,
  drupal: /Drupal/,
  pycurl: /PycURL/,
  httrack: /HTTrack/
  
}
```
