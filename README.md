#Awesome-Multimodal-Document-Understanding-AI-Analysis

## Top Multimodal Document Understanding & AI Analysis Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Vision-Language Document AI, OCR & Layout Parsing, Table/Formula Extraction, RAG Document Ingestion & Intelligent Document Processing (IDP)*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Multimodal Document Understanding & AI Analysis**. These tools enable AI engineers, enterprises, and researchers to parse complex PDFs, scanned invoices, multi-column scientific papers, tables, charts, and handwritten forms into structured JSON, Markdown, and grounded knowledge graphs.

**Examples** include Landing AI (Agentic Document Extraction), Scale Document AI, Google Document AI, AWS Textract, Azure AI Document Intelligence, Rossum, Hyperscience, ABBYY Vantage, Klippa DocHorizon, Veryfi OCR, and `Egonex-AI/Understand-Anything` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for open-weights Vision-Language OCR models (`MinerU`, `Docling`, `Marker`, `olmOCR`, `GOT-OCR2.0`), layout-aware document transformers, self-hosted IDP suites, and structured schema extractors — ideal for RAG pipeline architects, ML engineers, enterprise automation teams, and document AI researchers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Pricing (Starting Tier) | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- |
| **[Landing AI (Agentic Document Extraction)](https://landing.ai)** | Pay-as-you-go: $0.01/credit ($1 for 100 credits); Team plan starts at $250/month | 1,000 free credits on signup (Explore plan, valid for 90 days, no credit card required) | Visual-first multimodal document AI platform built by Andrew Ng's team, extracting structured JSON and grounded bounding-box citations from complex charts, tables, and diagrams. |
| **[Google Cloud Document AI](https://google.com)** | Pay-as-you-go: Enterprise Document OCR starts at $1.50 per 1,000 pages ($0.0015/page); Form Parser at $30.00 per 1,000 pages ($0.03/page) | 1,000 pages per month free forever for Enterprise Document OCR (plus $300 new GCP customer trial credits) | Managed enterprise document understanding platform combining layout parsing, custom entity extraction, invoice/receipt processors, and Gemini multimodal grounding. |
| **[AWS Textract](https://amazon.com)** | Pay-as-you-go: Detect Document Text starts at $0.0015/page ($1.50/1k pages); Analyze Expense at $0.01/page; Tables at $0.015/page | 3-month free trial: 1,000 pages/month for Detect Document Text, 100 pages/month for Analyze Document (Tables/Forms) and Analyze Expense | Cloud machine learning service that automatically extracts printed text, handwriting, key-value forms, and complex tables from scanned documents. |
| **[Azure AI Document Intelligence](https://microsoft.com)** | Pay-as-you-go (S0 tier): Read/OCR starts at $1.50 per 1,000 pages ($0.0015/page); Prebuilt models start at $10.00 per 1,000 pages ($0.01/page) | Free (F0) tier forever: 500 pages per month (first 2 pages per multi-page document, max 1 transaction/second) | Cloud document analysis service offering layout-to-Markdown conversion, prebuilt financial/ID models, and custom neural extraction templates. |
| **[Scale Document AI (Scale AI)](https://scale.com)** | Self-serve annotation/labeling starts at $0.05 per task/unit; Enterprise Document AI contracts typically start at ~$93,000/year | Free tier for self-labeling engine: 200 free units per month; Enterprise evaluation via sales demo/PoC (no permanent free tier for enterprise IDP) | Enterprise generative AI and human-in-the-loop document processing platform engineered for high-accuracy extraction across unstructured enterprise records. |
| **[Rossum](https://rossum.ai)** | Starter annual plan starts at $18,000/year ($1,500/month equivalent); scales with page volume commitments | 14-day free trial (full access to Rossum Aurora AI engine, document queues, and validation up to 300 trial documents; no credit card required) | Cloud-native cognitive Intelligent Document Processing (IDP) platform powered by transactional LLMs for automated invoice, purchase order, and logistics workflows. |
| **[Hyperscience](https://hyperscience.com)** | Custom enterprise annual contracts, typically starting at ~$150,000/year based on document volume and deployment model | Free proof of concept (PoC) / guided demo sandbox for prospective enterprise evaluations (no self-serve free tier or public trial) | Enterprise hyperautomation and AI document processing platform specializing in messy handwriting recognition and human-in-the-loop quality assurance. |
| **[ABBYY Vantage](https://abbyy.com)** | Metered volume-based licensing: 100k–500k pages/year rates at ~$0.04 to $0.08/page; base platform annual contracts start at ~$15,000 to $30,000/year | Guided evaluation trial tenant (14 to 30 days upon request, restricted volume quota for testing pre-trained cognitive skills; no self-serve free tier) | Low-code cloud Intelligent Document Processing suite combining industry-standard FineReader OCR with pre-trained cognitive document skills. |
| **[Klippa DocHorizon](https://klippa.com)** | Pay-as-you-go credit wallet model; modular finished products like SpendControl start at €95/month; API volume tiers vary by module | €25 in complimentary trial credits upon developer account creation for testing OCR and extraction APIs (no permanent free tier) | Cloud IDP and OCR API platform offering automated data extraction, document classification, anonymization, and fraud detection. |
| **[Veryfi OCR API](https://veryfi.com)** | Production Starter plan starts at $500/month minimum spend (~$0.08 per receipt, ~$0.16 per invoice); Growth tiers scale with volume | Free tier forever: 100 documents per month (up to 15 pages per document, full access to 100+ document APIs) + 14-day free trial for higher features | Real-time, zero-human-in-the-loop multimodal OCR API delivering sub-second structured JSON extraction for receipts, invoices, checks, and W-2s. |


## Open-Source GitHub Projects

- **[Egonex-AI/Understand-Anything](https://github.com)**  
  Open-source multimodal understanding and AI analysis framework engineered to ingest, parse, and reason over complex documents, media, and unstructured knowledge cleanly.

- **[Docling (IBM Research)](https://github.com)**  
  Premier open-source document processing toolkit parsing PDFs, DOCX, PPTX, images, and HTML with advanced layout analysis, table structure recovery (`TableFormer`), and seamless LangChain/LlamaIndex export.

- **[MinerU (OpenDataLab)](https://github.com)**  
  High-precision open-source multimodal PDF-to-Markdown and JSON extraction tool handling multi-column layouts, LaTeX mathematical formulas, tables, and OCR at scale.

- **[Marker](https://github.com)**  
  Fast, accurate open-source deep-learning pipeline converting PDFs, books, and scientific papers into clean Markdown, JSON, and HTML with equation and table extraction.

- **[Surya](https://github.com)**  
  Multilingual open-source document OCR toolkit supporting 90+ languages alongside line-level text detection, reading-order analysis, table recognition, and LaTeX OCR.

- **[olmOCR (Allen Institute for AI — Ai2)](https://github.com)**  
  Open-source Vision-Language Model (VLM) pipeline fine-tuned to linearize complex, messy PDFs (multi-column, equations, handwritten notes) into clean natural Markdown.

- **[PaddleOCR (PP-StructureV3)](https://github.com)**  
  Industry-leading open-source multilingual OCR and document layout analysis suite featuring ultra-lightweight mobile/server models, table recognition, and key-information extraction.

- **[GOT-OCR 2.0 (General OCR Theory)](https://github.com)**  
  Unified open-source end-to-end OCR 2.0 vision-language model capable of parsing plain text, molecular formulas, sheet music, geometric charts, and formatted tables.

- **[Unstructured (`unstructured-io`)](https://github.com)**  
  Widely adopted open-source ETL library for ingesting, partitioning, and cleaning dozens of unstructured document formats into LLM-ready RAG chunks.

- **[Nougat (Meta Research)](https://github.com)**  
  Pioneering open-source Visual Transformer model (`Neural Optical Understanding for Academic Documents`) converting scientific PDF pages directly into LaTeX-aware Markdown.

- **[Donut (Naver Clova AI)](https://github.com)**  
  OCR-free open-source Document Understanding Transformer (`Do`) performing end-to-end visual document classification, parsing, and VQA directly from document images.

- **[LayoutLMv3 (Microsoft Research)](https://github.com)**  
  Foundational open-source multimodal Transformer pre-trained jointly on text, visual patches, and 2D bounding-box layout positions for form and receipt understanding.

- **[ColPali / Byaldi (Vidore)](https://github.com)**  
  Breakthrough open-source Vision-Language document retrieval framework indexing raw PDF page images directly via late-interaction multi-vector embeddings without brittle OCR pipelines.

- **[Zerox](https://github.com)**  
  Lightweight open-source Node/Python OCR utility converting PDF pages into images and passing them through Vision LLMs to output clean, structured Markdown.

- **[LlamaParse / MegaParse](https://github.com)**  
  Open-source multimodal document parser engineered to preserve tables, headers, images, and layout hierarchy with zero information loss for RAG workflows.

- **[Paperless-ngx](https://github.com)**  
  Self-hosted open-source document management system featuring automated OCR indexing, ML-powered tagging, correspondent matching, and full-text search.

- **[Tesseract OCR](https://github.com)**  
  The classic, battle-tested open-source LSTM-based OCR engine supporting over 100 languages and serving as the backbone for countless document pipelines.

### Additional Strong Open-Source Options

- **[EasyOCR](https://github.com)** and **[DocTR (Mindee)](https://github.com)** for clean PyTorch/TensorFlow two-stage text detection and recognition pipelines.
- **[ExtractThinker](https://github.com)** for a flexible open-source Intelligent Document Processing (IDP) library combining document loaders with Pydantic structured LLM extraction.
- **[Kreuzberg](https://github.com)** for a high-performance, Rust-backed open-source Python library extracting text and metadata from PDFs, Office files, and images.
- **[LangExtract (Google)](https://github.com)** for open-source structured entity/field extraction with exact bounding-box and character-offset visual grounding.
- Many community **Qwen2.5-VL / SmolDocling / InternVL document fine-tunes**, **invoice/receipt schema validators (`Pydantic` + `Instructor`)**, and **MCP (Model Context Protocol) multimodal document servers**.

**Frameworks for building custom systems**: Combine **Docling** or **MinerU** (layout & table parsing), **ColPali** (visual page retrieval), **PaddleOCR / Surya** (multilingual OCR), and **ExtractThinker / LangExtract** (schema extraction) with **Egonex-AI/Understand-Anything** for an end-to-end, sovereign multimodal document intelligence stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
