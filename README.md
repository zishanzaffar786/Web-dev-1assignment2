# Personal Portfolio Website

**ZISHAN ZAFFAR** is a **B.Tech Computer Science Engineering (CSE)** core student specializing in **Web Development**. This project is a personal portfolio website designed to showcase web development skills, completed projects, a comprehensive contact form, and social media connectivity.

##  Features

*   **Fixed Navigation & Back-to-Top**: Features a sticky header header with absolute-positioned links for easy page navigation, along with a globally fixed `^ Back to Top` button.
*   **Smooth Scrolling**: Enabled native smooth-scroll behaviors across section anchors (`#about`, `#skills`, `#project`, `#form`).
*   **Modern Interactive Components**: 
    *   A structured **Web Development Skills** matrix table.
    *   A complete **Contact & Feedback Form** equipped with data pattern validations, checkboxes, dropdowns, and form action triggers.
*   **Responsive Styling**: Features custom-themed container layouts matching a professional navy blue (`#013a63`) color scheme.

---

##  Tech Stack & Skills

The repository incorporates vanilla frontend languages structured as follows:

| Skill | Experience Level | Description / Implementation |
| :--- | :--- | :--- |
| **HTML** | Intermediate | Semantic blocks (`<header>`, `<main>`, `<footer>`), structured tables, nested label inputs, forms, and custom accessibility attributes. |
| **CSS** | Beginner | Position configurations (`sticky`, `absolute`, `fixed`), border radiuses, element centering, and customized structural themes. |
| **JAVASCRIPT** | Learning | Planned integrations for dynamic input manipulation and form event listeners. |

---

##  Form Validations & Constraints

The customized feedback form strictly enforces data sanitization and strict browser constraints natively:
*   **Name**: Limited exclusively to alphabetical characters using regular expression pattern validation (`[A-Z a-z]+`).
*   **Password**: Enforced string length constraint matching a `minlength="6"` and `maxlength="10"` criteria.
*   **Date of Birth**: Restricted strictly between the years **2000-01-01** and **2026-09-18**.
*   **Contact Number**: Native telephone pattern matching requiring a length of exactly 10 digits starting with numbers 6-9 (`[6-9]{1}[0-9]{9}`).
*   **Terms**: Mandatory compliance required before submission (`required` field constraint).

---

##  Project Structure

```text
├── index.html   # Main structural markup page holding portfolio context and form blocks
└── style.css    # Layout rules, element positioning offsets, and dark navy branding
```

---

##  Connected Platforms

The footer houses quick-redirect nodes built to link out safely (`target="_blank"`) to official networks:
*   **Instagram** (`@zishan_zaffarx`)
*   **Facebook**
*   **Snapchat**
*   **LinkedIn**
