# 💻 ytuOS - Tek Dosyalık Web İşletim Sistemi / Single-File Web OS
<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/6f3917c7-ada9-4b6e-bf6c-ccec96862592" />


[![TR](https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e-red)](#türkçe)
[![EN](https://img.shields.io/badge/Language-English-blue)](#english)

---

## 🇹🇷 Türkçe

Tamamen **tek bir HTML dosyası** içinde çalışan, tarayıcı tabanlı tam işlevsel bir masaüstü ortamı. Herhangi bir derleme aracı veya karmaşık framework kullanılmadı; sadece saf Web API'leri, Vanilla JavaScript ve biraz da WebAssembly var.

### ✨ Özellikler

* **Özel Pencere Yöneticisi:** Dinamik z-index yönetimi ile sürüklenebilir, yeniden boyutlandırılabilir ve küçültülebilir pencereler.
* **Gerçek Python Ortamı:** Doğrudan tarayıcı terminalinde gerçek Python 3.10 kodlarını çalıştırmayı sağlayan entegre **Pyodide** (WebAssembly üzerinden Python) mimarisi.
* **Canlı Kod Editörü:** Yazdığınız kodları bir iframe üzerinden anlık olarak derleyen mini HTML/CSS/JS çalışma alanı.
* **Glassmorphism UI:** Yarı saydam arka planlar ve dinamik animasyonlarla modern, şık bir arayüz.
* **Dahili Uygulamalar:**
    * 🐍 **Yılan Oyunu:** HTML5 Canvas tabanlı klasik akıcı yılan oyunu.
    * 🎨 **Dijital Paint:** Renk ve fırça boyutu seçimi olan Canvas çizim aracı.
    * 📁 **Dosya Yöneticisi:** Etkileşimli arayüze sahip simüle edilmiş bir dosya sistemi.
    * 🎬 **Video Editörü:** Video renk düzenlemesi için gerçek zamanlı CSS filtre manipülasyonu.

### 🚀 Nasıl Çalıştırılır?

Çok basit. Sadece projeyi klonlayın veya indirin.
1. `index.html` dosyasını indirin.
2. Dosyaya çift tıklayarak Google Chrome'da (veya herhangi bir modern tarayıcıda) açın.
3. *Not: Python Terminali, ilk açılışta Pyodide çalışma zamanını çekmek için aktif bir internet bağlantısı gerektirir.*

### 🛠️ Teknolojiler

* **Frontend:** Vanilla JavaScript, HTML5, CSS3 (CSS Değişkenleri, Flexbox/Grid, Animasyonlar)
* **API'ler:** HTML5 Canvas API, DOM Manipülasyonu
* **WASM:** Python runtime için [Pyodide](https://pyodide.org/).

### 👨‍💻 Geliştirici
**Altay YELES** - Matematik Mühendisliği (Mathematical Engineering) Öğrencisi

---

## 🇬🇧 English

A fully functional, browser-based desktop environment contained entirely within a **single HTML file**. No build tools, no complex frameworks—just pure Web APIs, Vanilla JavaScript, and a touch of WebAssembly.

### ✨ Features

* **Custom Window Manager:** Draggable, resizable, and minimizable windows with dynamic z-index management.
* **Real Python Environment:** Integrated **Pyodide** (Python over WebAssembly) allowing you to execute real Python 3.10 code directly in the browser terminal.
* **Live Code Editor:** A mini HTML/CSS/JS playground that renders your code in real-time via an iframe.
* **Glassmorphism UI:** Modern, sleek interface with backdrop filters and dynamic animations.
* **Built-in Applications:**
    * 🐍 **Snake Game:** HTML5 Canvas-based classic game.
    * 🎨 **Digital Paint:** Canvas drawing tool with color and brush size selection.
    * 📁 **File Explorer:** A simulated file system with interactive UI.
    * 🎬 **Video Editor:** Real-time CSS filter manipulation for video color grading.

### 🚀 How to Run

It's ridiculously simple. 

1. Download the `index.html` file.
2. Double-click it to open in Google Chrome (or any modern browser).
3. *Note: The Python Terminal requires an active internet connection on the first run to fetch the Pyodide runtime.*

### 🛠️ Tech Stack

* **Frontend:** Vanilla JavaScript, HTML5, CSS3 (CSS Variables, Flexbox/Grid, Animations)
* **APIs:** HTML5 Canvas API, DOM Manipulation
* **WASM:** [Pyodide](https://pyodide.org/) for the Python runtime.

### 👨‍💻 Developer
**Altay Y.** - Mathematical Engineering Student
