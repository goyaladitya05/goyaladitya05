<h1 align="center">Aditya Goyal</h1>
<p align="center">Working on ML infrastructure and developer tooling </p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenVINO-00C7FD?style=flat-square&logo=intel&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

<br>

## Open Source Contributions

### Google Summer of Code 26' Contributor - Intel OpenVINO
Extending the LTX text-to-video pipeline with image-to-video generation, enabling video synthesis conditioned on an input image and text prompt. Implementing full C++ and Python API support, throughput/latency benchmarking, and a test suite ensuring consistency across both implementations.

### Keras 3 - [keras-team/keras](https://github.com/keras-team/keras)
Working on bringing the OpenVINO backend for Keras 3 to functional parity with the other backends — implementing operators that were missing for OpenVINO, cutting down excluded tests along the way, and now extending the same work to `keras-hub`. Also reported a handful of upstream bugs in OpenVINO found while doing this.

### OpenVINO Toolkit - [openvinotoolkit/openvino.genai](https://github.com/openvinotoolkit)
Added LoRA adapter support for GGUF-format models, extending what was previously safetensors-only, and brought LoRA support to the Text2Video (LTX-Video) pipeline, including fixes for adapter persistence across model reshapes and a Python API for setting adapter. Also added per-stage latency metrics for the LLM and Whisper pipelines, and fixed a missing opset re-export bug.

<br>

## Projects

### CanIRunIt
A web tool that checks whether a given HuggingFace model will fit on your hardware — estimating storage and VRAM across quantization formats (FP32, FP16, INT4, GGUF, and others) and checking compatibility against consumer GPUs, cloud instances, and Apple Silicon before you download anything.

### RAG-Based LLM Query–Retrieval System
`FastAPI` · `PyTorch` · `FAISS` · `LangChain`
A retrieval-augmented generation system for querying documents — semantic search via FAISS, context-aware answers via LLMs, and some work on making it fast (async + batching) and reliable under load.

<br>

## Contact

<p align="left">
  <a href="https://github.com/goyaladitya05">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>
