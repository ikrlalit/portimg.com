<div align="center">

<img src="https://portimg.com/favicon.ico" alt="PortImg Logo" width="80" height="80" />

# PortImg

### All-in-One Online Image & PDF Toolkit

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fportimg.com&label=portimg.com&style=flat-square&color=4f46e5)](https://portimg.com)
[![Tools](https://img.shields.io/badge/Tools-100%2B-4f46e5?style=flat-square)](https://portimg.com/featured-tools)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)]()
[![Built With](https://img.shields.io/badge/Built%20With-Nuxt.js%20%2B%20Django-00C58E?style=flat-square)](https://portimg.com)

**[🌐 Visit PortImg →](https://portimg.com)**

A fast, free, privacy-first platform for converting, editing, compressing, and transforming images and PDFs — all in your browser with no installs required.

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features & Tools](#-features--tools)
- [Tech Stack](#-tech-stack)
- [Tool Categories](#-tool-categories)
- [Blog & Resources](#-blog--resources)
- [License](#-license)
- [Contact](#-contact)

---

## 🌟 Overview

**[PortImg](https://portimg.com)** is a comprehensive web-based utility platform offering 100+ tools for image conversion, PDF manipulation, OCR, background removal, and more. Everything runs fast — no software downloads, no account needed for most tools.

### Why PortImg?

- ⚡ **Instant Processing** — client-side and server-assisted operations for speed
- 🔒 **Privacy-First** — uploaded files are processed and deleted, never stored long-term
- 🆓 **Free Core Tools** — the most-used features are free, forever
- 📱 **Fully Responsive** — works seamlessly on desktop, tablet, and mobile
- 🌍 **No Installation** — runs entirely in the browser

---

## 🛠 Features & Tools

### 🖼 Image Conversion
Convert between all major raster and vector formats:

| From → To | Supported Formats |
|-----------|-------------------|
| **Raster → Raster** | JPG, JPEG, PNG, GIF, BMP, TIFF, WebP |
| **Raster → Vector** | JPG/PNG/GIF/BMP/TIFF/WebP → SVG, EPS, DXF |
| **Vector → Raster** | SVG/EPS/DXF → JPG, PNG, GIF, BMP, TIFF, WebP |
| **Vector → Vector** | SVG ↔ EPS ↔ DXF |

### 📄 PDF Tools
| Tool | Description |
|------|-------------|
| [Compress PDF](https://portimg.com/compress-pdf) | Reduce PDF file size without quality loss |
| [PDF to Image](https://portimg.com/pdf-to-image) | Convert PDF pages to JPG/PNG |
| [Image to PDF](https://portimg.com/image-to-pdf) | Merge images into a single PDF |
| [Edit PDF](https://portimg.com/edit-pdf) | Annotate and edit PDF documents |
| [Merge PDFs](https://portimg.com/merge-pdfs) | Combine multiple PDFs into one |
| [PDF to Word](https://portimg.com/pdf-to-doc) | Convert PDF to editable .docx |
| [Word to PDF](https://portimg.com/doc-to-pdf) | Convert .docx to PDF |
| [Excel to PDF](https://portimg.com/excel-to-pdf) | Convert spreadsheets to PDF |
| [Add PDF Password](https://portimg.com/add-pdf-password) | Encrypt and password-protect PDFs |
| [Remove PDF Password](https://portimg.com/remove-pdf-password) | Unlock password-protected PDFs |

### 🎨 Image Editing Tools
| Tool | Description |
|------|-------------|
| [Edit Image](https://portimg.com/edit-image) | Online image editor |
| [Resize Image](https://portimg.com/resize-image) | Resize to any dimension |
| [Crop Image](https://portimg.com/crop-image) | Crop images online |
| [Remove Background](https://portimg.com/remove-bg) | AI-powered background removal |
| [Merge Images](https://portimg.com/merge-images) | Combine multiple images into one |
| [Passport Photo Maker](https://portimg.com/passport-photo-maker) | Create compliant passport photos |
| [HTML to Image](https://portimg.com/html-to-image) | Screenshot HTML/URL as image |

### 🔍 OCR & Extraction
| Tool | Description |
|------|-------------|
| [Image to Text (OCR)](https://portimg.com/image-to-text-ocr) | Extract text from any image |

### 📱 Social Media Tools
| Tool | Description |
|------|-------------|
| [Social Media Image Resizer](https://portimg.com/social-media-image-resizer) | Resize for Instagram, Twitter, Facebook, LinkedIn |
| [Image SEO Checker](https://portimg.com/image-seo-checker) | Analyze image SEO health |
| [Image Optimization Analyzer](https://portimg.com/image-optimization-analyzer) | Get optimization suggestions |
| [Image Metadata Remover](https://portimg.com/image-metadata-remover) | Strip EXIF metadata for privacy |

### 🏛 Government Exam Photo Resizers (India)
Purpose-built resizers with exact size and format requirements:

| Tool | Exam |
|------|------|
| [UPSC Photo Resizer](https://portimg.com/upsc-photo-resizer) | UPSC Civil Services |
| [SSC Photo Resizer](https://portimg.com/ssc-photo-resizer) | Staff Selection Commission |
| [Railway Photo Resizer](https://portimg.com/railway-photo-resizer) | RRB / Railway Recruitment |
| [UP Police Photo Resizer](https://portimg.com/up-police-photo-resizer) | UP Police Bharti |
| [Bank PO Photo Resizer](https://portimg.com/bank-po-photo-resizer) | IBPS / SBI PO |
| [NTA Photo Resizer](https://portimg.com/nta-photo-resizer) | NTA Exams |
| [NEET Photo Resizer](https://portimg.com/neet-photo-resizer) | NEET Medical Entrance |
| [Admit Card Photo Resizer](https://portimg.com/admit-card-photo-resizer) | Generic Admit Card |

### 🔧 Utility Tools
| Tool | Description |
|------|-------------|
| [Hash Generator](https://portimg.com/hash-generator) | Generate MD5, SHA-1, SHA-256 hashes |
| [Password Generator](https://portimg.com/online-password-generator) | Secure random password generator |
| [Base64 Encoder/Decoder](https://portimg.com/base64-encoder-decoder) | Encode or decode Base64 strings |
| [Create ZIP Online](https://portimg.com/create-zip-online) | Compress files into a ZIP archive |
| [Unzip Online](https://portimg.com/unzip-online) | Extract ZIP files in-browser |
| [Online Signature Maker](https://portimg.com/online-signature-maker) | Draw or type a digital signature |

---

## 🧰 Tech Stack

> Source code is private. This section documents the architectural stack used to build and deploy PortImg.

### Frontend
- **[Nuxt.js](https://nuxt.com/)** (Vue 3) — SSR/SSG hybrid rendering for SEO performance
- **Tailwind CSS** — Utility-first responsive design
- **Pinia** — State management
- **Vue Composables** — Reusable tool logic abstraction

### Backend
- **[Django](https://www.djangoproject.com/)** — REST API for server-side file processing
- **Django REST Framework** — API endpoints for all tools
- **Celery + Redis** — Async task queue for heavy processing (PDF compression, OCR, vectorization)
- **Pillow / OpenCV** — Image processing pipelines
- **PyMuPDF / pdf2image** — PDF manipulation
- **Tesseract OCR** — Optical Character Recognition engine
- **LibreOffice (headless)** — Office document conversions

### Infrastructure
- **Ubuntu Server** — Self-managed VPS deployment
- **Nginx** — Reverse proxy and static file serving
- **Gunicorn** — WSGI server for Django
- **PM2 / Systemd** — Process management for Node.js and Python services
- **Let's Encrypt (Certbot)** — Free SSL/TLS certificates
- **Cloudflare** — CDN, DDoS protection, and DNS

### Architecture Overview

```
User Browser
     │
     ▼
 Cloudflare CDN
     │
     ▼
  Nginx (Ubuntu Server)
  ├── /           → Nuxt.js SSR App (Node.js)
  └── /api/       → Django REST API (Gunicorn)
                       │
              ┌────────┴────────┐
              ▼                 ▼
        File Processing     Celery Workers
        (Pillow, PyMuPDF,   (Async heavy tasks)
        Tesseract, etc.)         │
                                 ▼
                            Redis (Task Queue)
```

---

## 🗂 Tool Categories

Explore all tools by category on the website:

| Category | Link |
|----------|------|
| All Image Tools | [portimg.com/image-tools](https://portimg.com/image-tools) |
| All PDF Tools | [portimg.com/pdf-tools](https://portimg.com/pdf-tools) |
| Featured Tools | [portimg.com/featured-tools](https://portimg.com/featured-tools) |
| Social Media Tools | [portimg.com/social-media-tools](https://portimg.com/social-media-tools) |
| JPG Tools | [portimg.com/jpg-tools](https://portimg.com/jpg-tools) |
| PNG Tools | [portimg.com/png-tools](https://portimg.com/png-tools) |
| WebP Tools | [portimg.com/webp-tools](https://portimg.com/webp-tools) |
| SVG Tools | [portimg.com/svg-tools](https://portimg.com/svg-tools) |
| GIF Tools | [portimg.com/gif-tools](https://portimg.com/gif-tools) |
| Govt Exam Resizers | [portimg.com/govt-exam-photo-resizers](https://portimg.com/govt-exam-photo-resizers) |

---

## 📖 Blog & Resources

The [PortImg Blog](https://portimg.com/blogs) covers image formats, optimization tips, conversion guides, and PDF workflows:

- [All-in-One Image Converter: What Makes PortImg Unique](https://portimg.com/blog/all-in-One-image-converter-what-makes-portimg-unique)
- [AVIF vs WebP Format Comparison](https://portimg.com/blog/avif-vs-webp-format-comparison)
- [Best Image Format for Print vs Web](https://portimg.com/blog/best-image-format-print-vs-web)
- [Compress PDF Files Without Losing Quality](https://portimg.com/blog/compress-pdf-files-without-losing-quality)
- [Ultimate Guide to OCR: Image to Text](https://portimg.com/blog/ultimate-guide-ocr-image-to-text)
- [Why WebP is Best for Websites](https://portimg.com/blog/why-webp-is-best-for-website)
- [Secure Your PDFs with Passwords](https://portimg.com/blog/secure-your-pdfs-with-passwords)
- [Top 10 Image Formats Explained](https://portimg.com/blog/top-10-image-formats-explained)

[→ View all articles](https://portimg.com/blogs)

---

## 📜 License

This repository is for **showcase purposes only**. The source code is proprietary and not publicly available.

All tools and services are © PortImg. Usage of the platform is subject to the [Terms of Service](https://portimg.com/terms) and [Privacy Policy](https://portimg.com/privacy-policy).

---

## 📬 Contact

| | |
|--|--|
| 🌐 Website | [portimg.com](https://portimg.com) |
| 📧 Contact | [portimg.com/contact-us](https://portimg.com/contact-us) |
| 💼 Advertise | [portimg.com/advertise-with-us](https://portimg.com/advertise-with-us) |
| ❓ FAQ | [portimg.com/faq](https://portimg.com/faq) |

---

<div align="center">

Made with ❤️ by the PortImg Team · [portimg.com](https://portimg.com)

</div>
