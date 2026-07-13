<div align="center">

<pre>
<font color="#FF8C00">
                                   .              .             ●          
       .               *        .            .       .              .           
                 .               *         ●               .         .              .              .           
       ●              *              .          .              ●             .              *              *              .               .
                                                          

    ███████╗██╗   ██╗███████╗██╗   ██╗ ██████╗ ██╗   ██╗ 
    ██╔════╝╚██╗ ██╔╝╚══███╔╝╚██╗ ██╔╝██╔════╝ ╚██╗ ██╔╝ 
    ███████╗ ╚████╔╝   ███╔╝  ╚████╔╝ ██║  ███╗ ╚████╔╝  
    ╚════██║  ╚██╔╝   ███╔╝    ╚██╔╝  ██║   ██║  ╚██╔╝   
    ███████║   ██║   ███████╗   ██║   ╚██████╔╝   ██║    
    ╚══════╝   ╚═╝   ╚══════╝   ╚═╝    ╚═════╝    ╚═╝    

               .              .              .           1.0.0
       .          ●             .               *              .       ●          
                 .               *        .         .               .              .              .           
       ●               *        .               ●              .              .              *         *  
</font>
</pre>


[![简体中文](https://img.shields.io/badge/🇨🇳-简体中文-red)](./README.md) [![English](https://img.shields.io/badge/🇺🇸-English-blue)](./README_EN.md) [![日本語](https://img.shields.io/badge/🇯🇵-日本語-lightgrey)](./README_JP.md)

**A Highly Smooth, Drag-and-Drop Web Resource Collection Browser Extension**

![version](https://img.shields.io/badge/version-v1.0.0-blue)

---

Available on: [![XHS](https://img.shields.io/badge/XHS-Xiaohongshu-ff2442)](https://xhslink.com/m/6hngqAykU24) [![QQ Group 1](https://img.shields.io/badge/QQ-Group%201-0084ff)](https://qm.qq.com/q/UiJVC3TZ2o) [![QQ Group 2](https://img.shields.io/badge/QQ-Group%202-0084ff)](https://qm.qq.com/q/6YW5SHcf04) [![WeChat](https://img.shields.io/badge/WeChat-yuhao__xiaban-07c160)](#) [![Official Account](https://img.shields.io/badge/Official%20Account-QR%20Code-07c160)](./assets/公众号二维码.jpg) [![UniFans](https://img.shields.io/badge/UniFans-Patron-946ce6)](https://app.unifans.io/c/y837668142)
</div>

---

## 📖 Introduction

In modern web pages, dynamic layouts are becoming increasingly complex, making traditional "Save As" or "Copy-Paste" methods for extracting resources very cumbersome. **Syzygy** was created to solve this.

Its core positioning is a highly smooth **"drag-and-drop web resource collection tool"**. The underlying architecture is injected with runtime self-adaptation and stability guardian logic, ensuring stable operation in various complex front-end web environments. With simple "drag and drop" actions, you can achieve WYSIWYG resource capture.

## ✨ Core Features

### 🪐 1. Innovative Force-Directed Gravity Engine (Dropzone Float)
Syzygy completely abandons traditional list stacking, adding a planetary companion to your web page. It can be dragged and zoomed arbitrarily, colliding and intertwining with captured resources (satellite nodes).
* **Mathematical Gravity Field Layout**: Based on Fermat's Spiral combined with the Golden Angle, it calculates the initial distribution of satellite nodes for uniform visual density.
* **Smooth Gravity Transition**: During drag and flick gestures, it uses EMA speed judgment and a first-order low-pass filter to simulate smooth physical attraction and centrifugal effects.
* **Collision & Elastic Boundaries**: Adaptive collision avoidance and elastic soft buffering at the viewport edges ensure multiple tasks do not overlap or overflow.

![](assets/操作演示.gif)

### 🎬 2. Deep Web Video Capture
Whether it's a standard video or a complex video sliced by special processing, simply hold `Shift` and drag. The backend automatically performs traffic analysis, accurately restoring and extracting the real download address.

![](assets/视频下载.gif)

### 🖼️ 3. Multi-Format High-Res Image & Background Extraction
Supports high-resolution original image extraction, penetrating complex page hierarchies to extract image resources hidden in CSS pseudo-elements or background attributes.

![](assets/图片下载.gif)
![](assets/GIF捕获.gif)

### 📊 4. Structured Table & Text Extraction
Drag tables or text on web pages to automatically extract structured data or high-value text information. Drag and go, saving you from tedious copying.

![](assets/表格捕获.gif)

### 📚 5. Web Comic & Long Image Extraction (Gesture Switch)
For Canvas or multi-nested special reading sites, just **flick (shake) your mouse rapidly left and right** in the air to trigger the gesture algorithm, cycling through candidate resource objects for precise locking.

![](assets/网页漫画捕获.gif)

### 💻 6. Pure Source Code Capture
One-click capture and format the pure source code of the current page or specific iframe, directly analyzing the structure and bidding farewell to cumbersome developer tools.

![](assets/网页源码.gif)

### 🛡️ 7. Ad & Tracking Script Blocking
Automatically applies multiple filtering rules to web requests, intercepting pre-roll ads and tracking scripts to ensure the purity of captured media sources.

![](assets/广告屏蔽.gif)

### 💾 8. One-Click Rapid Local Download
Directly calls the browser's native download interface. After capturing, just click the satellite node to securely save the resource to your local disk.

![](assets/下载演示.gif)

## 🔧 Installation & Configuration

1. **Download the Release Packages**:
   The project release consists of two components. Please download both:
   - **`Syzygy_Extension.zip`** (Browser Extension)
   - **`Syzygy_Server.exe`** (Backend Server)

2. **Install the Browser Extension**:
   - Extract **`Syzygy_Extension.zip`** and place the extracted folder in a safe location where it won't be accidentally deleted.
   - Open your browser and navigate to the extension management page (e.g., `chrome://extensions/` for Chrome).
   - Enable **"Developer mode"** in the top-right corner.
   - Click **"Load unpacked"** and select the extracted extension folder to install it.

3. **Configure the Server & Connection**:
   - Run **`Syzygy_Server.exe`**. Read and agree to the user agreement. By default, it will enter **Trial Mode**.
   - In the main menu of the server terminal, locate and copy the **`AccessToken`**.
   - Go back to the browser, right-click the Syzygy extension icon, and select **"Options"**.
   - Paste the copied `AccessToken` into the **"Access Token (内网通行证)"** field.
   - Verify that the **"Server URL (后端基站通信地址)"** IP and port in the options page match the server terminal display.
   - Click **"Save"** to apply the configuration.
   - Go back to the server terminal, enter `1` and press Enter to start the service.
   - Return to your browser. If the **"Server Connection Status Light"** turns **green**, the connection is successful, and you are ready to capture and download resources!

## 🎮 Operations & Shortcuts

- **Element Capture**: Hold `Shift` and drag a webpage element with your mouse to capture it.
- **Resource Download**: Drag the captured elements into the Dropzone floating window to trigger the download.
- **Switch Candidate Objects**: When multiple elements are captured, **shake/flick your mouse rapidly left and right** to cycle through the candidate resource objects.
- **Clear Cache**: Press `Shift + Alt + X` to clear cache and records for the current website.
- **Debug Capture Mode**: Press `Ctrl + Shift + D` to open the capture debug panel to verify the number of captured elements.

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

## 📬 Feedback & Support

If you encounter any issues during installation, configuration, or usage, or if you have suggestions, please feel free to reach out:
- **Email**: [martianc.feedback@gmail.com](mailto:martianc.feedback@gmail.com)
- Alternatively, you can open an [Issue](https://github.com/MartianDovah/syzygy_downloader/issues) on our GitHub repository.

## ❤️ Sponsor & Support

If Syzygy has helped you and saved you valuable time, please consider buying me a coffee via **UniFans** or becoming a long-term sponsor! Your support is my greatest motivation to keep coding and updating 🚀

<a href="https://app.unifans.io/c/y837668142" target="_blank"><img src="assets/YLQlogo.svg" height="30"></a> *👈 [Click here to visit my UniFans page](https://app.unifans.io/c/y837668142)*
