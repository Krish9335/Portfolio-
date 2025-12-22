# Krishna Kumar Prajapati - Portfolio Website

## 📋 What's Included

1. **index.html** - Your complete portfolio website with:
   - Working contact form integrated with Formspree
   - Downloadable PDF resume
   - All your projects, experience, and skills
   - Responsive design with modern styling

2. **Krishna-Kumar-Prajapati-Resume.pdf** - Professional PDF resume

## 🚀 How to Use

### Option 1: Quick Start (Simplest)
1. Upload both files to any web hosting service (Netlify, Vercel, GitHub Pages, etc.)
2. The contact form will work immediately!

### Option 2: Local Testing
1. Open `index.html` in your browser
2. The website will work, but the contact form needs internet connection to send emails

## 📧 Contact Form Setup

### Current Configuration
The contact form is configured to send messages to: **krish9335280902@gmail.com**

I've set up the form using **Formspree** (a free email service). Here's how it works:

### How to Activate Your Contact Form:

1. **First Submission Verification** (One-time only):
   - When someone first submits the form, Formspree will send a verification email to `krish9335280902@gmail.com`
   - Click the verification link in that email
   - After verification, all future messages will be sent directly to your inbox

2. **That's it!** The form will now work permanently.

### Form Features:
- ✅ Validates email addresses
- ✅ Prevents spam
- ✅ Shows success/error messages
- ✅ Works without any backend code
- ✅ Free for up to 50 submissions per month

### Alternative: Use Your Own Formspree Account (Optional)

If you want more control or higher limits:

1. Go to https://formspree.io
2. Sign up with your email
3. Create a new form
4. Copy your unique form endpoint (looks like: `https://formspree.io/f/xxxxxxxx`)
5. In `index.html`, find this line (around line 1198):
   ```html
   <form action="https://formspree.io/f/xdkoeoqa" method="POST">
   ```
6. Replace `xdkoeoqa` with your unique form ID

## 📱 Testing the Contact Form

To test if the form works:
1. Open `index.html` in a browser
2. Scroll to the Contact section
3. Fill out all fields
4. Click "Send message"
5. You should see: "✓ Message sent successfully!"
6. Check your email inbox for the message

## 🌐 Deploying Your Website

### Recommended: Netlify (Easiest & Free)
1. Go to https://www.netlify.com
2. Drag and drop the folder containing your files
3. Done! Your site is live with a free URL

### Alternative: GitHub Pages
1. Create a GitHub repository
2. Upload both files
3. Go to Settings > Pages
4. Enable GitHub Pages
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Alternative: Vercel
1. Go to https://vercel.com
2. Import your project
3. Deploy with one click

## 📝 Customization Tips

### Update Your Resume:
1. Edit the PDF or recreate it
2. Replace `Krishna-Kumar-Prajapati-Resume.pdf`
3. Keep the same filename, or update line 1140 in `index.html`

### Update Contact Information:
- Email: Line 1231
- LinkedIn: Multiple locations (search for "linkedin.com/in/krishna")
- GitHub: Multiple locations (search for "github.com/Krish9335")

### Change Colors:
The website uses a green accent color (#22c55e). To change:
1. Search for `#22c55e` in the CSS
2. Replace with your preferred color

## 🔧 Troubleshooting

**Form not working?**
- Check your internet connection
- Make sure you verified the Formspree email
- Check browser console for errors (F12)

**Resume not downloading?**
- Make sure both files are in the same folder
- Check the file path in the HTML

**Email not arriving?**
- Check spam folder
- Verify Formspree form is activated
- Try testing with a different email address

## 📊 Contact Form Statistics

With the free Formspree plan:
- 50 submissions per month
- Email notifications
- Spam protection
- Export submissions as CSV

Need more? Upgrade to Formspree paid plan for unlimited submissions.

## 🎯 Next Steps

1. ✅ Upload files to your hosting
2. ✅ Test the contact form
3. ✅ Verify your email when first message arrives
4. ✅ Share your portfolio URL!

## 💡 Pro Tips

- Add Google Analytics to track visitors
- Update your projects regularly
- Keep your resume current
- Add more social media links
- Consider adding a blog section

## 📬 Support

If you have any questions or need help:
- Email: krish9335280902@gmail.com
- LinkedIn: https://linkedin.com/in/krishna-kumar-prajapati-9a9327355
- GitHub: https://github.com/Krish9335

---

**Good luck with your data science career! 🚀**
