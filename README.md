# Relay4AI — One API for Leading AI Models

> OpenAI-compatible multi-model API proxy. 12+ models, one endpoint.

[![Website](https://img.shields.io/badge/Website-relay4ai.cloud-00d4ff)](https://relay4ai.cloud)
[![Twitter](https://img.shields.io/badge/Twitter-@relay4ai-1DA1F2)](https://x.com/relay4ai)

## Supported Models

| Provider | Models |
|----------|--------|
| OpenAI | GPT-4o, GPT-4o-mini |
| Anthropic | Claude Opus 4.7, Claude Sonnet 4.6 |
| Google | Gemini 2.5 Pro, Gemini 2.5 Flash |
| DeepSeek | V3.2, V4-Flash |
| Qwen | Qwen3.5-122B |
| Moonshot | Kimi K2.6 |
| Zhipu | GLM-5 |

## Quick Start

```bash
curl https://relay4ai.cloud/v1/chat/completions \
  -H Authorization: Bearer YOUR_API_KEY \
  -H Content-Type: application/json \
  -d '{model:gpt-4o-mini,messages:[{role:user,content:Hello!}]}'
```

## Features

- One API key for 12+ models
- OpenAI SDK compatible (change base URL only)
- Stream-first billing with automatic reconciliation
- Real-time usage dashboard
- Monthly plans from $9/month
- Free trial credits for new accounts
- USDT pay-as-you-go

## 🎨 AI Photo Curator (NEW)

Upload a photo and AI turns it into anime / comic / movie poster style.

- 3 art styles: Anime, Comic, Cinematic Poster
- Powered by StepFun image-to-image model
- 50 credits per generation
- Monthly plan users get free generations
- Try it: [relay4ai.cloud/curator](https://relay4ai.cloud/curator)

## Links

- Website: [relay4ai.cloud](https://relay4ai.cloud)
- Docs: [relay4ai.cloud/docs](https://relay4ai.cloud/docs)
- Pricing: [relay4ai.cloud/pricing](https://relay4ai.cloud/pricing)
- Twitter: [@relay4ai](https://x.com/relay4ai)
- Contact: Zzz666882@163.com

