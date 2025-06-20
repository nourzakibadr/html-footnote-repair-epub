### 📘 Stiff EPUB Footnote Restoration - Linkage Project :)
 
### About the Project

This project involved manually reconstructing and repairing the internal footnote structure of the EPUB version of *Stiff: The Curious Lives of Human Cadavers* by Mary Roach (320 pages), which had broken or improperly linked footnotes due to a flawed conversion from a Kindle-based format.

The goal was to restore all footnote references and definitions to make the reading experience seamless, structurally correct, and accessible.

This project was completed during my summer vacation as a way to practically apply HTML and regex concepts I learned during my BIS (Business Information Systems) coursework.

---

### 🛠️ Tools & Skills Used

* **Calibre Edit Book**: for EPUB structure navigation, editing `.xhtml` files, and previewing footnote behaviors.
* **HTML / XHTML**: to edit, clean, and structure content consistently across chapters and footnote sections.
* **CSS awareness**: for identifying and maintaining consistent class-based styling across content.
* **Regular Expressions (Regex)**: to automate the detection and replacement of broken links and format inconsistencies in footnotes across multiple text files.
* **Problem-Solving & Debugging**: analyzing non-functional filepos-based hyperlinks and reverse engineering their structure to implement a clean, functional link-back mechanism.

---

### 🧩 Key Tasks Completed

* Replaced 100+ broken `filepos`-based hyperlinks with readable and user-friendly footnote links (e.g. `#footnote-12`, `#backref-12`).
* Created bi-directional links for every footnote, allowing users to jump to the note and return seamlessly.
* Implemented regex-based search and replace for batch operations across multiple chapter files.
* Removed or cleaned up broken internal references caused by deleted or irrelevant content sections (e.g. table of contents).
* Ensured compliance with EPUB 2.0 structure standards using semantic HTML/XHTML tags and proper IDs.

---

### Before and After

| **Before Fix**                                                       | **After Fix**                                                             |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| `<a href="../Text/Section0004.xhtml#filepos109"><span>1]</span></a>` | `<a href="#footnote-1" id="backref-1">1</a>`                              |
| `<p>[<a href="#filepos109">1]</a> Some note text...</p>`             | `<p id="footnote-1">[1] Some note text... <a href="#backref-1">↩</a></p>` |

You can add screenshots of the EPUB in Calibre showing:

* The broken link behavior before
* The corrected, navigable footnotes after

---

### 📈 What I Learned

* How EPUB files are structured under the hood using XHTML.
* The practical application of **HTML and regex** for real-world document cleanup and data integrity.
* Debugging navigation-related issues in eBooks using Calibre’s editor and preview features.
* The importance of semantic structure in user experience (UX), especially in accessibility contexts like academic reading.
* How technical skills learned in BIS coursework can apply directly to digital content enhancement and publication workflows.

---

### Why This Matters in Business Information Systems

This project bridges BIS theory with hands-on practice:

* Working with **structured data** and **markup languages** (HTML/XHTML).
* Applying **user-centered thinking** to improve a product’s usability and readability.
* Demonstrating independent learning and initiative during academic downtime.

---

### 🚫 Disclaimer

This project was done solely for educational and personal learning purposes.
No copyrighted materials are uploaded to this repository.
Only code examples, structure notes, and project summaries are shared here.

---
