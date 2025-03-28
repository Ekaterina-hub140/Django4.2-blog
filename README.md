
# Django Blog with Authentication & Social Features

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2-green)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-purple)](https://getbootstrap.com/)

A full-featured blogging platform with modern authentication, post interactions, and responsive design.

![Blog Screenshot](https://via.placeholder.com/800x400?text=Django+Blog+Screenshot) <!-- Replace with actual screenshot -->

## ✨ Key Features

### 🛠 Core Functionality
- **User Authentication** (Register/Login/Password Reset)
- **CRUD Blog Posts** with rich text and images
- **Comments System** with threaded replies
- **AJAX-powered Likes** (no page reload)
- **Search & Pagination**

### 🚀 Technical Highlights
- **Django Class-Based Views**
- **PostgreSQL-ready** architecture
- **Crispy Forms** with Bootstrap 5
- **Pillow** for image processing
- **Production-grade** email configuration

## 🛠 Installation

### Prerequisites
- Python 3.7+
- PostgreSQL (or SQLite for development)

```bash
# Clone repository
git clone https://github.com/Ekaterina-hub140/Django-blog.git
cd Django-blog

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env with your settings
