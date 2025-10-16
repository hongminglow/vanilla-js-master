This repository is a small tutorial and showcase that demonstrates how to build a simple, production-minded web app using only plain (vanilla) JavaScript, HTML, and CSS.

What you'll find here
- A focused example application that implements common web app patterns without any frameworks: templating with <template>, client-side routing, a small cart, data fetching from a local JSON file, and a service worker for offline support.
- Minimal, readable code that you can study and adapt for your own projects.

Why use vanilla JavaScript sometimes
- Smaller footprint: no large framework bundles — faster initial load and simpler deployment.
- Full control: you see exactly what the app does and can optimize only the parts you need.
- Easier to learn and debug: the language and browser APIs are the source of truth, so problems are often easier to trace.
- Great for small to medium apps or when you want to progressively enhance an existing site.

How to run it locally (quick)
1. Serve the folder over HTTP (do not open the files with the file:// protocol). For example, with Python 3:

	python -m http.server 8000

2. Open http://localhost:8000/ in your browser.

Notes
- Service workers require a secure context — localhost is fine for development.
- This repo intentionally avoids external libraries: use it as a learning reference or a starting point for small projects.

Enjoy exploring how a modern web app can be built with the web platform itself.
