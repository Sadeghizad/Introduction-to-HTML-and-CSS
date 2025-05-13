# 📄 Advanced HTML5 Showcase

This project demonstrates a wide range of **HTML5 features** showcasing my **full command of modern, semantic, and standards-compliant HTML**.

The file includes proper use of multimedia, tabular data, semantic elements, citations, accessibility attributes, and character entities—all crafted for clarity, usability, and maintainability.

---

## 🚀 Highlights

| Feature                    | Description                                                     |
| -------------------------- | --------------------------------------------------------------- |
| **Audio/Video**            | Native HTML5 players with controls and fallback support         |
| **Downloadable Asset**     | Uses the `download` attribute for direct file saving            |
| **Date/Time Semantics**    | Machine-readable dates via `<time datetime="">`                 |
| **Structured Table**       | Advanced table with `rowspan` for cleaner repetition            |
| **Quotations & Citations** | Proper semantic elements like `<blockquote>`, `<q>`, `<cite>`   |
| **Contact Info**           | Encapsulated using `<address>` with multi-line formatting       |
| **Character Entities**     | Usage of `&lt;`, `&copy;`, `&trade;`, etc. for proper rendering |

---

## 📁 Structure

```
project/
├── index.html              ← Main showcase file
├── files/logo.png          ← Downloadable logo
├── assets/lecture.mp4      ← Used in both <audio> and <video>
├── assets/poster.png       ← Poster image for video tag
```

> Update paths if relocating the HTML file.

---

## 🧠 Clean Code Principles Demonstrated

* ✅ **Semantic HTML**: Each tag serves a meaningful role.
* ✅ **Minimal Dependencies**: Pure HTML with no external scripts or styles.
* ✅ **Accessibility**: Elements like `<time>`, `<address>`, and semantic tags improve screen reader support.
* ✅ **Internationalization (i18n)**: Example includes Persian content and bidirectional handling.
* ✅ **Fallback and Redundancy**: Ensures graceful degradation (e.g., video fallback message).

---

## 🔍 Code Sample Highlights

```html
<audio src="assets/lecture.mp4" controls></audio>

<a href="/files/logo.png" download="Logo">دانلود لوگو</a>

<time datetime="2024-02-10T22:30">10.30pm, 10 February 2024</time>

<table border="1" style="border-collapse: collapse">
  ...
</table>

<blockquote cite="https://www.huxley.net/bnw/four.html">
  <p>Words can be like X-rays...</p>
</blockquote>

<video src="assets/lecture.mp4" controls poster="assets/poster.png">
  مرورگر قادر به پخش ویدئو نیست.
</video>
```

---

## 📧 Contact

📍 Sadat Abad, Tehran, Iran
📞 +98937 294 2639
📩 [mosadeghizad@gmail.com](mailto:mosadeghizad@gmail.com)

---

## 🖋️ License

Free to use and adapt for learning or showcase purposes. Attribution appreciated.

