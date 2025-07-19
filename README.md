# 🚀 Amulya PR - Portfolio Website

> Modern, responsive portfolio website with serverless contact form functionality.

![Portfolio Preview](frontend/assets/profile-photo.jpeg)

## ✨ Features

- 📱 **Responsive Design** - Looks great on all devices
- 🎨 **Modern UI/UX** - Clean, professional interface
- 📧 **Contact Form** - Serverless email functionality via Vercel
- ⚡ **Fast Loading** - Optimized for performance
- 🔒 **Secure** - Built-in form validation and rate limiting

## 🏗️ Project Structure

```
Portfolio/
├── 📁 frontend/                 # Client-side code
│   ├── index.html              # Main HTML file
│   ├── styles.css              # Stylesheet
│   ├── script.js               # JavaScript functionality
│   └── assets/                 # Images and documents
│       ├── profile-photo.jpeg  # Profile image
│       ├── profile-photo-hd.jpeg
│       └── AmulyaPR.pdf        # Resume
├── 📁 api/                     # Serverless functions
│   └── contact.js              # Contact form handler
├── 📁 docs/                    # Documentation
│   └── setup.md                # Setup instructions
├── package.json                # Dependencies
├── vercel.json                 # Vercel configuration
├── .gitignore                  # Git ignore rules
└── README.md                   # This file
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Vercel account
- Gmail account (for contact form)

### Local Development
```bash
# Clone the repository
git clone https://github.com/amulyaraghuramulu/amulyapr.git

# Install dependencies
npm install

# Start development server
vercel dev
```

### Production Deployment
```bash
# Deploy to Vercel
vercel --prod
```

## 🔧 Configuration

### Environment Variables
Set these in your Vercel dashboard:

```env
EMAIL_USER=your-gmail@gmail.com
EMAIL_APP_PASSWORD=your-gmail-app-password
OWNER_EMAIL=where-emails-should-go@gmail.com
```

### Gmail Setup
1. Enable 2-Factor Authentication
2. Generate App Password for Mail
3. Use App Password (not regular password)

## 🎯 Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Vercel Serverless Functions
- **Email:** Nodemailer + Gmail SMTP
- **Deployment:** Vercel
- **Version Control:** Git + GitHub

## 📧 Contact Form Features

- ✅ Real-time form validation
- ✅ Spam protection (rate limiting)
- ✅ Professional email templates
- ✅ Auto-reply functionality (optional)
- ✅ Secure credential handling

## 🌐 Live Demo

**Portfolio:** [https://amulyaraghuramulu.github.io/amulyapr/](https://amulyaraghuramulu.github.io/amulyapr/)

## 👨‍💻 About

**Amulya PR** - Web Application Developer  
📧 amulyaraghuramulu@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/amulya-pr) | [GitHub](https://github.com/amulyaraghuramulu)

## 📄 License

MIT License - feel free to use this project for your own portfolio!

---

⭐ **Star this repo if it helped you!**

