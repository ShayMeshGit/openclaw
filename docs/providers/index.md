---
summary: "Model providers (LLMs) supported by OpenClaw"
read_when:
  - You want to choose a model provider
  - You need a quick overview of supported LLM backends
title: "Provider Directory"
---

# Model Providers

OpenClaw can use many LLM providers. Pick a provider, authenticate, then set the
default model as `provider/model`.

Looking for chat channel docs (WhatsApp/Telegram/Discord/Slack/Mattermost (plugin)/etc.)? See [Channels](../channels).

## Quick start

1. Authenticate with the provider (usually via `openclaw onboard`).
2. Set the default model:

```json5
{
  agents: { defaults: { model: { primary: "anthropic/claude-opus-4-6" } } },
}
```

## Provider docs

- [Alibaba Model Studio](./alibaba)
- [Amazon Bedrock](./bedrock)
- [Anthropic (API + Claude CLI)](./anthropic)
- [Arcee AI (Trinity models)](./arcee)
- [BytePlus (International)](../concepts/model-providers#byteplus-international)
- [Chutes](./chutes)
- [ComfyUI](./comfy)
- [Cloudflare AI Gateway](./cloudflare-ai-gateway)
- [DeepSeek](./deepseek)
- [fal](./fal)
- [Fireworks](./fireworks)
- [GitHub Copilot](./github-copilot)
- [GLM models](./glm)
- [Google (Gemini)](./google)
- [Groq (LPU inference)](./groq)
- [Hugging Face (Inference)](./huggingface)
- [inferrs (local models)](./inferrs)
- [Kilocode](./kilocode)
- [LiteLLM (unified gateway)](./litellm)
- [LM Studio (local models)](./lmstudio)
- [MiniMax](./minimax)
- [Mistral](./mistral)
- [Moonshot AI (Kimi + Kimi Coding)](./moonshot)
- [NVIDIA](./nvidia)
- [Ollama (cloud + local models)](./ollama)
- [OpenAI (API + Codex)](./openai)
- [OpenCode](./opencode)
- [OpenCode Go](./opencode-go)
- [OpenRouter](./openrouter)
- [Perplexity (web search)](./perplexity-provider)
- [Qianfan](./qianfan)
- [Qwen Cloud](./qwen)
- [Runway](./runway)
- [SGLang (local models)](./sglang)
- [StepFun](./stepfun)
- [Synthetic](./synthetic)
- [Together AI](./together)
- [Venice (Venice AI, privacy-focused)](./venice)
- [Vercel AI Gateway](./vercel-ai-gateway)
- [Vydra](./vydra)
- [vLLM (local models)](./vllm)
- [Volcengine (Doubao)](./volcengine)
- [xAI](./xai)
- [Xiaomi](./xiaomi)
- [Z.AI](./zai)

## Shared overview pages

- [Additional bundled variants](./models#additional-bundled-provider-variants) - Anthropic Vertex, Copilot Proxy, and Gemini CLI OAuth
- [Image Generation](../tools/image-generation) - Shared `image_generate` tool, provider selection, and failover
- [Music Generation](../tools/music-generation) - Shared `music_generate` tool, provider selection, and failover
- [Video Generation](../tools/video-generation) - Shared `video_generate` tool, provider selection, and failover

## Transcription providers

- [Deepgram (audio transcription)](./deepgram)

## Community tools

- [Claude Max API Proxy](./claude-max-api-proxy) - Community proxy for Claude subscription credentials (verify Anthropic policy/terms before use)

For the full provider catalog (xAI, Groq, Mistral, etc.) and advanced configuration,
see [Model providers](../concepts/model-providers).
