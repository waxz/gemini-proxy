# Gemini API 的cloudflare worker 代理

使用cloudflare worker 将Gemini 2.0 免费的原生多模态API代理到国内<br>

## 使用方法

在cloudflare创建一个worker，
将 [`worker.js`](worker.js)内容拷贝到worker
再绑定一个自定义域名即可

## cloudflare Connect to Github

```bash
npm i wrangler --save-dev

npx wrangler dev --port 8888

```

## call api

```bash
curl https://your-server/v1beta/models/gemini-pro?key=$API_KEY
```

## 作者
- https://github.com/CattleZoe/Gemini-proxy
- https://github.com/tech-shrimp/gemini-proxy
- Gemini
