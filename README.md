# Hi, I'm Mitja Leb 👋

**AI engineer** who likes understanding models from the inside out: I build
transformers, tokenizers and training pipelines from scratch, run controlled
experiments to find out what actually matters, and turn LLMs into reliable
applications with verifiers, guardrails and evals.

My projects follow the questions behind recent progress in AI: how to pick
architectures and hyperparameters on small models that still hold at scale
(µP, mixture of experts, scaling laws), how to make model output checkable
(verifiers, execution feedback, fact-checking before answering), and how
models can learn from their own verified outputs.

- 🔭 Currently working on: verifier-guided code generation for C (SEGVibe) and scaling experiments (tinyformer)
- 🌱 Learning: RL from verifiable rewards, LLM evaluation, efficient training and inference
- 📫 Reach me: [LinkedIn](https://www.linkedin.com/in/mlsween/)

## Featured projects

| Project | What it is | Highlights |
|---|---|---|
| [**tinyformer**](https://github.com/sweeney-007/tinyformer) | A transformer and byte-level BPE tokenizer from scratch (Python + raw PyTorch), plus µP and mixture-of-experts scaling experiments on cloud GPUs | BPE beats character tokens by 31% in bits per character; under µP the best learning rate stays put across an 8× width range; MoE beats dense at every width per FLOP but not per GPU-second. |
| [**SEGVibe**](https://github.com/sweeney-007/SEGVibe) | A code LLM writes C; sanitizers, fuzzing, static analysis and profiling check it; findings go back for repair | The checks catch 93% of 95 seeded defects with 0 false positives; 12 defects are caught only by a layer other than the tests. Includes a LangGraph repair agent and retrieval of CWE fix guidance. |
| [**filings-analyst**](https://github.com/sweeney-007/filings-analyst) | LLM agent that answers questions about company annual reports (SEC 10-K) with citations, built with LangGraph | Hybrid RAG with corrective retrieval, tool calling, fact-check step, typed error handling. 93% hit@5 retrieval on 300 questions. |

## Tech I use

`Python` · `PyTorch` · `C` · `Hugging Face` · `vLLM` · `LangChain` · `LangGraph` · `FastAPI` · `Docker` · `Modal` · `Clang sanitizers` · `Git` · `Linux`
