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

Looking for chat channel docs (WhatsApp/Telegram/Discord/Slack/Mattermost (plugin)/etc.)? See [Channels](/docs/channels).

## Quick start

1. Authenticate with the provider (usually via `openclaw onboard`).
2. Set the default model:

```json5
{
  agents: { defaults: { model: { primary: "anthropic/claude-opus-4-6" } } },
}
```

## Provider docs

- [Alibaba Model Studio](/docs/providers/alibaba)
- [Amazon Bedrock](/docs/providers/bedrock)
- [Anthropic (API + Claude CLI)](/docs/providers/anthropic)
- [Arcee AI (Trinity models)](/docs/providers/arcee)
- [BytePlus (International)](/docs/concepts/model-providers#byteplus-international)
- [Chutes](/docs/providers/chutes)
- [ComfyUI](/docs/providers/comfy)
- [Cloudflare AI Gateway](/docs/providers/cloudflare-ai-gateway)
- [DeepSeek](/docs/providers/deepseek)
- [fal](/docs/providers/fal)
- [Fireworks](/docs/providers/fireworks)
- [GitHub Copilot](/docs/providers/github-copilot)
- [GLM models](/docs/providers/glm)
- [Google (Gemini)](/docs/providers/google)
- [Groq (LPU inference)](/docs/providers/groq)
- [Hugging Face (Inference)](/docs/providers/huggingface)
- [inferrs (local models)](/docs/providers/inferrs)
- [Kilocode](/docs/providers/kilocode)
- [LiteLLM (unified gateway)](/docs/providers/litellm)
- [LM Studio (local models)](/docs/providers/lmstudio)
- [MiniMax](/docs/providers/minimax)
- [Mistral](/docs/providers/mistral)
- [Moonshot AI (Kimi + Kimi Coding)](/docs/providers/moonshot)
- [NVIDIA](/docs/providers/nvidia)
- [Ollama (cloud + local models)](/docs/providers/ollama)
- [OpenAI (API + Codex)](/docs/providers/openai)
- [OpenCode](/docs/providers/opencode)
- [OpenCode Go](/docs/providers/opencode-go)
- [OpenRouter](/docs/providers/openrouter)
- [Perplexity (web search)](/docs/providers/perplexity-provider)
- [Qianfan](/docs/providers/qianfan)
- [Qwen Cloud](/docs/providers/qwen)
- [Runway](/docs/providers/runway)
- [SGLang (local models)](/docs/providers/sglang)
- [StepFun](/docs/providers/stepfun)
- [Synthetic](/docs/providers/synthetic)
- [Together AI](/docs/providers/together)
- [Venice (Venice AI, privacy-focused)](/docs/providers/venice)
- [Vercel AI Gateway](/docs/providers/vercel-ai-gateway)
- [Vydra](/docs/providers/vydra)
- [vLLM (local models)](/docs/providers/vllm)
- [Volcengine (Doubao)](/docs/providers/volcengine)
- [xAI](/docs/providers/xai)
- [Xiaomi](/docs/providers/xiaomi)
- [Z.AI](/docs/providers/zai)

## Shared overview pages

- [Additional bundled variants](/docs/providers/models#additional-bundled-provider-variants) - Anthropic Vertex, Copilot Proxy, and Gemini CLI OAuth
- [Image Generation](/docs/tools/image-generation) - Shared `image_generate` tool, provider selection, and failover
- [Music Generation](/docs/tools/music-generation) - Shared `music_generate` tool, provider selection, and failover
- [Video Generation](/docs/tools/video-generation) - Shared `video_generate` tool, provider selection, and failover

## Transcription providers

- [Deepgram (audio transcription)](/docs/providers/deepgram)

## Community tools

- [Claude Max API Proxy](/docs/providers/claude-max-api-proxy) - Community proxy for Claude subscription credentials (verify Anthropic policy/terms before use)

For the full provider catalog (xAI, Groq, Mistral, etc.) and advanced configuration,
see [Model providers](/docs/concepts/model-providers).
