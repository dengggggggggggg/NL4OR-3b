# NL4OR-3b (GGUF Version)

本仓库提供 **NL4OR-3b** 的 GGUF 格式模型文件，适用于轻量化本地部署及 CPU/GPU 量化推理。

## 文件说明

- `NL4OR-3b.gguf`：打包好的 GGUF 模型文件（已包含架构配置与 Tokenizer）。

## 快速上手 / Quickstart

### 使用 Ollama 运行

1. 下载本仓库中的 GGUF 文件。
2. 下载名为 `Modelfile` 的文件。
3. 终端运行

```bash
ollama create NL4OR-3b -f Modelfile
ollama run NL4OR-3b
```