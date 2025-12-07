---
marp: true
title: Product Documentation Presentation
author: Sameer Shah
theme: custom-tech
paginate: true
footer: "22f1000091@ds.study.iitm.ac.in"
---

<!-- _class: lead -->
# Product Documentation  
### Using Marp for Version-Control-Friendly Docs

**Author:** Sameer Shah  
**Email:** 22f1000091@ds.study.iitm.ac.in

---

<!-- _class: lead -->
# Why Marp for Documentation?

- Markdown-based  
- Version control friendly  
- Export to **PDF, PPTX, HTML, PNG**
- Custom themes + automation

---

<!-- Custom theme applied via inline CSS -->
<style>
section {
  background-color: #f5f7fa;
  color: #222;
  font-family: "Segoe UI", sans-serif;
}

h1, h2, h3 {
  color: #0057b7;
}

code {
  background: #eef;
  padding: 4px 6px;
  border-radius: 6px;
}

section {
  font-size: calc(1vw + 1vh + 0.3vmin);
}
</style>

# Custom Theme (Inline Specification)

This presentation uses a theme named **custom-tech**, defined directly using CSS above.

---

<!-- _backgroundColor: #002244 -->
<!-- _color: white -->

# Slide With Custom Styling 🎨

This slide explicitly uses Marp directives to set:

- Background color  
- Text color  

✔️ This ensures Marp detects directives properly.

---

# Mathematical Equations

Example of algorithmic complexity:

Inline:  
The time complexity is $O(n \log n)$.

Block:

$$
T(n) = T\left(\frac{n}{2}\right) + n
$$

---

<!-- Background image example -->
![bg cover](https://images.unsplash.com/photo-1451187580459-43490279c0fa?auto=format&fit=crop&w=1920&q=80)

# Slide With Background Image

This slide demonstrates a **full-cover background image** using:  
`![bg cover](images/background.jpg)`

---

# Code Example

```python
def add_record(record):
    db.append(record)
    return True
