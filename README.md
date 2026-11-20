# Hi, I'm Viraj Panchal

**AI/ML Engineer** building production computer vision, multimodal AI and LLM systems.

I work at Vartit Technology on a content-safety classification platform that serves 4 client products and has processed **720M+ images and 3B+ text messages**.

## What I work on

- **Computer vision**: trained the production EVA-02 Vision Transformer classifier (93.35% F1, 95.57% recall across 6 harm categories), chosen over DINOv2 and EfficientNet in head-to-head tests
- **Multimodal pipelines**: image classification + object detection + OCR + LLM reasoning in one flow
- **LLMs**: LoRA fine-tuning of SmolLM2 (and contributed to Qwen fine-tuning), helped set up a self-hosted Qwen 27B with vLLM, Pydantic-validated JSON outputs
- **Synthetic data**: 24,000+ training images generated with FLUX, Qwen-Image and SDXL
- **Production**: ONNX / TFLite / GGUF on-device models, FastAPI + Docker, Prometheus + Grafana monitoring (about 1,000 images/min at about 90 ms model latency)

## Research

**First author**: *KidsNanny: A Two-Stage Multimodal Content Moderation Pipeline Integrating Visual Classification, Object Detection, OCR, and Contextual Reasoning for Child Safety*, [arXiv:2603.16181](https://arxiv.org/abs/2603.16181) (2026)

86.16% F1 at 120 ms per image, more accurate and 9–34x faster than ShieldGemma-2 and LlavaGuard.

## Tech stack

- **ML / DL:** Python · PyTorch · Hugging Face (Transformers, PEFT, TRL) · TensorFlow
- **Vision:** EVA-02 · DINOv2 · YOLO · D-FINE · RF-DETR · CLIP · PaddleOCR · OpenCV
- **LLMs:** vLLM · Qwen · LLaVA · LoRA / SFT · RAG · Pydantic structured outputs
- **Deployment:** FastAPI · Docker · ONNX · TensorFlow Lite · NCNN · GGUF · Prometheus · Grafana · AWS · Qdrant

## Certifications

- AWS Certified Machine Learning Engineer – Associate
- AWS Certified Solutions Architect – Associate

My production work at Vartit is proprietary and is not published here.

[LinkedIn](https://linkedin.com/in/panchalviraj) · [arXiv paper](https://arxiv.org/abs/2603.16181)
