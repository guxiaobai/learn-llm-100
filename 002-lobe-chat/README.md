# Lobe Chat


|本期版本|上期版本
|:---:|:---:
`Sat Feb  8 12:34:22 CST 2025` | -

```bash
docker pull lobehub/lobe-chat
docker pull postgres:16
```

```bash
# docker run -itd  --name=lobechat -p 3210:3210 -e OLLAMA_PROXY_URL=http://host.docker.internal:11434/v1 lobehub/lobe-chat
docker run -d -p 3210:3210 -e OLLAMA_PROXY_URL=http://host.docker.internal:11434 lobehub/lobe-chat
```

<https://127.0.0.1:3210>

## Ref



* <https://github.com/lobehub/lobe-chat>