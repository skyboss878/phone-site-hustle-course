**[VIDEO INTRO - Artistic, flowing music. Graphics showing colors, fonts, and layouts transforming a bland page into a beautiful one. You look creative and inspiring.]**

Welcome back, Phone Site Hustlers! If HTML is the skeleton of your webpage, then **CSS (Cascading Style Sheets)** is the skin, hair, clothes, and makeup! CSS is what makes your website beautiful, defining its colors, fonts, spacing, layout, and overall visual appeal.

Just like with HTML, you don't need to become a CSS expert overnight. Your AI co-pilot will be invaluable in generating the styles you need.

---

### **What is CSS?**

* CSS is a styling language. It tells the browser *how* to display HTML elements.
* You write CSS rules that target specific HTML elements and apply properties (like `color`, `font-size`, `margin`).
* Example: `p { color: blue; font-size: 16px; }` would make all paragraphs blue and 16 pixels tall.

---

### **Key CSS Concepts & Properties You'll Use**

Focus on what these concepts *do*, and let AI handle the exact syntax.

1.  **Selectors:**
    * How you target HTML elements to style them.
    * **Element Selector:** `h1 { ... }` (targets all `<h1>` elements)
    * **Class Selector:** `.my-class { ... }` (targets elements with `class="my-class"`)
    * **ID Selector:** `#my-id { ... }` (targets a unique element with `id="my-id"`)
    * **AI Prompt Example:** "Write CSS to target all buttons with a class of `primary-btn`."

2.  **Colors:**
    * `color`: For text color.
    * `background-color`: For element background.
    * Can use names (red), hex codes (`#FF0000`), RGB (`rgb(255,0,0)`), or HSL.
    * **AI Prompt Example:** "Generate CSS to make the background color of the header section light blue."

3.  **Text Styling (Fonts):**
    * `font-family`: The font style (e.g., Arial, 'Open Sans').
    * `font-size`: How big the text is (e.g., `16px`, `1.2em`).
    * `font-weight`: Boldness (e.g., `normal`, `bold`, `700`).
    * `text-align`: Alignment (`left`, `center`, `right`).
    * **AI Prompt Example:** "Write CSS to center the main heading and make its font size 36 pixels."

4.  **Box Model (Spacing & Layout):**
    * Every HTML element is a "box." Understanding this is key to layout.
    * **`margin`:** Space *outside* the box (pushes other elements away).
    * **`padding`:** Space *inside* the box (space between content and border).
    * **`border`:** A line around the box.
    * **AI Prompt Example:** "Add CSS to give a `div` 20 pixels of padding and a 5-pixel solid gray border."

5.  **Flexbox & Grid (Advanced Layout - AI's Superpower Here!):**
    * Modern CSS techniques for arranging elements on a page. These can be complex manually, but AI makes them easy!
    * **AI Prompt Example:** "Using Flexbox, arrange three `div` elements horizontally with equal spacing between them."

---

### **Adding CSS to Your HTML (The `<style>` Tag)**

For small projects and quick testing, you can put your CSS directly into your HTML file within a `<style>` tag, typically in the `<head>` section.

**Let's style the `my_first_landing_page.html` you created in the last lesson.**

**Action: Open Gemini (or your chosen AI). Use this prompt:**

"I have this HTML code for a simple landing page [paste your HTML code from 02_02 here].
Now, generate modern CSS to:
* Set a sans-serif font for the entire body.
* Make the `<h1>` a bold, dark blue, centered, and 48px font size.
* Make the `<p>` text light gray and centered.
* Style the two `<button>` elements with a background color of vibrant green, white text, 10px padding, no border, and slightly rounded corners (5px radius). Add a little space between them.
* Provide only the CSS code. Ensure it works within a `<style>` tag in the HTML head."

**Review & Integrate:**
1.  Copy the CSS code AI provides.
2.  Open your `my_first_landing_page.html` file in your `Scratchpad` directory using `nano`:
    ```bash
    cd ~/phone-site-hustle-course/Scratchpad
    nano my_first_landing_page.html
    ```
3.  **Find the `<head>` section** of your HTML.
4.  **Paste the CSS code** just before the closing `</head>` tag, like this:
    ```html
    <head>
        <title>My Page Title</title>
        <style>
            /* PASTE YOUR AI-GENERATED CSS HERE */
        </style>
    </head>
    ```
5.  Save (`Ctrl+O`, Enter) and exit (`Ctrl+X`).

Now, open `my_first_landing_page.html` in your phone's browser again. You'll see a dramatic difference! Your page now has structure *and* style, all with AI's help.

**[VIDEO OUTRO - Creative, polished music. Text overlay: "CSS: THE BEAUTY. NEXT: JavaScript Interactivity with AI!"]**
