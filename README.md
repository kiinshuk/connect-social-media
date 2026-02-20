# Connect - Django Social Media App (Work in Progress)

A social media platform built with Django. This project is under active development and I'm looking for collaborators to help add features!

## 🚀 Current Features

- ✅ User authentication (login/register/logout)
- ✅ User profiles with bio and profile pictures
- ✅ Create posts with images and captions
- ✅ Like/unlike posts
- ✅ Follow/unfollow users
- ✅ News feed showing posts from followed users
- ✅ Search users by username

## 🎯 Coming Soon / Looking for Help With

These are features I plan to add and would love help with:

- 🔴 **Real-time Chat** - Private messaging between users (WebSockets/Django Channels)
- 🔴 **Notifications** - When someone likes/follows/messages you
- 🔴 **Comments** - Comment on posts
- 🔴 **Stories** - 24-hour disappearing posts
- 🔴 **Hashtags** - Clickable hashtags in posts
- 🔴 **Image Filters** - Basic image editing before posting
- 🔴 **Dark Mode** - Theme toggle
- 🔴 **Performance Optimization** - Pagination, lazy loading
- 🔴 **Testing** - Unit tests for all features
- 🔴 **Deployment** - Deploy to production (AWS/Heroku/PythonAnywhere)

## 🛠️ Tech Stack

- **Backend**: Django 6.0.2
- **Frontend**: HTML, CSS, JavaScript, Tailwind CSS
- **Database**: SQLite (development)
- **Other**: Git, GitHub

## 📋 Prerequisites

- Python 3.12+
- pip
- Git

## 🔧 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/kiinshuk/connect-social-media.git
cd connect-social-media

# Create virtual environment
python -m venv venv

# Activate it
# Windows: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver