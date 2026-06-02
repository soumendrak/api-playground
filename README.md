<p align="center">
  <img src="https://raw.githubusercontent.com/soumendrak/api-playground/main/logo.svg" alt="API Playground" width="120" />
</p>

<h1 align="center">API Playground</h1>

<p align="center">A mini Postman-like API client that runs entirely in your browser.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Zero_Dependencies-0b0?style=flat" alt="Zero Dependencies" />
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat" alt="License: MIT" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat" alt="PRs Welcome" />
</p>

## Overview

API Playground is a lightweight, single-file HTTP client for testing REST APIs. Enter a URL, choose a method, add headers and a body, and send the request — all from your browser. Save frequently used requests as collections in localStorage for quick access.

Built with zero external dependencies — just vanilla HTML, CSS, and JavaScript.

## Features

| Feature | Description |
|---|---|
| **All HTTP Methods** | GET, POST, PUT, DELETE, PATCH, HEAD, OPTIONS |
| **Custom Headers** | Add, edit, and remove request headers dynamically |
| **Request Body** | Full text body support for POST/PUT/PATCH |
| **Response Viewer** | Status code with color coding, response headers, formatted body |
| **JSON Pretty-Print** | Auto-formats JSON responses for readability |
| **Collections** | Save named requests to localStorage, load with one click |
| **Keyboard Shortcut** | Ctrl+Enter to send request |
| **Dark Theme** | Easy on the eyes with orange accents |

## Quick Start

1. Open `index.html` in any modern browser
2. Enter an API URL (e.g., `https://jsonplaceholder.typicode.com/posts/1`)
3. Choose a method and click **Send**
4. Save frequent requests using the **Save Current** button

No build step, no server, no dependencies.

## Project Structure

```
api-playground/
└── index.html    # The entire application
```

## License

MIT — see [LICENSE](LICENSE)
