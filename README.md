# Awesome-AI-Image-Enhancement

# Top AI Image Enhancement Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Super-Resolution, Face Restoration & Real-World Image Restoration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Image Enhancement**. These tools enable photographers, archivists, and creators to upscale low-resolution images, restore degraded faces, remove noise and compression artifacts, and recover detail in photographs where the original signal has been lost.

**Examples** include Remini, Topaz Photo AI, VanceAI, Let's Enhance, Fotor, Cutout.pro, Pixelcut, Photoroom, Magnific AI, and Spaceman (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, face restoration, and super-resolution—ideal for researchers, photographers, and developers seeking transparent, vendor-independent image enhancement.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Remini](https://remini.ai/)**
  Mobile app for photo and video enhancement. Over 100 million photos revitalized. Uses deep learning for face restoration, sharpening, and upscaling. Subscription-based with weekly/yearly plans.

- **[Topaz Photo AI](https://www.topazlabs.com/topaz-photo-ai)**
  Desktop AI photo enhancement suite. Features Gigapixel (upscaling), DeNoise AI, Sharpen AI, and face recovery. **The most feature-complete commercial desktop enhancement tool.**

- **[VanceAI](https://vanceai.com/)**
  AI image enhancement suite including upscaler, denoiser, sharpener, and background remover. Credit-based pricing with multiple tool subscriptions.

- **[Let's Enhance](https://letsenhance.io/)**
  Online image upscaling and enhancement. Features AI upscaling up to 16x, background removal, and smart compression.

- **[Fotor](https://www.fotor.com/)**
  Online photo editor with AI enhancement tools. Features AI upscaling, background removal, and object removal.

- **[Cutout.pro](https://www.cutout.pro/)**
  AI visual design platform with photo enhancement, background removal, and upscaling. API access available.

- **[Pixelcut](https://www.pixelcut.ai/)**
  AI photo editing for e-commerce. Background removal, product staging, and batch editing.

- **[Photoroom](https://www.photoroom.com/)**
  AI photo editing for e-commerce. Features background removal, AI backgrounds, and batch editing.

- **[Magnific AI](https://magnific.ai/)**
  AI image upscaling and enhancement with creative detail generation. Known for aggressive upscaling with artistic style preservation.

- **[Spaceman](https://spaceman.id/)**
  AI image upscaling and enhancement platform.

## Open-Source GitHub Projects

- **[GFPGAN](https://github.com/TencentARC/GFPGAN)**
  **Practical Algorithm for Real-world Face Restoration** (Apache-2.0). **35,000+ GitHub stars.** The standard open-source face restoration model—recovers faces from degraded images with high fidelity. **Widely used in restoration pipelines alongside Real-ESRGAN** .

- **[CodeFormer](https://github.com/sczhou/CodeFormer)**
  **Towards Robust Blind Face Restoration with Codebook Lookup Transformer** (NTU S-Lab License). **10,000+ GitHub stars.** **Often produces subtler results than GFPGAN**—start with CodeFormer at low strength for less aggressive restoration . **Restrictions apply for commercial use**—verify license before deployment .

- **[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)**
  **Practical algorithms for general image and video restoration** (BSD-3-Clause). **36,000+ GitHub stars.** Ships portable executables for Windows, Linux, and macOS. **AnimeVideo-v3** for video content—3× faster than Real-CUGAN at Full HD. **RealESRGAN_x4plus_anime_6B** for compact anime-image upscaling. Python inference supports tiling for low-VRAM GPUs .

- **[BasicSR](https://github.com/XPixelGroup/BasicSR)**
  **Open Source Image and Video Restoration Toolbox for Super-resolution, Denoise, Deblurring, etc.** (Apache-2.0). **8,285 GitHub stars.** Includes EDSR, RCAN, SRResNet, SRGAN, ESRGAN, EDVR, BasicVSR, SwinIR, ECBSR, StyleGAN2, and DFDNet .

- **[Restormer](https://github.com/swz30/Restormer)**
  **Efficient Transformer for High-Resolution Image Restoration** (CVPR 2022 Oral). **1,805 GitHub stars.** SOTA for motion deblurring, image deraining, denoising (Gaussian/real data), and defocus deblurring .

- **[MPRNet](https://github.com/swz30/MPRNet)**
  **Multi-Stage Progressive Image Restoration** (CVPR 2021). **1,186 GitHub stars.** SOTA results for image deblurring, deraining, and denoising .

- **[Uformer](https://github.com/ZhendongWang6/Uformer)**
  **A General U-Shaped Transformer for Image Restoration** (CVPR 2022). **796 GitHub stars.** General architecture for denoising, deraining, and deblurring .

- **[SwinIR](https://github.com/JingyunLiang/SwinIR)**
  **Image Restoration Using Swin Transformer** (official repository). **5,514 GitHub stars.** Strong performance across super-resolution, denoising, and artifact reduction .

- **[HAT (Hybrid Attention Transformer)](https://github.com/XPixelGroup/HAT)**
  **Activating More Pixels in Image Super-Resolution Transformer** (CVPR 2023). **1,551 GitHub stars.** Strong super-resolution performance, though may introduce brightness shifts in some applications .

- **[KAIR](https://github.com/cszn/KAIR)**
  **Image Restoration Toolbox (PyTorch)** . **3,491 GitHub stars.** Training and testing codes for DPIR, USRNet, DnCNN, FFDNet, SRMD, DPSR, BSRGAN, SwinIR .

- **[Swin2SR](https://github.com/mv-lab/swin2sr)**
  **SwinV2 Transformer for Compressed Image Super-Resolution and Restoration** (ECCV 2022). Strong performance on JPEG artifact removal and compressed image restoration .

- **[SUPIR](https://github.com/Fanghua-Yu/SUPIR)**
  **Practical Algorithms for Photo-Realistic Image Restoration In the Wild** (open-source). Online demo available at suppixel.ai. **The most aggressive open-source restoration approach** .

- **[StableSR](https://github.com/IceClear/StableSR)**
  **Exploiting Diffusion Prior for Real-World Image Super-Resolution** (IJCV 2024). Leverages diffusion models for realistic super-resolution .

- **[SeeSR](https://github.com/cswry/SeeSR)**
  **Towards Semantics-Aware Real-World Image Super-Resolution** (CVPR 2024). **437 GitHub stars.** Uses semantic awareness for better super-resolution results .

- **[InstructIR](https://github.com/mv-lab/InstructIR)**
  **High-Quality Image Restoration Following Human Instructions** (ECCV 2024). **3.3M+ runs on Replicate.** Instruct-based restoration—describe what you want fixed .

- **[OpenPixels](https://gitlab.com/openpixelsapp/OpenPixels)**
  **The open-source alternative to Remini, Let's Enhance and Topaz Photo AI** (open-source). **Every photo stays in your browser—nothing uploaded.** Features **upscale to 8×**, **noise and compression artifact removal**, **face reconstruction**, **colorization of black-and-white photos**, **background removal**, and **batch processing**. **Shows before/after slider with real measurements**—a capability none of the twelve products surveyed in their PLAN.md offer. **Nine ONNX models, all under commercial-use licenses, every one checksum-pinned.** Built with Rust (pixel operations) and Svelte 5 (UI), running in a Web Worker with WebGPU. **The most privacy-preserving open-source image enhancer available** .

- **[local-upscaler](https://pypi.org/project/local-upscaler/)**
  **Drag a photo in, click Enhance, done** (open-source). Model weights download automatically with checksum verification. Features **4× upscale**, **deblur (NAFNet)**, **face restore (GFPGAN)**, **ONNX backend**, **batch folder processing**, **video frame-by-frame upscaling with ffmpeg**, **format conversion**, and **Remove BG**. **GPU-accelerated setup for AMD on Windows via WSL2 + ROCm.** **The most accessible command-line upscaler** for developers .

- **[Upscalin](https://github.com/BrokenSource/Upscalin)**
  Open-source image upscaling tool (Python) .

### Additional Strong Open-Source Options

- **[Awesome-Super-Resolution](https://github.com/ChaofWang/Awesome-Super-Resolution)** — Collect super-resolution related papers, data, and repositories. **3,071 GitHub stars** .
- **[Awesome-Face-Restoration](https://github.com/TaoWangzj/Awesome-Face-Restoration)** — Comprehensive list of face restoration methods. **435 GitHub stars** .
- **[Awesome-Denoise](https://github.com/oneTaken/Awesome-Denoise)** — Latest image/burst/video denoising papers with code. **417 GitHub stars** .
- **[image_api](https://github.com/Dodant/image_api)** — Image AI API for outpainting and super-resolution .
- **[Face-Upscalers-ONNX](https://github.com/harisreedhar/Face-Upscalers-ONNX)** — ONNX-powered inference for state-of-the-art face upscalers .
- **[GFPGAN-1024](https://github.com/LeslieZhoa/GFPGAN-1024)** — GFPGAN variant for 1024 resolution .
- Community **n8n** workflows for batch image enhancement automation and asset pipeline integration.

**Frameworks for building custom systems**: Combine **GFPGAN** or **CodeFormer** for face restoration with **Real-ESRGAN** for upscaling, **Restormer** or **MPRNet** for denoising and deblurring, **SwinIR** for general restoration, and **OpenPixels** for privacy-preserving browser-based processing—creating a fully self-hosted, enterprise-grade image enhancement platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI image enhancement tools handling personal photographs must comply with data protection regulations (GDPR, CCPA, etc.) and respect personal likeness rights.
- **Open-source image enhancement is mature and production-ready.** GFPGAN (35K+ stars) and CodeFormer (10K+ stars) handle face restoration . Real-ESRGAN (36K+ stars) handles upscaling . Restormer and MPRNet handle denoising and deblurring . **These are genuine alternatives to Remini and Topaz Photo AI.**
- **Face restoration requires ethical consideration.** GFPGAN and CodeFormer can generate plausible facial detail that may not accurately reflect the original subject. **Never use face restoration to misrepresent identity in forensic, journalistic, or evidentiary contexts.** Research shows GFPGAN can produce "unnatural pupils" while HAT emits brightness shifts—outputs should be validated for accuracy .
- **Restoration is not the same as enhancement.** OpenPixels explicitly excludes AI portrait generation—"enhancing your photo and inventing a new one are different jobs." Aggressive upscaling models can drift on faces and text at high scale factors. **A 2× pass is the safer default than 4× on important photographs** .
- **License restrictions apply to commercial use.** CodeFormer carries NTU S-Lab License with non-commercial restrictions . OpenPixels curates nine ONNX models, **all under commercial-use licenses, every one checksum-pinned**—a rare display of licensing discipline .
- Self-hosted open-source solutions require proper GPU provisioning, model management, and ongoing maintenance. **Generated content may inadvertently reproduce training data—validate outputs for copyright compliance before commercial use.**

---

**Made for photographers, archivists, and developers building transparent AI image enhancement solutions.**  
Let's make AI Image Enhancement more open, data-driven, and detail-preserving.
