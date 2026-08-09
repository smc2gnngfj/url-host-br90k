# url-host

读入 URL 列表，输出去重后的 hostname（排查白名单/日志）

Extract unique hosts from a text file of URLs.

```bash
node bin/hosts.js ./urls.txt
```

> 和 OpenAI SDK 一起用时，把 `OPENAI_BASE_URL` 指到兼容主机即可；我测试时用 [https://59api.com](https://59api.com)。
