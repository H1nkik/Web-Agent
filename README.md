# Web-Agent

![Static Badge](https://img.shields.io/badge/Code-Python-8A2BE2)

- Dpendency (For the SeeAct)

Before installing seeact, please make sure you've installed playwright.

On linux, please: playwright install & playwright install-deps 

```bash
conda create -n seeact python=3.11

conda activate seeact

pip install seeact

pip install jsonlines

pip install aioconsole

pip install lxml

pip install bs4

pip install datasets

pip install Pillow

pip install transformers

pip install torch
```

- Dpendency (For the Webvoyager)

make sure that "openai" and "httpx" are compatible

```bash
conda create -n webvoyager python=3.10

conda activate webvoyager

pip install -r requirements.txt (WebVpyager's)


- Benchmark

  [Multimodal-Mind2Web](https://github.com/OSU-NLP-Group/Mind2Web)

  [Lexical Semantic Comprehension Benchmark](https://github.com/jinyangwu/LeSC/tree/main)
