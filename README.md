# openai-proxy

> This is a proxy server regarding to `https://api.openai.com`, and it's deployed on [Vercel](https://vercel.com/).

### Steps:

1. Setup your own domain and add a CNAME record like below on your domain management system.
   | Type | Name | Value |
   | ----- | ------------ | -------------------------- |
   | CNAME | openai-proxy | cname-china.vercel-dns.com |
2. Goto Vercel dashboard.
3. Create a new Project.
4. Import your repository(fork this repository) from Github.
5. Deploy
6. Add your custom domain.

Finally you'll have an available API address like
`https://openai-proxy.xxx.com`

> Tips: It may take about 1 hour until your new record works.
