**[literature-rag-eval](https://github.com/idlebranch/literature-rag-eval)** — 水处理科研文献的检索问答。270 篇论文，BGE-M3 稠密加稀疏混合检索，RRF 融合。真正花时间的是证据判断：检索不到足够证据就拒答，不许编。带引用校验和 32 条独立验收题的评测。

**[multi-agent-bi](https://github.com/idlebranch/multi-agent-bi)** — 中文业务问题转 PostgreSQL 查询。六个节点的 LangGraph 工作流，SQL 由模型写、另一个节点独立审、再过确定性校验、最后只读执行。90 条业务题加 25 条安全题的真实评测。

### 技术栈

Python、FastAPI、LangGraph、PostgreSQL、Docker、ChromaDB、BGE-M3。

