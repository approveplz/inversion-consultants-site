# Inversion Consultants Website

A modern, professional website for Inversion Consultants built with HTML, CSS, and vanilla JavaScript.

## Features

- Responsive design that works on all devices
- Modern, professional styling
- Contact form integration (Google Forms)
- Fast loading and lightweight
- SEO-friendly structure

## EASY DEPLOYMENT STEPS (5 minutes total)

### Step 1: Deploy to Netlify
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop your entire project folder onto the page
3. Your site will be live instantly at a temporary URL like `amazing-site-123.netlify.app`

### Step 2: Connect Your Custom Domain
1. In your Netlify dashboard, click "Domain settings"
2. Click "Add custom domain" 
3. Enter: `inversionconsultants.com`
4. Netlify will show you DNS records to add

### Step 3: Update Your Domain DNS (at your registrar)
Add these records where you bought your domain:
```
Type: A
Name: @
Value: 75.2.60.5

Type: CNAME  
Name: www
Value: [your-netlify-url].netlify.app
```

### Step 4: Set Up Contact Form
1. Go to [Google Forms](https://forms.google.com)
2. Create a new form with fields: Name, Email, Company, Message
3. Click "Send" → "Embed HTML" → Copy the form ID
4. Replace `YOUR_FORM_ID_HERE` in `index.html` with your form ID
5. Re-upload the updated file to Netlify (drag & drop again)

**That's it!** Your site will be live at www.inversionconsultants.com in ~10 minutes.

## File Structure

```
├── index.html          # Main HTML file
├── style.css           # All styling
└── README.md          # This file
```

## Customization

- Update company information in `index.html`
- Modify colors and styling in `style.css`
- Replace placeholder contact information
- Add your actual Google Form embed code

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)