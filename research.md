---
layout: default
---

# LLM Research

I am currently a Member of Technical Staff at [Flourish Labs](). 

Previously I worked on LLM pretraining, post training, agentic search/retrieval, and evals at Databricks Research. 

Some projects while at Databricks include 
- [OfficeQA Pro: An Enterprise Benchmark for End-to-End Grounded Reasoning](https://arxiv.org/abs/2603.08655)
- [KARL: Knowledge Agents via Reinforcement Learning](https://arxiv.org/abs/2603.05218)
- [LoRA Learns Less and Forgets Less](https://arxiv.org/abs/2405.09673) (TMLR 2024, ICLR 2025) with [Dan Biderman](https://dan-biderman.netlify.app/)
- [Beyond Chinchilla-Optimal: Accounting for Inference in Language Model Scaling Laws](https://openreview.net/forum?id=0bmXrtTDUu) (ICML 2024) with Nikhil Sardana

As a Research Scientist at MosaicML, I was part of the team that pretrained and finetuned the open-source large language models [MPT-7B](https://www.mosaicml.com/blog/mpt-7b) and [MPT-30B](https://www.mosaicml.com/blog/mpt-30b) at the dawn of the ChatGPT era and [DBRX](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm) (see this fun story about how we were open weights SOTA for ~3 weeks!: [Inside the Creation of the World’s Most Powerful Open Source AI Model](https://www.wired.com/story/)) 

Back when the MosaicML NLP team consisted of only 9 researchers, we did some work on optimizing BERT pretraining. Here is our detailed [blog post](https://www.mosaicml.com/blog/mosaicbert) and report: ["MosaicBERT: A Bidirectional Encoder Optimized for Fast Pretraining"](https://openreview.net/forum?id=5zipcfLC2Z) (NeurIPS 2023). We used a lot of the insights from this work to build MPT-7B and MPT-30B. This work formed the backbone of [nomic-bert](https://www.nomic.ai/blog/posts/nomic-embed-text-v1) and [ModernBERT](https://github.com/AnswerDotAI/ModernBERT).

This [talk by Jonathan Frankle](https://www.youtube.com/watch?v=HBHeYNlNPIw) gives an overview of some of MosaicML's early days.

**Selected LLM Papers & [Technical Blog Posts](https://www.databricks.com/blog/author/jacob-portes)**

- **2026** — [OfficeQA Pro: An Enterprise Benchmark for End-to-End Grounded Reasoning](https://arxiv.org/abs/2603.08655)<br>
  Krista Opsahl-Ong, Arnav Singhvi, Jasmine Collins, Ivan Zhou, Cindy Wang, Ashutosh Baheti, Owen Oertell, **Jacob Portes**, Sam Havens, Erich Elsen, Michael Bendersky, Matei Zaharia, Xing Chen. *(arXiv preprint)*.
- **2026** — [KARL: Knowledge Agents via Reinforcement Learning](https://arxiv.org/abs/2603.05218)<br>
  Jonathan D. Chang, Andrew Drozdov, Shubham Toshniwal, Owen Oertell, Alexander Trott, **Jacob Portes**, Abhay Gupta, Pallavi Koppol, Ashutosh Baheti, Sean Kulinski, Ivan Zhou, Irene Dea, Krista Opsahl-Ong, Simon Favreau-Lessard, Sean Owen, Jose Javier Gonzalez Ortiz, Arnav Singhvi, Xabi Andrade, Cindy Wang, Kartik Sreenivasan, Sam Havens, Jialu Liu, Peyton DeNiro, Wen Sun, Michael Bendersky, Jonathan Frankle. *(arXiv preprint)*.
- **2025** — [Retrieval Capabilities of Large Language Models Scale with Pretraining FLOPs](https://arxiv.org/abs/2508.17400)<br>
  **Jacob Portes**, Connor Jennings, Erica Ji Yuen, Sasha Doubov, Michael Carbin *(NeurIPS Workshop)*.
- **2025** - [Improving Retrieval and RAG with Embedding Model Finetuning](https://www.databricks.com/blog/improving-retrieval-and-rag-embedding-model-finetuning) <br>
  **Jacob Portes**, Andrew Drozdov, Erica Ji Yuen, Vincent Chen, Sean Kulinski, Milo Cress, Colton Peltier, Sam Havens, Michael Carbin, Vitaliy Chiley and Connor Jennings
- **2024** — [Long Context RAG Performance of Large Language Models](https://arxiv.org/abs/2411.03538)<br>
  Quinn Leng\*, **Jacob Portes**\*, Sam Havens, Matei Zaharia, Michael Carbin *(NeurIPS Workshop)*.
- **2024** — [LoRA Learns Less and Forgets Less](https://arxiv.org/abs/2405.09673)<br>
  Dan Biderman, **Jacob Portes**, Jose Javier Gonzalez Ortiz, Mansheej Paul, Philip Greengard, Connor Jennings, Daniel King, Sam Havens, Vitaliy Chiley, Jonathan Frankle, Cody Blakeney, John P. Cunningham. *(TMLR)*.
- **2024** — [Introducing DBRX: A New State-of-the-Art Open LLM](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)<br>
  Mosaic Research Team.
- **2024** — [Beyond Chinchilla-Optimal: Accounting for Inference in Language Model Scaling Laws](https://arxiv.org/abs/2401.00448)<br>
  Nikhil Sardana, **Jacob Portes**, Sasha Doubov, Jonathan Frankle *(ICML)*.
- **2023** — [LIMIT: Less Is More for Instruction Tuning Across Evaluation Paradigms](https://arxiv.org/abs/2311.13133)<br>
  Aditi Jha, Sam Havens, Jeremy Dohmann, Alex Trott, **Jacob Portes**. *(NeurIPS Workshop)*.
- **2023** — [MosaicBERT: A Bidirectional Encoder Optimized for Fast Pretraining](https://proceedings.neurips.cc/paper_files/paper/2023/hash/095a6917768712b7ccc61acbeecad1d8-Abstract-Conference.html)<br>
  **Jacob Portes**\*, Alexander Trott\*, Sam Havens, Daniel King, Abhinav Venigalla, Moin Nadeem, Nikhil Sardana, Daya Khudia, Jonathan Frankle *(NeurIPS)*.
- **2023** — [MPT-30B: Raising the Bar for Open-Source Foundation Models](https://www.mosaicml.com/blog/mpt-30b)<br>
  MosaicML NLP Team.
- **2023** — [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b)<br>
  MosaicML NLP Team.
- **2022** — [Fast Benchmarking of Accuracy vs. Training Time with Cyclic Learning Rates](https://arxiv.org/abs/2206.00832)<br>
  **Jacob Portes**, Davis Blalock, Cory Stephenson, Jonathan Frankle *(NeurIPS Workshop)*.




-----



# Computational Neuroscience

**Brain Machine Interfaces and Biological Learning Rules**

During my PhD I worked on biologically plausible learning in recurrent neural networks (RNNs), reinforcement learning (RL), and motor control with [James M. Murray](https://murraylab.uoregon.edu/): ["Distinguishing Learning Rules with Brain Machine Interfaces"](https://arxiv.org/abs/2206.13448) (NeurIPS 2022).

**The Fly Connectome**

For a large part of my PhD, I worked on a project with [Rudy Behnia](http://behnialab.neuroscience.columbia.edu/), [Larry Abbott](https://zuckermaninstitute.columbia.edu/larry-f-abbott-phd) and [Jessica Kohn](http://behnialab.neuroscience.columbia.edu/people/) on the neural computation of motion in *Drosophila* eyes. Our paper ["Flexible filtering by neural inputs supports motion computation across states and stimuli"](https://www.sciencedirect.com/science/article/pii/S0960982221013178) was published in Current Biology. Here is a Current Biology "Dispatch" that summarizes this work: [Motion vision: Pinning down motion computation in an ever-changing circuit](https://www.sciencedirect.com/science/article/pii/S0960982221013567)

Our work is summarized in this research talk:

[<img class="center" src="/images/WWN_Talk2.png" alt="drawing"/>](https://www.youtube.com/watch?v=-qnnRwfesAY)

Some of my pre-PhD work in the [Hillman Lab](https://hillmanlab.zuckermaninstitute.columbia.edu/) investigated patterns of neural activation and blood flow (i.e. neurovascular coupling) in the rodent cortex.

In a previous life, I wrote a review-style [master's thesis on superconducting qubits]((/files/decoherence-superconducting-qubitsWEBv2.pdf)) for quantum computing and dabbled in philosophy of science.
