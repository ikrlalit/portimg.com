<div align="center">

<br/>

# PortImg

**The image and PDF toolkit that just works.**

[![Live Site](https://img.shields.io/badge/🌐_Live_Site-portimg.com-4f46e5?style=for-the-badge)](https://portimg.com)
&nbsp;
[![Tools Count](https://img.shields.io/badge/⚡_100%2B_Tools-Free_to_Use-10b981?style=for-the-badge)](https://portimg.com/featured-tools)
&nbsp;
[![Stack](https://img.shields.io/badge/🛠_Nuxt.js_%2B_Django-Full_Stack-f59e0b?style=for-the-badge)](#tech-stack)

<br/>

> *No signups. No watermarks. No nonsense. Just upload, convert, done.*

<br/>

</div>

---

## The Story Behind It

Most online tools make you jump through hoops — create an account, wait for an email, hit a paywall after two uses. We got tired of that.

**[PortImg](https://portimg.com)** started as a frustration project. We needed a reliable place to convert an image, compress a PDF, or pull text out of a scan — without landing on a sketchy website or installing desktop software that hasn't been updated since 2014.

So we built the tool we actually wanted to use. One URL. 100+ utilities. Everything runs fast, files aren't stored, and the most useful stuff is always free.

---

## What You Can Do

<br/>

### ↔️ Convert Images — Any Format, Any Direction

We support the full matrix of image formats. Whether you're going from a modern WebP to a legacy BMP, or vectorizing a raster logo, it's a single upload away.

**Raster formats:** `JPG` · `JPEG` · `PNG` · `GIF` · `BMP` · `TIFF` · `WebP`  
**Vector formats:** `SVG` · `EPS` · `DXF`

Every combination works. Raster ↔ Raster, Raster → Vector, Vector → Raster, Vector ↔ Vector. Browse the full list at [portimg.com/image-tools](https://portimg.com/image-tools).

<br/>

### 📄 PDF Tools That Cover the Full Workflow

We've all been there — you have a PDF and need to do *something* with it, but you don't have Acrobat and don't want to pay for it. Here's what PortImg handles:

| What You Need | Tool |
|---|---|
| Shrink an oversized PDF | [Compress PDF](https://portimg.com/compress-pdf) |
| Turn PDF pages into images | [PDF → Image](https://portimg.com/pdf-to-image) |
| Combine images into one PDF | [Image → PDF](https://portimg.com/image-to-pdf) |
| Combine multiple PDFs | [Merge PDFs](https://portimg.com/merge-pdfs) |
| Make a PDF editable | [PDF → Word](https://portimg.com/pdf-to-doc) |
| Convert a Word doc to PDF | [Word → PDF](https://portimg.com/doc-to-pdf) |
| Export Excel as PDF | [Excel → PDF](https://portimg.com/excel-to-pdf) |
| Lock a PDF with a password | [Add Password](https://portimg.com/add-pdf-password) |
| Remove a password you forgot | [Remove Password](https://portimg.com/remove-pdf-password) |
| Annotate or fill in a PDF | [Edit PDF](https://portimg.com/edit-pdf) |

<br/>

### 🎨 Image Editing & Enhancement

Not a full Photoshop replacement — but for the quick stuff you need done in 30 seconds, it's more than enough.

- **[Remove Background](https://portimg.com/remove-bg)** — AI-powered, surprisingly accurate on complex edges
- **[Resize Image](https://portimg.com/resize-image)** — Pixel-perfect, with aspect ratio lock
- **[Crop Image](https://portimg.com/crop-image)** — Free crop or fixed aspect ratios
- **[Merge Images](https://portimg.com/merge-images)** — Stack them side-by-side or vertically
- **[Edit Image](https://portimg.com/edit-image)** — Brightness, contrast, filters, text overlays
- **[HTML to Image](https://portimg.com/html-to-image)** — Screenshot any URL or raw HTML as an image
- **[Passport Photo Maker](https://portimg.com/passport-photo-maker)** — Sized and formatted to official standards
- **[Online Signature Maker](https://portimg.com/online-signature-maker)** — Draw, type, or upload your signature

<br/>

### 🔍 OCR — Pull Text Out of Anything

Scanned documents, screenshots, photos of receipts, handwritten notes — the [Image to Text tool](https://portimg.com/image-to-text-ocr) runs Tesseract under the hood and handles multi-language documents cleanly.

<br/>

### 📱 Social Media & SEO Tools

Uploading the wrong image size to Instagram or LinkedIn is one of those small annoyances that adds up. These tools cut that friction:

- **[Social Media Image Resizer](https://portimg.com/social-media-image-resizer)** — Presets for every major platform and post type
- **[Image SEO Checker](https://portimg.com/image-seo-checker)** — Flags alt text, file size, naming, and format issues
- **[Image Optimization Analyzer](https://portimg.com/image-optimization-analyzer)** — Actionable compression and format recommendations
- **[Image Metadata Remover](https://portimg.com/image-metadata-remover)** — Strip EXIF data before posting publicly

<br/>

### 🏛️ Government Exam Photo Resizers

Indian competitive exams have strict, exam-specific photo requirements that trip up a lot of applicants. We built dedicated resizers with the exact dimensions, DPI, and file size limits baked in — no guesswork:

[UPSC](https://portimg.com/upsc-photo-resizer) · [SSC](https://portimg.com/ssc-photo-resizer) · [Railway](https://portimg.com/railway-photo-resizer) · [UP Police](https://portimg.com/up-police-photo-resizer) · [Bank PO](https://portimg.com/bank-po-photo-resizer) · [NTA](https://portimg.com/nta-photo-resizer) · [NEET](https://portimg.com/neet-photo-resizer) · [Admit Card](https://portimg.com/admit-card-photo-resizer)

Full list at [portimg.com/govt-exam-photo-resizers](https://portimg.com/govt-exam-photo-resizers)

<br/>

### 🔧 Developer & Utility Tools

The stuff that doesn't fit neatly into a category but gets used constantly:

- **[Hash Generator](https://portimg.com/hash-generator)** — MD5, SHA-1, SHA-256, and more
- **[Password Generator](https://portimg.com/online-password-generator)** — Configurable length, symbols, entropy estimate
- **[Base64 Encoder / Decoder](https://portimg.com/base64-encoder-decoder)** — Text and file support
- **[Create ZIP](https://portimg.com/create-zip-online)** / **[Unzip Online](https://portimg.com/unzip-online)** — No software needed

---

## Tech Stack

> The source code is private, but we're happy to talk architecture.

Building a tool platform that handles file uploads, heavy processing, and decent traffic requires a few deliberate choices. Here's how PortImg is put together:

### Frontend — Nuxt.js (Vue 3)

The frontend is built on **[Nuxt.js](https://nuxt.com)** with hybrid SSR/SSG rendering. Pages that don't change often are pre-rendered at build time for near-instant loads. Tool pages use server-side rendering so they land fast and index well. Tailwind CSS handles styling — no component library overhead.

### Backend — Django

The API layer runs on **[Django](https://djangoproject.com)** with Django REST Framework. Most tool endpoints are stateless — receive a file, process it, return a result. Heavier operations (PDF compression, OCR, vectorization) get offloaded to **Celery** workers backed by Redis so the API stays responsive.

The processing pipeline uses:
- **Pillow + OpenCV** — raster image operations
- **PyMuPDF + pdf2image** — PDF rendering and manipulation
- **LibreOffice (headless)** — Office document conversion
- **Tesseract** — OCR engine
- **Potrace / Inkscape CLI** — Raster-to-vector tracing

### Infrastructure — Ubuntu + Nginx

Deployed on a **Ubuntu Server** VPS behind **Nginx**, which handles reverse proxying, static asset serving, and SSL termination via Let's Encrypt. Django runs behind Gunicorn. The frontend Node process is managed by PM2. **Cloudflare** sits in front for CDN caching, DDoS mitigation, and DNS.

```
Browser
  └─▶ Cloudflare (CDN + DDoS)
        └─▶ Nginx (Ubuntu VPS)
              ├─▶ Nuxt.js  →  SSR Pages + Static Assets
              └─▶ Gunicorn  →  Django REST API
                                  └─▶ Celery Workers (via Redis)
                                           └─▶ Processing Libraries
```

---

## Explore by Format

Looking for tools for a specific file format? We have dedicated hub pages:

[JPG Tools](https://portimg.com/jpg-tools) · [PNG Tools](https://portimg.com/png-tools) · [WebP Tools](https://portimg.com/webp-tools) · [GIF Tools](https://portimg.com/gif-tools) · [BMP Tools](https://portimg.com/bmp-tools) · [TIFF Tools](https://portimg.com/tiff-tools) · [SVG Tools](https://portimg.com/svg-tools) · [EPS Tools](https://portimg.com/eps-tools) · [DXF Tools](https://portimg.com/dxf-tools)

---

## From the Blog

We write about image formats, compression techniques, OCR accuracy, PDF workflows, and web performance. No SEO fluff — just guides we'd actually want to read.

A few recent picks:

- 📷 [AVIF vs WebP — A Proper Format Comparison](https://portimg.com/blog/avif-vs-webp-format-comparison)
- 🗜️ [How to Compress a PDF Without Losing Quality](https://portimg.com/blog/compress-pdf-files-without-losing-quality)
- 🔍 [The Complete Guide to OCR: Image to Text](https://portimg.com/blog/ultimate-guide-ocr-image-to-text)
- 🌐 [Why WebP Should Be Your Default for Web Images](https://portimg.com/blog/why-webp-is-best-for-website)
- 🖼️ [Best Image Format for Print vs Web](https://portimg.com/blog/best-image-format-print-vs-web)
- 🔐 [How to Password-Protect a PDF (and When You Should)](https://portimg.com/blog/secure-your-pdfs-with-passwords)
- 📱 [Converting Images for Every Device and Platform](https://portimg.com/blog/convert-any-image-format-online)

[→ All articles on the blog](https://portimg.com/blogs)

---

## Privacy

Files uploaded to PortImg are used only to perform the requested operation. They are not stored permanently, not shared with third parties, and not used for training anything. The full policy is at [portimg.com/privacy-policy](https://portimg.com/privacy-policy).

---

## Get in Touch

If you're interested in integrating PortImg tools into your product, have a feature request, or just want to say hi:

- 🌐 [portimg.com](https://portimg.com)
- 📬 [Contact us](https://portimg.com/contact-us)
- 📣 [Advertise with us](https://portimg.com/advertise-with-us)
- ❓ [FAQ](https://portimg.com/faq)

---

<div align="center">

<br/>

Built and maintained by the PortImg team.

**[portimg.com](https://portimg.com)**

<br/>

</div>
