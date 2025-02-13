# My Portfolio Website ✨

A Personal Portfolio Website built using HTML, CSS, and JavaScript. It showcases my skills, projects, and contact information in a professional, user-friendly design, supporting light and dark modes.

# 🚀Features

Home Page: A welcoming section introducing myself.

About Page: Detailed information about me, my journey, and my interests.

Skills Page: A showcase of my technical and professional skills.

Projects Page: Highlights of my completed and ongoing projects.

Contact Page: An easy way to get in touch with me.

Dark/Light Mode: Switch between dark and light themes for better usability.

# 🛠️ Technologies Used

HTML: For structuring the website.

CSS: For styling and creating a visually appealing design.

JavaScript: For interactive elements like theme switching and dynamic content.


# How to Run the Project Locally
Step 1: Open your terminal or command prompt.

Step 2: Navigate to your project folder:

Step 3:
```bash
cd path/to/your/project
```

Step 4: Initialize a Git repository:
```bash
git init
```

Step 5: Add all files to the staging area:
```bash
git add .
```

Step 6: Commit the files:
```bash
git commit -m "Initial commit"
```

Step 7: Link your local repository to GitHub:
```bash
 git remote add origin https://github.com/your-username/your-repo-
name.git
```
(Replace your-username and your-repo-name accordingly.)

Step 8: Push the files to GitHub:
```bash
git push -u origin main
```



# Challenges Faced & How You Overcame Them
1. CSS Not Loading Properly

Issue: Styles were not applied when viewing the site in the browser.
Solution:

- Checked if the CSS file path was correct and used relative paths

```bash
<link rel="stylesheet" href="style.css">
```

- Ensured the CSS file was saved and correctly linked in index.html.


# 2. JavaScript Not Working

Issue: JavaScript functions weren’t executing properly.

Solution:

Opened DevTools (F12 → Console) to check for errors.

Used console.log() to debug.

Ensured the script was properly linked in index.html:

```bash
<script src="script.js"></script>
```

- Placed the script before closing the <body> tag or used defer to ensure it loads after the page:

```bash
<script src="script.js" defer></script>
```

# 3. Images or Links Not Showing
Issue: Images or links were broken when viewed on GitHub Pages.

Solution:

Used relative paths instead of absolute paths. Example:

```bash
<img src="assets/images/profile.jpg" alt="Profile">
```

# 4. GitHub Pages Not Updating
Issue: After making changes and pushing updates, the website didn’t reflect the latest version.

Solution:

Cleared the browser cache (Ctrl + Shift + R or Cmd + Shift + R on Mac).

Made sure all changes were committed and pushed.

```bash
git add .
git commit -m "Updated portfolio"
git push origin main
```

Verified that GitHub Pages was enabled in the repository settings


# 🚀 Live Demo

https://nusha825.github.io/E2E-Portfolio/

# 👩‍💻 Author

Nusha AGF
