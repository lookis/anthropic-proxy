# openai-proxy

> 这是一个关于 `https://api.openai.com` 的代理服务器, 它部署在 [Vercel](https://vercel.com/).

### 步骤:

1. 准备一个自有的域名，在你的域名管理平台添加一条 CNAME 记录，像下面这样：
   | Type | Name | Value |
   | ----- | ------------ | -------------------------- |
   | CNAME | openai-proxy | cname-china.vercel-dns.com |
2. 访问 Vercel dashboard.
3. 创建一个新项目.
4. 从 Github 导入你的仓库(可以先 fork 这个仓库).
5. 部署
6. 添加绑定你自己的域名

最有就会有一个可用的 openai API 资质
`https://openai-proxy.xxx.com`

> Tips: 如果是新的域名，可能需要一个小时才能从 DNS 上解析到这个地址。
