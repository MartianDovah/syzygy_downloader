<div align="center">

```text
 ███████╗██╗   ██╗███████╗██╗   ██╗ ██████╗ ██╗   ██╗
 ██╔════╝╚██╗ ██╔╝╚══███╔╝╚██╗ ██╔╝██╔════╝ ╚██╗ ██╔╝
 ███████╗ ╚████╔╝   ███╔╝  ╚████╔╝ ██║  ███╗ ╚████╔╝
 ╚════██║  ╚██╔╝   ███╔╝    ╚██╔╝  ██║   ██║  ╚██╔╝ 
 ███████║   ██║   ███████╗   ██║   ╚██████╔╝   ██║  
 ╚══════╝   ╚═╝   ╚══════╝   ╚═╝    ╚═════╝    ╚═╝  
```

[![简体中文](https://img.shields.io/badge/🇨🇳-简体中文-red)](./README.md) [![English](https://img.shields.io/badge/🇺🇸-English-blue)](./README_EN.md) [![日本語](https://img.shields.io/badge/🇯🇵-日本語-lightgrey)](./README_JP.md)

**A Highly Smooth, Drag-and-Drop Web Resource Collection Browser Extension**

![version](https://img.shields.io/badge/version-v1.0.0-blue)
</div>

---

## 📖 Introduction

In modern web pages, dynamic layouts are becoming increasingly complex, making traditional "Save As" or "Copy-Paste" methods for extracting resources very cumbersome. **Syzygy (Super_Dropzone)** was created to solve this.

Its core positioning is a highly smooth **"drag-and-drop web resource collection tool"**. The underlying architecture is injected with runtime self-adaptation and stability guardian logic, ensuring stable operation in various complex front-end web environments. With simple "drag and drop" actions, you can achieve WYSIWYG resource capture.

## ✨ Core Features

### 🪐 1. Innovative Force-Directed Gravity Engine (Dropzone Float)
Syzygy completely abandons traditional list stacking, adding a planetary companion to your web page. It can be dragged and zoomed arbitrarily, colliding and intertwining with captured resources (satellite nodes).
* **Mathematical Gravity Field Layout**: Based on Fermat's Spiral combined with the Golden Angle, it calculates the initial distribution of satellite nodes for uniform visual density.
* **Smooth Gravity Transition**: During drag and flick gestures, it uses EMA speed judgment and a first-order low-pass filter to simulate smooth physical attraction and centrifugal effects.
* **Collision & Elastic Boundaries**: Adaptive collision avoidance and elastic soft buffering at the viewport edges ensure multiple tasks do not overlap or overflow.

![](https://pic1.imgdb.cn/item/6a436160514f59159c639145.gif)

### 🎬 2. Deep Web Video Capture
Whether it's a standard video or a complex video sliced by special processing, simply hold `Shift` and drag. The backend automatically performs traffic analysis, accurately restoring and extracting the real download address.

![](https://pic1.imgdb.cn/item/6a4362d7514f59159c639274.gif)

### 🖼️ 3. Multi-Format High-Res Image & Background Extraction
Supports high-resolution original image extraction, penetrating complex page hierarchies to extract image resources hidden in CSS pseudo-elements or background attributes.

![](https://pic1.imgdb.cn/item/6a436196514f59159c639180.gif)
![](https://pic1.imgdb.cn/item/6a436160514f59159c639146.gif)

### 📊 4. Structured Table & Text Extraction
Drag tables or text on web pages to automatically extract structured data or high-value text information. Drag and go, saving you from tedious copying.

![](https://pic1.imgdb.cn/item/6a436199514f59159c639182.gif)

### 📚 5. Web Comic & Long Image Extraction (Gesture Switch)
For Canvas or multi-nested special reading sites, just **flick (shake) your mouse rapidly left and right** in the air to trigger the gesture algorithm, cycling through candidate resource objects for precise locking.

![](https://pic1.imgdb.cn/item/6a43615f514f59159c639144.gif)

### 💻 6. Pure Source Code Capture
One-click capture and format the pure source code of the current page or specific iframe, directly analyzing the structure and bidding farewell to cumbersome developer tools.

![](https://pic1.imgdb.cn/item/6a436159514f59159c63913e.gif)

### 🛡️ 7. Ad & Tracking Script Blocking
Automatically applies multiple filtering rules to web requests, intercepting pre-roll ads and tracking scripts to ensure the purity of captured media sources.

![](https://pic1.imgdb.cn/item/6a43615c514f59159c639142.gif)

### 💾 8. One-Click Rapid Local Download
Directly calls the browser's native download interface. After capturing, just click the satellite node to securely save the resource to your local disk.

![](https://pic1.imgdb.cn/item/6a43615b514f59159c639141.gif)

## 🔒 Statements & Technical Protection

**1. No Cracking or Privilege Escalation**
Syzygy absolutely does not contain any code for cracking Digital Rights Management (DRM, such as Widevine, FairPlay, etc.), nor does it feature account privilege escalation or VIP paywall bypassing. This extension strictly integrates and extracts unencrypted data streams publicly transmitted on web pages within the compliant API framework of the browser, replacing tedious manual packet capturing.

**2. Note on Current "Closed Source" and Technical Protection**
As a developer who loves open-source sharing, deciding to temporarily keep this project closed-source was a difficult decision. This is primarily based on the following considerations:
* **Preventing Abuse & API Scraping**: The extension integrates deep resource fetching and bypass technologies. If fully open-sourced, it is highly susceptible to being repackaged by gray-market teams into large-scale commercial scraping tools, leading to upgraded protections on target websites and potentially malicious traffic on backend services.
* **Protecting Core Tech & Anti-Reversing**: To cope with highly-protected web pages, we've implemented a series of runtime protection mechanisms in the extension (e.g., sandbox hardening against host probing, anti-pollution mechanisms, dynamic DOM self-healing guardians). Fully open-sourcing would make it easy to crack these defenses or resell the package, ultimately causing abuse.

Once I find an effective method to protect the copyright, I will consider open-sourcing it. I hope for your understanding.

## ⏳ Current Development Status & Challenges

From the very first line of code to the current complete architecture, this project has been independently developed by me alone during my off-work hours.

As the project delves into deeper technical waters, funding and resources are facing significant pressure. Server bandwidth costs, daily maintenance, multi-platform compatibility testing, and keeping up with the changing strategies of target websites all require substantial effort and material resources. **Due to the lack of stable financial support, the current iteration progress is highly constrained, and updates are moving rather slowly.**

I very much hope to maintain this project long-term, building it into the handiest tool in every geek's browser. Thank you all for your continuous patience and support!

## ❤️ Sponsor & Support

If Syzygy has helped you and saved you valuable time, please consider buying me a coffee via **Afdian** or becoming a long-term sponsor! Your support is my greatest motivation to keep coding and updating 🚀

<a href="https://afdian.com/a/syzygy_downloader" target="_blank"><img src="https://afdian.net/static/img/logo/logo.png" height="30"></a>
*(Click to visit my Afdian page)*
