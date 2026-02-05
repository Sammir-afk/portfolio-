# Technical Writer Portfolio

A professional portfolio website showcasing technical writing expertise, experience, and projects.

## 🌐 Live Demo

This portfolio is designed to be hosted on GitHub Pages. Once deployed, it will be available at:
`https://yourusername.github.io/portfolio`

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Portfolio Showcase**: Display your documentation projects and work samples
- **Skills Section**: Highlight your technical writing tools and competencies
- **Experience Timeline**: Visual timeline of your professional journey
- **Contact Section**: Easy ways for potential employers to reach you

## 🚀 Quick Start - Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository: `portfolio` (or any name you prefer)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Your Portfolio Files

1. Download the `index.html` file from this portfolio
2. In your new GitHub repository, click **Add file** → **Upload files**
3. Drag and drop the `index.html` file
4. Scroll down and click **Commit changes**

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** (top menu)
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/ (root)**
5. Click **Save**

### Step 4: Access Your Live Portfolio

After a few minutes, your portfolio will be live at:
- `https://yourusername.github.io/portfolio`

GitHub will show you the exact URL in the Pages settings.

## 🎨 Customization

### Update Your Information

Open `index.html` and customize these sections:

1. **Contact Information** (lines ~600-620):
   ```html
   <a href="mailto:your.email@example.com" class="contact-link">
   ```
   Replace with your actual email address

2. **GitHub Link**:
   ```html
   <a href="https://github.com/yourusername" class="contact-link">
   ```
   Replace `yourusername` with your GitHub username

3. **LinkedIn Link**:
   ```html
   <a href="https://linkedin.com/in/yourprofile" class="contact-link">
   ```
   Replace `yourprofile` with your LinkedIn profile URL

4. **Footer Link**:
   ```html
   <a href="https://github.com/yourusername/portfolio">
   ```
   Update with your actual repository URL

### Modify Content

- **About Section**: Update the description to match your experience
- **Portfolio Projects**: Customize the project cards with your actual work
- **Skills**: Add or remove skills based on your expertise
- **Experience**: Update the timeline with your actual work history
- **Stats**: Change the numbers to reflect your achievements

### Change Colors

The color scheme is defined at the top of the CSS (lines 9-17):

```css
:root {
    --primary: #0F172A;      /* Main dark color */
    --accent: #F97316;       /* Orange accent */
    --bg: #FAFAF9;          /* Background */
}
```

## 📱 Responsive Design

The portfolio automatically adapts to different screen sizes:
- **Desktop**: Full layout with side-by-side timeline
- **Tablet**: Optimized spacing and layout
- **Mobile**: Stacked layout with simplified timeline

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations
- **JavaScript**: Smooth scrolling and scroll animations
- **Google Fonts**: Fraunces, Instrument Sans, IBM Plex Mono

## 📄 File Structure

```
portfolio/
├── index.html          # Main portfolio page
└── README.md          # Documentation (this file)
```

## 🔧 Local Development

To test your portfolio locally before deploying:

1. Download the `index.html` file
2. Open it in your web browser
3. Make edits in a text editor
4. Refresh the browser to see changes

## 💡 Tips for Success

1. **Add Screenshots**: Consider adding actual screenshots of your documentation work
2. **Link to Live Docs**: If possible, link to live documentation you've created
3. **Keep It Updated**: Regularly update your portfolio with new projects
4. **Optimize for SEO**: Update the page title and add meta descriptions
5. **Add Analytics**: Consider adding Google Analytics to track visitors

## 🤝 Need Help?

If you encounter issues:
- Check [GitHub Pages documentation](https://docs.github.com/en/pages)
- Ensure your repository is set to Public
- Verify the branch and folder settings in Pages configuration
- Wait a few minutes after enabling Pages for the site to build

## 📜 License

This portfolio template is free to use and modify for your personal portfolio.

---

**Ready to deploy?** Follow the Quick Start guide above and have your portfolio live in minutes!
