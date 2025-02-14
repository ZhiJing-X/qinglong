# qinglong

### 拉库

## BiliBili-Tool
## 项目地址
```bash
https://github.com/RayWangQvQ/BiliBiliToolPro
```

## 拉库地址
```bash
https://github.com/RayWangQvQ/BiliBiliToolPro.git
```

### 拉取脚本后缀

```bash
js mjs py pyc sh ts
```

### NodeJs依赖

```bash
axios
crypto-js
cheerio
prettytable
dotenv
jsdom
date-fns
MD5@1.3.0
md5@2.x
canvas
request
tough-cookie
tslib
ws@7.4.3
ts-md5
jsrsasign
jsencrypt
jieba
fs
form-data
json5
global-agent
png-js
@types/node
require
typescript
js-base64
moment
node-jsencrypt
node-rsa
node-fetch
qs
ds
yml2213-utils
sm-crypto
node-telegram-bot-api
ql
```

### Python3依赖

```bash
bs4
rsa
requests
canvas
ping3
jieba
PyExecJS
aiohttp
redis
pycryptodome
httpx
```

### Linux依赖

```bash
--no-cache
build-base
g++
cairo-dev
pango-dev
giflib-dev
```

### BiliBili-Tool
1.打开青龙编辑 extra.sh 文件，添加如下指令：
```bash
# 安装dotnet环境
curl -sSL https://raw.githubusercontent.com/RayWangQvQ/BiliBiliToolPro/main/qinglong/ray-dotnet-install.sh | bash /dev/stdin --no-official
```

2.重启青龙容器
```bash
docker exec -it qinglong bash /ql/data/config/extra.sh
```
