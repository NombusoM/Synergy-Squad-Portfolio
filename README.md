# Team Portfolio Website

A collaborative portfolio website project for learning HTML, CSS, JavaScript, and Git/GitHub workflows.

## 📁 Project Structure

```
ss-portfolio/
└── src/
│   ├── index.html
│   ├── Nombuso.html
│   ├── contact.html
│   ├── script.js
│   ├── styles/                   ← Stlyes folder
│   │   ├── global.css            ← Base styles, reset, typography
│   │   ├── navbar.css            ← Navbar styles
│   │   ├── home.css              ← Homepage specific (hero, team cards, tech stack)
│   │   ├── profile.css           ← Profile page styles
│   │   └── contact.css           ← Contact form styles
│   └── assets/
│       ├── icons/
│       │   ├── csharp.svg
│       │   ├── css.svg
│       │   ├── dotnet.svg
│       │   ├── html.svg
│       │   ├── javascript.svg
│       │   ├── python.svg
│       │   ├── rstudio.svg
│       │   ├── sas.svg
│       │   └── sql.svg
│       └── images/
│          ├── letho.jpg
│          ├── mpumi.jpg
│          ├── nombuso.jpg
│          ├── placeholder1.jpg
│          ├── sam.jpg
│          └── thando.jpg
│    
└── README.md                       ← This file
```

## 🚀 Getting Started

### 1. Initial Setup (Team Leader - Nombuso) THIS STEP HAS BEEN COMPLETED

```Git Bash/ Windows Powershell/ Visual Studio Code Terminal
# Create a new repository on GitHub
# Clone it to your computer
git clone https://github.com/NombusoM/Synergy-Squad-Portfolio.git
cd Synergy-Squad-Portfolio

# Add all the starter files
# Commit and push
git add .
git commit -m "Initial project setup"
git push origin main
```

### 2. Team Members Join THIS IS WHERE YOU START

```Git Bash/ Windows Powershell/ Visual Studio Code Terminal
# Each team member clones the repository
git clone https://github.com/NombusoM/Synergy-Squad-Portfolio.git
cd Synergy-Squad-Portfolio
```

## 👥 Task Distribution

### Nombuso: Profile Page THIS HAS BEEN COMPLETED --SKIP
- Copy `Nombuso.html` as your starting point
- Create a branch: `git checkout -b profiles/nombuso-profile`
- Customize your profile page with:
  - Your photo (or placeholder)
  - About me section
  - Skills
  - Projects
- Commit and push your changes
- Create a Pull Request on GitHub

### Member 2,3.4,5: Profile Page THIS IS THE STEP YOU COMPLETE
- Copy `Nombuso.html` and rename to `Your name.html`
- Create a branch: `git checkout -b profiles/Your name-profile`
- Follow same steps as the Nombuso.html step - editing it and adding your information
- Update navigation links to include your page



## 🔄 On Git Workflow FOLLOW THESE STEPS TO SAVE ON GIT HUB LOCAL AND REMOTELY AFTER YOUR FINISHED EDITING YOUR PROFILE

### Creating a Feature Branch
```bash
# Make sure you're on main and it's up to date
git checkout main
git pull origin main

# Create your feature branch
git checkout -b feature/your-feature-name
```

### Making Changes
```bash
# After making changes
git add .
git commit -m "Description of what you changed"
git push origin feature/your-feature-name
```

### Creating a Pull Request
1. Go to the repository on GitHub
2. Click "Pull Requests" → "New Pull Request"
3. Select your branch
4. Add a description of your changes
5. Request review from team members
6. Wait for approval, then merge

### Keeping Your Branch Updated
```bash
# Get latest changes from main
git checkout main
git pull origin main

# Update your feature branch
git checkout feature/your-feature-name
git merge main
```


### Additional Tasks (can be divided) THIS WILL BE COMPLETED AT THE END -
- **Homepage Enhancement**: Improve the team section on `index.html`
- **Contact Form**: Add email validation or styling improvements
- **Styling**: Add more CSS animations or effects
- **JavaScript**: Add interactive features (dark mode, animations, etc.)

## 🎨 Customization Guide

### Changing Colors
Edit `styles.css` and look for these color variables:
- Primary: `#667eea` (purple)
- Secondary: `#3498db` (blue)
- Dark: `#2c3e50` (navy)

### Adding Your Photo
Replace the Nombuso image URL in your HTML:
```html
<img src="path/to/your-photo.jpg" alt="Your Name">
```

### Adding More Team Members
1. Copy `member1.html` to `memberX.html`
2. Add a link in the navigation of ALL pages
3. Add a card on `index.html` homepage

## 📝 Best Practices

### Commit Messages
- ✅ Good: "Add profile photo and update bio section"
- ❌ Bad: "changes"

### Branch Names
- ✅ Good: `profile/yourname-profile`, `fix/contact-form-bug`
- ❌ Bad: `my-branch`, `test`

### Before Pushing
1. Test your changes in a browser
2. Check for console errors (F12 → Console)
3. Make sure all links work
4. Verify responsive design (mobile view)

## 🐛 Common Issues

### Merge Conflicts
If you get a merge conflict:
1. Open the conflicting file
2. Look for `<<<<<<<`, `=======`, `>>>>>>>`
3. Choose which version to keep
4. Remove the conflict markers
5. Commit the resolved file

### Can't Push
```bash
# If you get "rejected" error
git pull origin main
# Resolve any conflicts
git push origin your-branch-name
```

## 🎯 Learning Goals

- [ ] Basic HTML structure
- [ ] CSS styling and layouts
- [ ] JavaScript DOM manipulation
- [ ] Git branching and merging
- [ ] Pull Request workflow
- [ ] Code review process
- [ ] Team collaboration

## 📚 Resources

- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

## 🤝 Team Communication

- Review each other's Pull Requests
- Leave constructive comments
- Ask questions if something is unclear
- Help each other debug issues

## 📞 Need Help?

- Create an issue on GitHub
- Ask in your team chat
- Check the Resources section above

---

**Happy Coding! 🚀**
