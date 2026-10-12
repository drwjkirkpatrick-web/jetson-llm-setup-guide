# A Field Guide to 3B-Class LLMs on the Jetson Orin Nano 8 GB

**Tags:** `jetson` `nvidia-jetson` `llm` `llama.cpp` `setup-guide` `edge-ai` `aarch64` `tutorial` `latex`

A practical field guide to running 3B-class LLMs on the Jetson Orin Nano 8 GB — **setup, flags, benchmark suite, and everything we learned along the way**.

Written from live experiments on the device: server launch recipes (foreground/setsid discipline, `ngl`, batch/ubatch, flash-attention, Jinja templates), KV-cache sizing math that keeps a resident agent + gateway inside 8 GB, context-window feasibility at 64K, speculative decoding (MTP/DSpark), and the honest failure modes (OOM interactions with Chromium, background-wrapper kills, keepalive self-healing).

## Contents

- `Jetson_3B_LLM_Guide.tex` — LaTeX source
- `Jetson_3B_LLM_Guide.pdf` — compiled guide (read this one)

Rebuild the PDF with your preferred LaTeX toolchain (`pdflatex` or `latexmk`).