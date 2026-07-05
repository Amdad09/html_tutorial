# 🌍 Module 1 — The Birth of the Web & HTML

> **Course:** HTML: From Beginner to Frontend Engineer

---

# 📖 What You Will Learn

After completing this module, you will understand:

* What is the Internet?
* What is the World Wide Web (WWW)?
* Why HTML was created.
* Who created HTML.
* What HyperText means.
* What Markup means.
* Why HTML is **not** a programming language.
* What HTML actually does.
* The relationship between HTML, CSS, and JavaScript.
* How a browser reads an HTML file.

---

# 🌍 Module 1 — Internet & World Wide Web (WWW)

> **Course:** HTML: From Beginner to Frontend Engineer

---

# 📖 Learning Objectives

After completing this chapter, you should be able to:

* Explain what the Internet is.
* Explain what the World Wide Web (WWW) is.
* Differentiate between the Internet and the Web.
* Understand the relationship between the Internet, WWW, Websites, Web Pages, and HTML.

---

# 🌐 What is the Internet?

## Definition

The **Internet** is a global network that connects millions of computers, servers, mobile devices, and networks around the world so they can communicate and exchange data.

It is often called a **Network of Networks** because many smaller networks are connected together.

---

## Simple Example

Imagine every university, bank, company, and home has its own network.

When all of these networks connect together, they form the **Internet**.

```text
Network
   +
Network
   +
Network
   =
Internet
```

---

## Main Components of the Internet

* Computers
* Servers
* Routers
* Internet Service Providers (ISP)
* Fiber Optic Cables
* Wireless Networks

---

## How Internet Works (Simplified)

```text
Server
   │
   ▼
Internet
   │
   ▼
ISP
   │
   ▼
Router
   │
   ▼
Your Computer
```

When you visit a website, data travels through this network in just a few milliseconds.

---

## ISP (Internet Service Provider)

An ISP is a company that provides Internet access.

Examples in Bangladesh include:

* Link3
* BDCOM
* Amber IT
* Carnival Internet

Without an ISP, you cannot connect to the Internet.

---

# 🌐 What is the World Wide Web (WWW)?

## Definition

The **World Wide Web (WWW)** is an information system built on top of the Internet that allows users to access linked web pages using a web browser.

The Web is **not** the Internet.

It is one of the most popular services that runs on the Internet.

---

## Who Invented the WWW?

**Tim Berners-Lee**

While working at **CERN**, he introduced:

* HTML
* HTTP
* The World Wide Web
* The first Web Browser
* The first Web Server

---

## Why Was the Web Created?

The Internet already existed.

However, there was no simple way to connect documents together.

Tim Berners-Lee solved this problem by introducing **HyperText**, allowing one document to link to another.

This idea became the foundation of the World Wide Web.

---

# 🌍 Website vs Web Page

## Website

A website is a collection of related web pages.

Example:

```text
Amazon Website

├── Home
├── Products
├── About
├── Contact
└── Login
```

---

## Web Page

A web page is a single page within a website.

Examples:

* Home Page
* Contact Page
* Product Details Page

Most web pages are built using HTML.

---

# 🌍 Internet vs World Wide Web

| Internet                   | World Wide Web            |
| -------------------------- | ------------------------- |
| Global Network             | Information System        |
| Connects Computers         | Connects Web Pages        |
| Infrastructure             | Service                   |
| Uses Routers, ISPs, Cables | Uses HTML, HTTP, Browsers |
| Can exist without the Web  | Depends on the Internet   |

---

# 🌍 Relationship

```text
Internet
      │
      ▼
World Wide Web (WWW)
      │
      ▼
Website
      │
      ▼
Web Page
      │
      ▼
HTML
```

---

# 🎤 Interview Questions

### What is the Internet?

A global network that connects millions of computers and networks worldwide.

---

### Why is the Internet called the "Network of Networks"?

Because it is formed by connecting many smaller networks together.

---

### What is the World Wide Web?

An information system built on top of the Internet that allows users to access linked web pages.

---

### Is the Internet the same as the World Wide Web?

No.

The Internet is the global network infrastructure.

The World Wide Web is a service that runs on the Internet.

---

### Who invented the World Wide Web?

Tim Berners-Lee.

---

### What is a Website?

A collection of related web pages.

---

### What is a Web Page?

A single page within a website.

---

# 📝 Quick Revision

```text
Internet
│
├── Global Network
├── Network of Networks
├── Uses ISP
├── Connects Devices
└── Infrastructure

↓

World Wide Web
│
├── Runs on the Internet
├── Created by Tim Berners-Lee
├── Uses HTML
├── Contains Websites
└── Websites contain Web Pages
```

---

# 💡 Key Takeaways

* The Internet and the World Wide Web are **not** the same.
* The Internet is the communication infrastructure.
* The Web is an information system that runs on the Internet.
* Websites are made of multiple web pages.
* HTML is the language used to structure web pages.
---------

# 🌍 Before HTML

Imagine the year **1989**.

There was no:

* Facebook
* Google
* YouTube
* GitHub

Computers already existed, and the Internet also existed.

However, there was a major problem.

Scientists and researchers could not easily share information with each other.

Different computers stored documents in different ways, and finding related documents was difficult.

---

# ❓ The Problem

People had information.

But they didn't have an easy way to **connect** and **share** documents.

Imagine reading one research paper and wanting to open another related paper instantly.

That wasn't easy.

---

# 👨‍💻 Who Solved This Problem?

**Tim Berners-Lee**

He was working at **CERN**, a European research laboratory.

His idea was simple:

> "What if one document could directly link to another document?"

That idea completely changed the world.

---

# 🌐 What is HyperText?

HyperText means:

> Text that contains links to other documents or web pages.

Example:

```
Page A
   │
   ▼
Page B
   │
   ▼
Page C
```

Today, every website uses this idea.

Whenever you click a link and move to another page, you are using **HyperText**.

---

# 🏷 What is Markup?

Markup means adding information that tells the browser what each piece of content represents.

For example:

```html
<h1>Welcome</h1>
```

The browser understands:

> This is a Heading.

Another example:

```html
<p>Hello World</p>
```

The browser understands:

> This is a Paragraph.

HTML doesn't describe how something should look.

It describes **what it is**.

---

# 📚 HTML Full Form

**HTML = HyperText Markup Language**

| Word      | Meaning                                      |
| --------- | -------------------------------------------- |
| HyperText | Connected documents through links            |
| Markup    | Describing the meaning of content using tags |
| Language  | A language with its own syntax and rules     |

---

# ❌ Is HTML a Programming Language?

**No.**

HTML is a **Markup Language**, not a Programming Language.

---

## Why?

Programming languages have features like:

* Variables
* Functions
* Loops
* Conditions

HTML has none of these.

HTML only describes the structure of a webpage.

Example:

```html
<h1>Hello</h1>
```

HTML tells the browser:

> This is a heading.

It does **not** perform calculations or make decisions.

---

# 🎯 What is HTML Used For?

HTML creates the **structure** of a webpage.

Think of building a house.

Before painting or decorating, you first build:

* Foundation
* Walls
* Doors
* Windows

Similarly, HTML builds the structure of a webpage.

For example:

* Header
* Navigation
* Main Content
* Footer

---

# 🎨 HTML vs CSS vs JavaScript

| Technology | Responsibility         |
| ---------- | ---------------------- |
| HTML       | Structure              |
| CSS        | Design & Styling       |
| JavaScript | Behavior & Interaction |

Think of a human body:

* HTML → Skeleton
* CSS → Clothes & Appearance
* JavaScript → Brain & Movement

---

# 🌐 How Does a Browser Read HTML?

When you open an HTML file, the browser follows a simple process.

```
HTML File
      │
      ▼
Read HTML
      │
      ▼
Understand Tags
      │
      ▼
Create Page Structure
      │
      ▼
Display the Web Page
```

Later in this course, you will learn this process in much greater depth when studying the DOM and Browser Rendering.

---

# 💼 Real Project Example

Suppose you are building a Restaurant Website.

### HTML

* Header
* Navigation
* Menu
* Food List
* Footer

### CSS

* Colors
* Fonts
* Layout
* Animations

### JavaScript

* Order Button
* Search
* Shopping Cart
* Payment

Each technology has a different responsibility.

---

# 🚫 Common Misconceptions

### ❌ HTML is a programming language.

Wrong.

HTML is a markup language.

---

### ❌ HTML creates complete websites.

Wrong.

HTML creates only the structure.

A complete website usually requires:

* HTML
* CSS
* JavaScript
* Backend
* Database

---

# 💡 Senior Engineer Note

A beginner usually says:

> HTML is HyperText Markup Language.

A professional frontend engineer explains:

> HTML is a language that communicates the meaning and structure of content to the browser. The browser then interprets that structure and renders a webpage.

Understanding **why HTML exists** is far more valuable than simply memorizing its full form.

---

# 🎤 Interview Questions

### 1. What is HTML?

HTML is a markup language used to create the structure of web pages.

---

### 2. What does HTML stand for?

HyperText Markup Language.

---

### 3. Who invented HTML?

Tim Berners-Lee.

---

### 4. Where was HTML invented?

At CERN.

---

### 5. Is HTML a programming language?

No.

It is a markup language.

---

### 6. What is HyperText?

Text that contains links to other documents or web pages.

---

### 7. What is Markup?

Markup is a way of describing the meaning and structure of content using tags.

---

### 8. What is the main purpose of HTML?

To define the structure of a webpage.

---

# 📝 Summary

* HTML was created to make information sharing easier.
* Tim Berners-Lee invented HTML at CERN.
* HTML stands for HyperText Markup Language.
* HTML is **not** a programming language.
* HTML defines the structure of a webpage.
* CSS styles the webpage.
* JavaScript adds behavior and interactivity.
* Browsers read HTML tags to understand the structure of a page.

---

# 🚀 Quick Revision

```
HTML
│
├── Structure
├── Markup Language
├── HyperText
├── Tim Berners-Lee
├── CERN
├── Not a Programming Language
├── Browser Reads Tags
└── Foundation of Every Web Page
```
