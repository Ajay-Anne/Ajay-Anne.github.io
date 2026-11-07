# Personal portfolio

This is a static website for GitHub Pages. It uses plain HTML and CSS, so it does not need a build step or a package manager.

## Pages

- `index.html` — welcome statement and site overview
- `about.html` — biography
- `resume.html` — embedded and downloadable resume
- `goals.html` — career goals
- `projects/index.html` — project portfolio
- `projects/discovery-project.html` — Discovery Project feature

## Add your content

Replace the bracketed prompts and sample text with your own writing. Update the sample email address and any project details throughout the HTML files.

For the resume, add your PDF as `assets/files/resume.pdf`. The resume page uses that same file for its preview and download button.

The homepage portrait is loaded from `assets/css/ajay-anne.jpg`.

The About page has an elevator-pitch and education introduction with a placeholder for a casual portrait at `assets/css/about-casual.jpg`. Its “Beyond the classroom” section lists Violin, Scouting, then Quiz Bowl, with writing beside compact photo galleries. Scouting uses `assets/css/EagleProject1.JPG` and `assets/css/EagleProject2.JPG`; Violin uses `assets/css/violin.jpg` and `assets/css/violin2.jpg`. Quiz Bowl has photo placeholders; replace them with `<img>` elements when you add photos, and update the captions and alt text.

For the Discovery Project, replace the visual placeholder with at least one photo or visual that you took or created. Add a caption, complete the project details, and write at least 400 words across the project story. Address all five questions from your Discovery Project Showcase presentation.

The Projects page uses a clickable card with editable thumbnail, title, description, and month/year fields. Replace the Discovery Project card's thumbnail placeholder and bracketed text with your content. To add projects, duplicate the `<article>` card, update its details and link, and create its project page.

## Publish

In the repository’s GitHub settings, open **Pages** and select the `main` branch and `/ (root)` as the publishing source. Once Pages finishes deploying, the site is available at the repository’s GitHub Pages URL.
