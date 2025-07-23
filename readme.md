🧠 GPT from Scratch — Transformer Language Model
This project implements a Generatively Pretrained Transformer (GPT) from scratch, inspired by the seminal paper “Attention is All You Need” and OpenAI’s GPT-2/GPT-3 architecture.

It is a minimal, educational codebase that walks through the foundational ideas behind autoregressive language models and transformer architectures, focusing on clarity and full visibility into what happens under the hood.

🚀 What’s Inside
✅ Tokenization and dataset preparation (Tiny Shakespeare)

✅ Bigram language model as a baseline

✅ Self-attention mechanism implemented from first principles

✅ Positional encoding

✅ Multi-head self-attention

✅ Transformer blocks: feedforward, residuals, normalization

✅ Training loop using PyTorch

✅ Scaling and model regularization (dropout, layer norm)

✅ Discussion on architectural tradeoffs and pretraining vs. fine-tuning

.
├── manage-1.ipynb            # Entry point: training loop
├── test.py            # Transformer architecture
├── data.py             # Dataset preprocessing and loader
├── config.py           # Model and training hyperparameters
├── utils.py            # Helper functions
└── README.md           # You're here


🙏 Acknowledgements
This project is heavily inspired by the works of Andrej Karpathy and the open-source AI community. It is built as a self-contained educational resource to deepen understanding of how modern LLMs work.

🔗 Key References
Attention is All You Need (Vaswani et al.)

GPT-3: Language Models are Few-Shot Learners (Brown et al.)

OpenAI ChatGPT Blog Post

nanoGPT — A scalable and modernized implementation

Lambda Labs — For cloud GPU compute used in training