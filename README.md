# NL4OR-3b (GGUF Version)

本仓库提供 **NL4OR-3b** 的 GGUF 格式模型文件，适用于轻量化本地部署及 CPU/GPU 量化推理。

## 文件说明

- `Modelfile`：用于 Ollama 的模型配置文件，指导 Ollama 如何加载、打包和运行指定的模型文件（如 .gguf），并定义模型的默认行为、 Prompt 模板和超参数。

## 快速上手 / Quickstart

### 使用 Ollama 运行

1. 在[https://huggingface.co/DinGrogu/qwen2.5-3b-nl4opt] 下载`NL4OR-3b` 模型文件。
2. 下载名为 `Modelfile` 的文件。
3. 终端运行

```bash
ollama create NL4OR-3b -f Modelfile
ollama run NL4OR-3b
```