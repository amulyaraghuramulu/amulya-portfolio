# Portfolio Setup Guide

This guide will help you set up your portfolio with a fully functional contact form backend.

## 🚀 Quick Start

### Step 1: Setup Backend

1. **Navigate to backend folder:**
   ```bash
   cd backend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment:**
   ```bash
   cp env.example .env
   ```

4. **Edit `.env` file with your Gmail credentials:**
   ```env
   EMAIL_USER=your-email@gmail.com
   EMAIL_APP_PASSWORD=your-gmail-app-password
   OWNER_EMAIL=amulyaraghuramulu@gmail.com
   FRONTEND_URL=http://localhost:3000
   PORT=3001
   ```

5. **Get Gmail App Password:**
   - Go to [Google Account Security](https://myaccount.google.com/security)
   - Enable 2-Factor Authentication
   - Generate App Password for "Mail"
   - Use this password in your `.env` file

6. **Start the backend server:**
   ```bash
   npm run dev
   ```

### Step 2: Test Your Setup

1. **Open your portfolio in browser:** `index.html`
2. **Fill out the contact form and submit**
3. **Check your email for the submission**

## 📁 Project Structure

```
Portfolio/
├── index.html              # Main portfolio page
├── styles.css              # Styling
├── script.js               # Frontend JavaScript
├── profile-photo.jpeg      # Profile image
├── backend/                # Backend service
│   ├── server.js           # Express server
│   ├── package.json        # Dependencies
│   ├── env.example         # Environment template
│   └── README.md           # Backend documentation
└── setup.md                # This file
```

## 🎯 What You Get

### Frontend Features:
- ✅ Responsive design
- ✅ Modern animations
- ✅ Professional layout
- ✅ Contact form with validation
- ✅ Social media links
- ✅ Mobile-friendly navigation

### Backend Features:
- ✅ Email notifications to you
- ✅ Auto-reply emails to visitors
- ✅ Form validation and security
- ✅ Rate limiting
- ✅ Professional email templates

## 🚀 Deployment

### Frontend Deployment (Free options):
- **Netlify**: Drag and drop your files
- **Vercel**: Connect your GitHub repo
- **GitHub Pages**: Enable in repository settings

### Backend Deployment:
- **Heroku**: Free tier available
- **Railway**: Modern deployment platform
- **Vercel**: Serverless functions
- **DigitalOcean**: App Platform

## 🔧 Customization

### Update Personal Information:
1. **Name and title** in `index.html`
2. **Email and phone** in contact section
3. **Social media links**
4. **Profile photo** (replace `profile-photo.jpeg`)
5. **Resume/CV** (replace `AmulyaPR.pdf`)

### Styling:
- Edit `styles.css` to change colors, fonts, layout
- All CSS custom properties are at the top of the file

### Add More Sections:
- Follow the existing HTML structure
- Add corresponding CSS styles
- Update navigation menu

## 🆘 Troubleshooting

### Common Issues:

1. **Contact form not working:**
   - Check backend server is running
   - Verify CORS settings
   - Check browser console for errors

2. **Emails not sending:**
   - Verify Gmail App Password
   - Check environment variables
   - Look at server logs

3. **Styling issues:**
   - Check CSS file path
   - Verify all classes are applied correctly

### Getting Help:
- Check the `backend/README.md` for detailed backend setup
- Review browser console for JavaScript errors
- Check server logs for backend issues

## 📱 Testing

### Frontend Testing:
- Test on different screen sizes
- Check all navigation links
- Verify form validation

### Backend Testing:
```bash
# Test API endpoint
curl -X POST http://localhost:3001/api/contact \
  -H "Content-Type: application/json" \
  -d '{
    "name": "Test User",
    "email": "test@example.com", 
    "subject": "Test",
    "message": "Testing the contact form"
  }'
```

## 🎉 You're Ready!

Your portfolio is now ready with:
- Professional design
- Functional contact form
- Email notifications
- Mobile responsiveness
- Modern animations

Update the content with your information and deploy to share with the world! 