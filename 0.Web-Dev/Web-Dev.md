# 🌐 WEB DEVELOPMENT · WEEK 01 · DAY 01

## Your first step into the web

> **Today's mission**  
> Understand what happens when you visit a website, meet the parts of a web application, and build your first webpage with HTML.

| 🎯 Learn | 🧭 Explore | 🛠️ Build |
| --- | --- | --- |
| Web fundamentals | Frontend and backend | A simple HTML portfolio |

## Lesson map

| # | Stop | What you'll discover |
| :---: | --- | --- |
| 01 | [The web](#1--the-web) | Internet, World Wide Web, browser, and server |
| 02 | [Web app parts](#2--web-app-parts) | Frontend, backend, and the three frontend building blocks |
| 03 | [HTML basics](#3--html-basics) | Elements, tags, and attributes |

---

## 1 · The web

Web development is the process of creating and maintaining websites and web applications. Examples include online shops, social platforms, educational websites, and banking applications.

When you enter a web address in your browser, the browser requests a resource from a server. The server responds, and the browser displays the webpage.

### Internet and World Wide Web

| Internet | World Wide Web (WWW) |
| --- | --- |
| A global network connecting computers and devices. | A collection of webpages accessed through the Internet. |
| Provides the infrastructure for communication. | Uses browsers and web addresses. |

> **Remember:** The Internet is the network. The Web is one service that runs on it.

### The browser-server journey

```text
USER
  ↓
BROWSER ── HTTP / HTTPS request ──→ SERVER
BROWSER ←──────── response ───────── SERVER
  ↓
WEBPAGE DISPLAYED
```

| Term | Meaning |
| --- | --- |
| **HTTP** | Hypertext Transfer Protocol |
| **HTTPS** | Secure HTTP communication |
| **URL** | Uniform Resource Locator; tells the browser where to find a resource |

### Parts of a URL

For `https://www.example.com/about`:

| Part | Example | Meaning |
| --- | --- | --- |
| Protocol | `https` | The communication protocol |
| Domain | `www.example.com` | The website's domain |
| Path | `/about` | The requested location on the website |

## 2 · Web app parts

| Frontend | Backend |
| --- | --- |
| The part people see and interact with. | Handles application logic and data. |
| Examples: buttons, forms, images, layouts, and navigation. | Examples: authentication, APIs, and database operations. |

```text
USER → FRONTEND → BACKEND → DATABASE
```

A **full-stack developer** works with both frontend and backend.

### The frontend's three building blocks

| Technology | Responsibility |
| --- | --- |
| **HTML** | Structure |
| **CSS** | Styling |
| **JavaScript** | Behaviour |

For a button, HTML creates it, CSS changes its appearance, and JavaScript makes it respond to a click. This guide focuses on web fundamentals and introductory HTML; CSS styling and JavaScript behaviour are covered in their own learning sections.

### Get ready to build

You'll need:

- Visual Studio Code
- A web browser (Chrome is recommended in the lesson)
- A project folder

Create a folder with an `index.html` file:

```text
my-first-website/
└── index.html
```

Open the project folder in Visual Studio Code.

## 3 · HTML basics

**HTML** stands for **HyperText Markup Language**. It structures webpages and defines content such as headings, paragraphs, images, and links. HTML is a markup language, not a programming language.

## Day 1 recap

You explored the Internet and World Wide Web, the browser-server request and response, URLs, frontend and backend, and HTML's role in a webpage. You also practised basic HTML elements, attributes, document structure, and browser Developer Tools.

**Next lesson:** HTML forms, tables, and an introduction to CSS.

> Keep practising: build, experiment, inspect, and understand what happens in the browser.
