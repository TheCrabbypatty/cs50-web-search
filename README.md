# CS50 Web: Search

A front-end web application that mimics the aesthetic and core functionality of Google Search, Google Image Search, and Google Advanced Search. Built as part of Harvard's CS50’s Web Programming with Python and JavaScript course.

## 🚀 Live Demo
* https://youtu.be/dB-YpJSZA6Y
---

## ✨ Features

### 1. Google Search Page
* **Core Search**: Query text and get redirected straight to Google's official results.
* **Centered Design**: Features a clean, centered search bar with rounded corners.
* **Search Buttons**: Includes "Google Search" and "I'm Feeling Lucky" buttons perfectly aligned beneath the input.
* **"I'm Feeling Lucky"**: Bypasses the normal results page to take you directly to the first search result (including handling Google's redirect notice).

### 2. Google Image Search Page
* **Image Querying**: Dedicated page to search strictly for visual content.
* **Navigation Link**: A subtle button in the upper-right corner seamlessly toggles between standard Search and Image Search.

### 3. Google Advanced Search Page
* **Four-Field Criteria**: Search using specific filters:
  * Find pages with *all these words*
  * Find pages with *this exact word or phrase*
  * Find pages with *any of these words*
  * Find pages with *none of these words*
* **Stacked Layout**: Aligning with Google's design, the four options are stacked vertically, left-aligned.
* **Consistent Styling**: The final submit button is styled in blue text with a white background, matching Google's own layout rules.

---

## 🛠️ Tech Stack

* **HTML5**: Structured semantic layout for all three search pages.
* **CSS3**: Custom styles implementing Flexbox/Grid to match Google's layout, fonts, margins, hover behaviors, and button graphics.

---

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Navigate into the project folder:**
   ```bash
   cd search
   ```
3. **Open the project:**
   * Double-click `index.html` to open it in your default web browser.
   * Alternatively, use the **Live Server** extension in VS Code.

---

## 🎓 Specification Requirements Met
* **Links**: Upper right navigation links properly route between the three main views.
* **Behavior**: Search fields match the official Google query parameters (`q`, `as_q`, `as_epq`, `as_oq`, `as_eq`).
* **Aesthetics**: Replicated Google's CSS style rules closely, including button shapes, colors, and font treatments.
