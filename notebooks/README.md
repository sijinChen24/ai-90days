# notebooks/ — 日常练习区

所有 `.ipynb` 放这里。这是「过程性」目录：语法练习、跟课程随手敲的实验、调 API 的小验证。

## 子目录

| 目录 | 内容 |
|---|---|
| `01-python-basics/` | Python 语法：内置类型、控制流、函数、类、文件读写 |
| `02-numpy-pandas/` | 数组与表格处理 |
| `03-llm-api/` | 调大模型 API 的小实验（流式输出、参数、异常处理） |
| `04-langchain/` | LangChain / LlamaIndex 框架练习 |
| `05-rag-agent/` | RAG 与 Agent 的实验 |

## 命名约定

`NN-主题.ipynb`，例如 `01-hello.ipynb`、`03-embedding-similarity.ipynb`。
名字要能说明内容 —— 不要留 `Untitled.ipynb`。

## 一条规矩

**探索用 notebook，交付用 .py。**

一段代码如果满足下面任一条，就该挪进 `projects/` 写成 `.py`：

- 你要反复运行它
- 别人要用它
- 它要出现在简历／作品集里

留在 notebook 里的东西，三个月后你自己都不会再看。
