# Kjarni

**Run transformer models inside your program, in any language. Same output as PyTorch, no Python, no server.**

Local AI inference as a library: one native engine for Python, C#, Go, C++, Rust and the
browser. Embeddings, classification, semantic search, reranking, chat, speech to text,
summarization, translation and CLIP image search, all on your own machine and offline once
a model has downloaded.

```bash
pip install kjarni                  # Python
dotnet add package Kjarni           # C#
go get github.com/olafurjohannsson/kjarni-go
cargo add kjarni                    # Rust
npm i kjarni-wasm                   # browser
curl -fsSL https://kjarni.ai/install.sh | sh   # CLI
```

```python
from kjarni import Embedder

print(Embedder("minilm-l6-v2").similarity("doctor", "physician"))   # 0.8598
```

## Repositories

| | |
|---|---|
| [**kjarni**](https://github.com/olafurjohannsson/kjarni) | The engine, the CLI and every language binding |
| [kjarni-examples](https://github.com/kjarni-ai/kjarni-examples) | Runnable examples in Python, C#, C++, Go, Rust, JavaScript and the CLI |
| [langchain-kjarni](https://github.com/kjarni-ai/langchain-kjarni) | Local embeddings for LangChain |
| [llama-index-embeddings-kjarni](https://github.com/kjarni-ai/llama-index-embeddings-kjarni) | Local embeddings for LlamaIndex |
| [kjarni-obsidian](https://github.com/kjarni-ai/kjarni-obsidian) | Related notes and semantic search for Obsidian, fully local |

[kjarni.ai](https://kjarni.ai) · [Docs](https://kjarni.ai/docs/) · [Blog](https://kjarni.ai/blog/) · [Try it in your browser](https://kjarni.ai/demo/)

MIT or Apache-2.0.
