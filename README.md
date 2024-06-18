# geodata-lite

项目规则来自 https://github.com/MetaCubeX/meta-rules-dat

删除精简规则 geoip-lite.dat 与 geosite-lite.dat 的 -lite 后缀

## **geoip.dat**

国家仅包含 CN/JP,精简体积,替换一些类别

- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:cloudflare`
  - `geoip:cloudfront`
  - `geoip:facebook`
  - `geoip:bilibili`
  - `geoip:google`
  - `geoip:netflix`
  - `geoip:telegram`
  - `geoip:twitter`
  - `geoip:apple`


## **geosite.dat**

仅包含常用集合,cn 为精简集合,可能不全

集合包含 `abema / apple / applemusic / bilibili / biliintl / bahamut / cn / ehentai / google / github / microsoft / netflix / openai / onedrive / pixiv / proxy / spotify / telegram / twitter / tiktok / youtube / proxymedia`
