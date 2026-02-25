# EasyFolio CV Setup Guide

## Welcome! 🎉
Your portfolio template has been optimized for use as a professional CV. Here's what was updated and how to customize it with your information.

---

## ✨ Key Improvements Made

### 1. **Content Updates**
- ✅ Updated hero section targeted at Web Developers & Technical Support Engineers
- ✅ Replaced generic placeholder text with professional CV-focused content
- ✅ Rewrote About section to emphasize professional expertise
- ✅ Updated Skills section with relevant tech skills (JavaScript, React, Backend, Technical Support)
- ✅ Refreshed Resume with developer-focused work experience and education
- ✅ Optimized Portfolio section for code/app projects
- ✅ Updated Services section to highlight developer offerings
- ✅ Changed FAQ section to developer-relevant questions

### 2. **New Features**
- ✅ **Download CV Button** - Floating button appears when scrolling (automatically becomes visible after scrolling down)
- ✅ **Print as PDF** - Click the button to print/save your portfolio as PDF
- ✅ **Print Optimization** - Special CSS rules ensure clean PDF output
- ✅ **Better Mobile Responsiveness** - Optimized for all devices

### 3. **Visual Enhancements**
- ✅ Improved professional card styling with hover effects
- ✅ Enhanced typography for better readability
- ✅ Better spacing and layout organization
- ✅ Consistent professional color scheme

---

## 📝 What to Update Next

### **In index.html:**

#### Hero Section (Line ~120)
- Your name/title in the "Web Developer & Technical Support Engineer" heading
- Update the professional summary in the `<p class="lead">` tag
- Adjust the stats to reflect your actual experience (5+ years, 30+ projects, etc.)

#### About Section (Line ~200)
- **Name**: Change "Your Name" in the About content
- **Phone**: Update with your actual phone number
- **Location**: Add your city and country
- **Email**: Replace with your email address
- **Experience**: Update years of experience
- **Expertise**: Update your main technical expertise area

#### Skills Section (Line ~330)
- Update the 4 skill boxes with your main skills
- Adjust percentages to match your proficiency level
- Update descriptions for each skill

#### Work Experience (Line ~430)
- Replace placeholder company names with your actual employers
- Update job titles and dates
- Modify descriptions and bullet points to match your actual experience
- Remove/add timeline items as needed

#### Education (Line ~500)
- Add your university/college name
- Update graduation year
- List relevant certifications and courses

#### Portfolio Section (Line ~600)
- Replace portfolio project descriptions with your actual projects
- Update project images (replace the .webp files in `assets/img/portfolio/`)
- Change project categories and technologies used

#### Contact Section (Line ~950)
- Update email address
- Add your phone number
- Update your location
- Ensure the contact form is working (currently posts to `forms/contact.php`)

### **Profile Images:**
1. **Hero image**: Replace `assets/img/profile/image.png` with your professional photo
2. **About section image**: Replace `assets/img/profile/profile-square-2.webp`
3. **Portfolio images**: Update the `.webp` files in `assets/img/portfolio/`

### **Optional Updates:**
- Customize colors in `assets/css/main.css` (lines 24-36) by updating CSS variables
- Update the favicon in `assets/img/favicon.png` and `apple-touch-icon.png`
- Remove the "Dropdown" menu from navigation if not needed

---

## 🎨 Customization Tips

### **Colors**
Edit the color variables in `assets/css/main.css` (around line 24):
```css
:root { 
  --background-color: #ffffff;
  --default-color: #0a0f14;
  --heading-color: #0f2943;
  --accent-color: #e87532;  /* Your brand color */
  ...
}
```

### **Fonts**
Change fonts by updating the Google Fonts imports in `index.html` (line ~18)

### **Social Links**
Update header and footer social links in `index.html`:
- Twitter/X
- Facebook
- Instagram
- LinkedIn

---

## 📱 Testing Your CV

### **On Desktop:**
1. Open `index.html` in your browser
2. Scroll down and click the "Download CV" button
3. Use browser's print dialog to save as PDF
4. Adjust print settings if needed

### **On Mobile:**
- Test responsive design by viewing on phone/tablet
- All sections should stack nicely on smaller screens

### **Print Quality:**
- Print background graphics are optimized
- Navigation and footer hide automatically when printing
- Clean, professional layout for PDF output

---

## 🚀 Going Live

### **Option 1: GitHub Pages (Free)**
1. Create a GitHub repository
2. Push your files to the repo
3. Enable GitHub Pages in repository settings
4. Your CV is live at `https://username.github.io/repo-name`

### **Option 2: Custom Domain**
- Use services like Netlify, Vercel, or traditional hosting
- Point your domain to your hosted files

### **Option 3: Self-Hosted**
- Upload files to your own web server
- Ensure `forms/contact.php` is properly configured for your server

---

## 📧 Contact Form Setup

The contact form (`forms/contact.php`) requires:
1. A mail server configured on your hosting
2. Update the recipient email in `forms/contact.php`
3. Test the form functionality before going live

*Note: The form won't work on GitHub Pages (static hosting only)*

---

## 🔧 Troubleshooting

### **Download button not appearing?**
- Make sure you've scrolled down at least 300px
- Check browser console for JavaScript errors
- Verify `assets/js/main.js` is loading correctly

### **Images not showing?**
- Check file paths in `index.html`
- Ensure image files exist in `assets/img/` folder
- Use relative paths, not absolute URLs

### **Form not sending emails?**
- Verify your hosting supports PHP
- Check `forms/contact.php` configuration
- Test with a form testing service if needed

---

## 💡 Pro Tips

1. **Keep it updated**: Regularly update your projects and experience
2. **Use high-quality images**: Professional photos make a difference
3. **Mobile-first**: Most recruiters browse on mobile devices
4. **SEO**: Add meta descriptions and keywords in `<head>` section
5. **Analytics**: Add Google Analytics to track visitor stats

---

## 📞 Need Help?

- Check the original template docs: https://bootstrapmade.com/
- Bootstrap documentation: https://getbootstrap.com/
- Common CSS customizations are in `assets/css/main.css`

---

## Happy Customizing! 🎊

Your portfolio is now ready to showcase your skills and experience. Good luck with your job search or client acquisition!

**Last updated:** February 24, 2026
