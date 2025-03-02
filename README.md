<!-- @credence-[/docs/introduction.html]-[Credence] -->

# Credence - markdown compiler for blogs & project Documentation 🚀  

**Credence** is a  **Markdown-powered** static site generator designed for **modern blogs and project documentation**. It integrates **the simplicity of Markdown and Tailwind CSS** to generate sites with minimal effort.  

## **Why Choose Credence?**  

✅ **Markdown-First** – Write Markdown, and let Credence handle the rest.  
✅ **Tailwind CSS Integration** – inbuilt tailwind css compiler. <br>
✅ **Ultra-Fast Builds** – Optimized for speed.  
✅ **Pluggable UI** – Use Tailwind, CSS, or custom themes—**your choice**.  
✅ **Live Reload & Watch Mode** – Instant preview while editing.
 
### **Get Started**    

```sh

npm i -g credence
mkdir my-blog
cd my-blog
credence
```
<br>
<br> 

**How Credence works** 🚀

#### Credence parses the credence headers on every text based files in your input folder, recursively to extracts md and html text.

**Parts of  a credence header**

@credence --- output file ---- page title

 syntax
 ```
/*@credence-[/index.html]-[Credence]
```

# Usage

### Using inline-docs (comments style)

```markdown
/**
 * @title   Add Function
 * @type    function
 * @description Adds two numbers and returns the result.
 * @tags    math, utility

 * @param {number} a The first number.
 * @param {number} b The second number.
 * @returns {number} The sum of `a` and `b`.
 */
function add(a, b) {
  return a + b;
}

```

```markdown
/*@credence-[/index.html]-[Credence]

### first clone the repo
  git clone credence
  ### running build command
  npm run build
*/
```


### Using md files (comment header)

```markdown
<!-- @credence-[/docs/introduction.html]-[documentation] -->

# Credence Command-Line Interface (CLI) Documentation

The **Credence CLI** is a robust tool designed to streamline and automate tasks associated with the Credence application suite. This document details its installation, usage, available commands, and developer guidelines.

## Table of Contents
```

### **About credence 🚀**  

1. **Markdown-Powered, But Smarter** 📝  
   - Unlike most static site generators, **Credence** doesn't just convert Markdown to HTML—it **understands context**.  
   - It allows **nested Markdown inside HTML elements**, solving limitations seen in other generators like Hugo and Docusaurus.  

2. **Tailwind, But on Your Terms** 🎨  
   - You’re not **forced** into Tailwind, but if you enable it, **Credence intelligently processes styles** while avoiding unnecessary bloat.  
   - It scans **Markdown, HTML, and even component files** to ensure only the needed styles make it into your final build.  

3. **Live Reload That Actually Works** 🔄  
   - Credence’s **watch mode** goes beyond just reloading pages—it can **retry connections**, detect stale caches, and ensure that **your development experience is smooth** even when working with large projects.  

4. **No More Ugly Typography** 🎭  
   - By default, **Credence applies optimized typography settings** so Markdown-based content looks **professional and polished** right out of the box.  
   - No need for **extra CSS** just to make text readable like in other generators.  

5. **Intelligent Asset Handling** 📦  
   - Automatically **copies, optimizes, and references assets** like images, fonts, and stylesheets, ensuring they’re efficiently bundled.  
   - Works even when running in a serverless environment or blob storage.  

6. **Code Highlighting That Feels Right** 💻  
   - Uses **highlight.js with custom themes**, ensuring code snippets are **visually pleasing and readable**.  

7. **CLI That Doesn’t Get in Your Way** 🛠️  
   - Runs in **zero-config mode** by default but lets **power users tweak every aspect** via an easy-to-use CLI.  
   - Supports **auto-detection of project structures**, so **you don’t have to manually set up folders** every time.  

8. **Fast, Even at Scale** ⚡  
   - **Batch processes file changes** to avoid unnecessary rebuilds.  
   - Can **handle thousands of Markdown files** without slowing down, making it a solid choice for **large-scale documentation**.  

9. **SEO & Accessibility Built-In** 🌍  
   - Generates **clean, semantic HTML** optimized for search engines.  

> Designed to be focused on **speed, developer experience, and flexibility**.  
 
 