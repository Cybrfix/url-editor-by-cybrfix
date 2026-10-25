# 🔗 URL Editor & Domain Extractor Tool
> **Developed by Cybrfix**[cite: 5]

A powerful, lightweight, and completely client-side web utility built for batch processing URLs with speed and precision[cite: 5]. All processing is executed locally right inside your web browser[cite: 5] to ensure maximum speed and privacy.

---

## 🚀 Key Features & Use Cases

* **Batch URL Parameter Trimming (LFI & Security Testing):** 
  * Ideal for penetration testers and bug hunters. When performing **Local File Inclusion (LFI)** testing or parameter manipulation using tools like Burp Suite, you often need to clean or trim massive lists of URLs. 
  * Mode 1 instantly strips everything after the final `=` in every link line, allowing quick payload appending or vulnerability validation.
* **One-Click Domain / Base URL Extraction:** 
  * Extracts clean main host origins (`origin`) or base domains from messy, full-path URL lists in a single click. Useful for scope reduction, reconnaissance, and asset discovery.
* **100% Client-Side Processing:** Runs entirely within your browser via JavaScript without sending any sensitive target lists or data to external servers[cite: 5].
* **Copy & Clear Convenience:** Quick-copy output to clipboard with visual toast alerts and a single-click clear utility.

---

## 🛠️ Operation Modes

1. **Remove text after last '=':** Trims the value following the final `=` in every link line[cite: 5].
2. **Extract Main Domain / Base URL Only:** Strips unwanted paths, query parameters, and fragments to keep only the main host URL[cite: 5].

---

## 💻 Tech Stack
* **HTML5 & JavaScript (Vanilla JS)**
* **Tailwind CSS** (via CDN)[cite: 5]
* **Phosphor Icons**[cite: 5]

---

## 🌐 Live Demo
You can access and use the live tool directly via GitHub Pages:  
👉 [ https://cybrfix.github.io/url-editor-by-cybrfix/ ](#) 
