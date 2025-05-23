# django-tailwind
**Blazing-fast Django + Tailwind CSS v4 Starter**  
Pre-configured for custom fonts, static files, and JIT. Skip setup—clone and code! Perfect for tutorials &amp; rapid prototyping.

## Features
- 🐍 Django 5.0+ ready
- 🎨 Tailwind CSS v4 (Oxide engine)
- ✨ Custom font setup (self-hosted + Google Fonts)
- 📦 Minimal dependencies

## Quick Start
```bash
git clone https://github.com/ak-boateng/djangotailwind.git
cd djangotailwind
npm install && python -m venv venv
source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt  # Add Django if needed
npx tailwindcss -i ./static/css/styles.css -o ./static/css/output.css --watch
