# Hi, I'm Murat Uyar 👋

I'm a computer science master's student at the **University of Bremen**. I build AI assistants for colleagues at work and use my research projects to explore how well language models handle unfamiliar tasks.

## At Joh. Gottfr. Schütte

Since August 2026, I've worked part-time in IT at **Joh. Gottfr. Schütte GmbH & Co. KG** in Bremen. I build internal assistants and agents in **Microsoft Copilot Studio**, turn manual processes into **Power Apps**, and automate recurring steps with **Power Automate** in the Microsoft cloud.

## Research · Can a small model learn EvoAl?

For my bachelor's thesis at the University of Bremen (July 2026), I trained **Qwen3-4B** to turn natural-language requests into EvoAl code. I built 7,500 training examples from the language grammars and sample files, then fine-tuned the model with LoRA on an RTX 4060 with 8 GB of VRAM.

A correction to the training data raised the number of generated files accepted by the EvoAl parser from **36/50 to 44/50 (88%)**. All three end-to-end workflow tests still failed. In two cases, the model reproduced training examples instead of following the request. That finding changed how I evaluate code generation: I test whether the output runs and whether it actually does what the user asked.

## Selected projects

| Project | What I built |
| --- | --- |
| [Parliamentary Protocol AI](https://github.com/uyar1/parliamentary-protocol-ai) | A FastAPI backend for transcribing and summarizing Bremen Parliament sessions. WhisperX transcribes the audio, and a multi-stage pipeline groups and summarizes the discussion by topic. |
| [Document Q&A](https://github.com/uyar1/document-qa-rag) | A PDF question-answering app. It retrieves relevant passages with ChromaDB and passes them to Claude to generate an answer. Built with FastAPI and Docker, deployed on AWS. |

I also spent an Erasmus+ semester at **Boğaziçi University** in Istanbul, studying computer science and operations research.
