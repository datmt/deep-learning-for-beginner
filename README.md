# Introduction
I'm a developer (backend). This is the curriculum I asked Grok to create for me to familiarize with deep learning and AI in general. 

Many parts of this repo is AI generated. Use at your own risk.


The **fastest, most effective roadmap for a senior software engineer** (who already codes well) to go from **zero ML knowledge to being dangerous with modern deep learning** (including Transformers, LLMs, softmax, GELU, etc.) in **~4–8 months**, depending on how much time you can spend per week.

### Phase 0 – Mindset & Tools (1 week)
Goal: Feel comfortable running code and breaking things.

| Task                                          | Resource                                                                 |
|-----------------------------------------------|--------------------------------------------------------------------------|
| Python mastery (if rusty)                     | “Python Crash Course” (3rd ed) – only Part I                             |
| NumPy + Pandas + Matplotlib                   | “Python for Data Analysis” by Wes McKinney – chapters 4, 5, 12          |
| Jupyter notebooks & virtual environments      | Just do it                                                               |
| Install PyTorch (not TensorFlow)              | https://pytorch.org/get-started/locally/                                 |

### Phase 1 – Math for Deep Learning (3–5 weeks part-time)
You don’t need full university courses. Just the “minimum effective dose”.

| Topic                          | Best Resource (free or cheap)                                                                 | Time   |
|--------------------------------|-----------------------------------------------------------------------------------------------|--------|
| Linear algebra (vectors, matrices, eigenvalues) | 3Blue1Brown “Essence of Linear Algebra” (YouTube) + Gilbert Strang’s MIT 18.06 lectures (selectively) | 1 week |
| Probability & Statistics basics | StatQuest with Josh Starmer (YouTube) – all playlists up to “Maximum Likelihood”              | 1 week |
| Calculus (gradients, chain rule) | 3Blue1Brown “Essence of Calculus” + Khan Academy derivatives & partial derivatives            | 1 week |
| Backpropagation from scratch   | “Neural Networks: Zero to Hero” by Andrej Karpathy (YouTube, 2023–2024 series) – watch first 3 videos and code along | 1–2 weeks |

### Phase 2 – Deep Learning Foundations (6–8 weeks)
Best single sequence in 2025:

| Resource                                                                                   | Why it’s perfect for senior devs                                      | Duration |
|--------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------|
| Fast.ai Practical Deep Learning for Coders (2023 or newer course) – free                   | Top-down, code-first, uses PyTorch, modern practices from day 1   | 6–7 weeks (do Lessons 1–7) |
| Then: Deep Learning Specialization by Andrew Ng on Coursera (2024 version) – only courses 1–3 | Bottom-up theory, fills gaps fast.ai skips                        | 4 weeks part-time |
| Book (optional but excellent): “Deep Learning” by Goodfellow, Bengio, Coursera (free PDF) | Reference when you get stuck – read chapters 6–9 selectively      | Ongoing  |

By the end of Phase 2 you will:
- Train CNNs on ImageNet-level datasets
- Understand softmax, ReLU, batch norm, optimizers, etc.
- Read most PyTorch code

### Phase 3 – Modern Architectures & Transformers (6–8 weeks)
This is where you learn everything you asked about (GELU, SwiGLU, RMSNorm, attention, etc.)

| Resource                                                                                              | Notes                                                                 |
|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| “Transformers from Scratch” – Andrej Karpathy’s “Let’s build GPT” (YouTube Jan 2024)                  | Best video on the planet. Code a full nanoGPT from scratch in <300 lines |
| Stanford CS224n: Natural Language Processing with Deep Learning (2024 lectures on YouTube)            | Lectures 1–8 are gold. Watch at 1.75×                                          |
| “The Annotated Transformer” (Harvard NLP blog)                                                        | http://nlp.seas.harvard.edu/2018/04/03/attention.html – read while coding       |
| Hugging Face Transformers Course (free)                                                              | Free, hands-on, uses latest libraries                                                 |

### Phase 4 – Production & Advanced Topics (ongoing, 2–3 months+)
Now you become “job-ready” or can build serious projects.

| Topic                             | Resource                                                                 |
|-----------------------------------|--------------------------------------------------------------------------|
| Training LLMs (LoRA, QLoRA, quantization | “Efficient Fine-Tuning” course on Lightning AI (free tier)                |
| MLOps & deployment                | “Made With ML” by Goku Mohandas (free) or Full Stack Deep Learning (2024) |
| Papers you must read (in order)   | 1. Attention Is All You Need (2017)<br>2. BERT (2018)<br>3. GPT-3 (2020)<br>4. Llama 1 & 2 papers<br>5. FlashAttention-2 (2023) |

### Recommended Book Stack (buy only when you can afford
1. Deep Learning – Goodfellow et al. (the “bible”)
2. Dive into Deep Learning (d2l.ai) – interactive, free online, PyTorch version
3. Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow (3rd ed) – Aurélien Géron (excellent code walkthroughs)

### Suggested Timeline (20 hrs/week)

| Month | Milestone                                                                 |
|-------|---------------------------------------------------------------------------|
| 0–1   | Math + Python refresh                                                     |
| 1–3   | Finish fast.ai + Andrew Ng → you can train strong vision models           |
| 3–5   | Build GPT from scratch (Karpathy) + read Transformer paper                |
| 5–7   | Fine-tune Llama 3 / Mistral / Phi-3 with LoRA → build real apps (RAG, agents) |
| 7+    | Contribute to open-source repos, write blogs, apply for ML roles        |

### Bonus: One-Page Cheat Sheet of Resources (2025)

| Type       | Link                                                                              |
|------------|-----------------------------------------------------------------------------------|
| Best free course | https://course.fast.ai/                                                           |
| Best YouTube series | Andrej Karpathy – https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ |
| Best hands-on LLM | https://github.com/karpathy/nanoGPT                                               |
| Best free book   | https://d2l.ai/ (PyTorch version)                                                 |
| Best paid book   | Hands-On Machine Learning (Géron) – worth every penny                             |
