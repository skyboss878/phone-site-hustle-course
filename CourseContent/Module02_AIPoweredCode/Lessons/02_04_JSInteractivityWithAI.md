**[VIDEO INTRO - Energetic, dynamic music. Graphics showing elements moving, forms submitting, and pop-ups appearing. You look engaging and excited.]**

Welcome back, Phone Site Hustlers! We've covered HTML (structure) and CSS (style). Now, let's add the **spark and brains to your websites: JavaScript!** JavaScript is the programming language that makes websites interactive, dynamic, and responsive to user actions.

Think of it this way: HTML is the building, CSS is the interior design, and JavaScript is the electricity, the moving parts, and the security systems that make the building *function*. And guess what? AI is your electrician, making complex JavaScript simple!

---

### **What is JavaScript?**

* JavaScript (JS) is a scripting language that runs primarily in web browsers.
* It allows you to manipulate HTML and CSS, respond to user clicks, validate forms, fetch data from servers, and much more.
* It's what makes web applications feel alive.

---

### **Key JavaScript Concepts AI Can Help With**

Don't worry about writing complex JS from scratch. Focus on *what* you want to achieve, and AI will give you the code.

1.  **Interacting with HTML (DOM Manipulation):**
    * JS can find (select) any HTML element on a page and change its content, style, or attributes.
    * **AI Prompt Example:** "Write JavaScript to change the text of an `<h1>` element with the ID 'main-title' to 'Welcome Back!'"

2.  **Responding to Events:**
    * JS can listen for things users do (clicks, typing, hovering) and then execute code.
    * **AI Prompt Example:** "Generate JavaScript to show an alert box that says 'Button Clicked!' when a button with the ID 'myButton' is clicked."

3.  **Variables & Data:**
    * JS can store information in variables (e.g., a user's name, a count).
    * **AI Prompt Example:** "Write JavaScript to store the number 10 in a variable called `score` and then print it to the console."

4.  **Conditions (`if/else` statements):**
    * JS can make decisions based on whether something is true or false.
    * **AI Prompt Example:** "Generate a JavaScript `if` statement that checks if a variable `age` is greater than or equal to 18 and prints 'Adult' to the console, otherwise prints 'Minor'."

5.  **Loops:**
    * JS can repeat actions multiple times.
    * **AI Prompt Example:** "Write a JavaScript `for` loop that prints numbers from 1 to 5 to the console."

6.  **Functions:**
    * Blocks of reusable code that perform a specific task.
    * **AI Prompt Example:** "Create a JavaScript function called `greetUser` that takes a `name` as an argument and prints 'Hello, [name]!' to the console."

---

### **Adding JavaScript to Your HTML (The `<script>` Tag)**

For our simple projects, you'll put your JavaScript inside a `<script>` tag. It's generally best practice to place this *just before the closing `</body>` tag*. This ensures all your HTML is loaded before JavaScript tries to interact with it.

**Let's add some interactivity to your `my_first_landing_page.html`.**

**Action: Open Gemini (or your chosen AI). Use this prompt:**

"I have this HTML structure for a landing page with two buttons.
[Paste the relevant HTML for your buttons here, e.g., `<div class="buttons"> <button id="button1">Learn More</button> <button id="button2">Sign Up</button> </div>`]
Generate JavaScript that does the following:
1.  When 'button1' is clicked, change the `<h1>` text to 'Thanks for learning more!'
2.  When 'button2' is clicked, change the `<h1>` text to 'Get Started Now!'
3.  Provide only the JavaScript code, suitable for placement in a `<script>` tag at the end of the HTML body."

**Review & Integrate:**
1.  Copy the JavaScript code AI provides.
2.  Open your `my_first_landing_page.html` file in your `Scratchpad` directory using `nano`:
    ```bash
    cd ~/phone-site-hustle-course/Scratchpad
    nano my_first_landing_page.html
    ```
3.  **Paste the JavaScript code** just before the closing `</body>` tag, like this:
    ```html
    <body>
        <script>
            /* PASTE YOUR AI-GENERATED JAVASCRIPT HERE */
        </script>
    </body>
    </html>
    ```
4.  Save (`Ctrl+O`, Enter) and exit (`Ctrl+X`).

Now, open `my_first_landing_page.html` in your phone's browser again. Click the buttons and watch the `<h1>` text change! You've just added dynamic interactivity to your page, all powered by AI.

**[VIDEO OUTRO - Dynamic, functional music. Text overlay: "JAVASCRIPT: THE BRAINS. NEXT: Responsive Design with AI!"]**
