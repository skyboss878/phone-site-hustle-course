**[VIDEO INTRO - Clear, instructional music. Graphics showing blocks assembling, skeleton structures, and HTML tags highlighting. You look focused and practical.]**

Welcome back, Phone Site Hustlers! In our last lesson, you got your first taste of AI code generation. Now, we're going to dive into the **foundation of every website: HTML**. Think of HTML as the *structure* or *skeleton* of your webpage. It defines what content is there – headings, paragraphs, images, links – but not how it looks.

The best part? You'll learn HTML concepts rapidly by having your AI co-pilot do the heavy lifting of writing the actual code!

---

### **What is HTML? (HyperText Markup Language)**

* HTML uses "tags" (e.g., `<p>`, `<h1>`, `<a>`) to mark up different parts of content.
* These tags tell the web browser what each piece of text or media is (e.g., a paragraph, a main heading, a link).
* Every webpage you visit is built with HTML.

---

### **Key HTML Elements You'll Use Constantly**

Don't try to memorize every tag. Focus on understanding these core elements, and AI will handle the syntax.

1.  **`<h1>` to `<h6>` (Headings):**
    * Defines titles and subtitles. `<h1>` is the most important (main title), `<h6>` the least.
    * **AI Prompt Example:** "Generate an `<h1>` tag that says 'My Awesome Phone Site'."

2.  **`<p>` (Paragraph):**
    * For blocks of text.
    * **AI Prompt Example:** "Create a `<p>` tag with placeholder text about web design."

3.  **`<a>` (Anchor - for links):**
    * Creates hyperlinks to other pages or websites. Uses the `href` attribute.
    * **AI Prompt Example:** "Give me an `<a>` tag that links to `https://google.com` with the text 'Visit Google'."

4.  **`<img>` (Image):**
    * Embeds images. Requires a `src` (source) attribute (the image's URL) and `alt` (alternative text for accessibility).
    * **AI Prompt Example:** "Generate an `<img>` tag for an image at `images/logo.png` with alt text 'Company Logo'."

5.  **`<div>` (Division) & `<section>` (Section):**
    * Generic container elements used to group other HTML elements together. Essential for layout.
    * `<div>` is more generic, `<section>` implies a thematic grouping.
    * **AI Prompt Example:** "Create a `<div>` that contains an `<h1>` and a `<p>`."

6.  **`<input>`, `<textarea>`, `<button>` (Form Elements):**
    * Used to create forms for user input.
    * **AI Prompt Example:** "Generate an HTML input field for email and a submit button."

---

### **Structuring a Basic Webpage with AI**

Every HTML page has a basic structure:

```html
<!DOCTYPE html>  <html lang="en"> <head>           <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Page Title</title> </head>
<body>           <h1>Hello, Phone Site Hustler!</h1>
    <p>This is my first paragraph.</p>
</body>
</html>
