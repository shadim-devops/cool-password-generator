# OneFile Password Generator

A secure, offline password generator implemented as a single HTML file.

The application runs entirely in the browser, requires no build step, and can be deployed directly to GitHub Pages or served via Nginx.

## Features

- Cryptographically secure password generation (Web Crypto API)
- Configurable length and number of passwords
- Optional character classes (lowercase, uppercase, digits, symbols)
- Exclusion of ambiguous characters
- Entropy-based strength indicator
- Pronounceable password mode
- Works fully offline

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Docker
- Nginx

## Run with Docker

Build the image:

```bash
docker build -t onefile-password-generator .
