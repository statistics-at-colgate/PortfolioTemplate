# Setting up GitHub Pages

Go to [github.com](https://github.com). Follow [these instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site), which I outline below:

1. Click 'New'
2. Make sure your username is listed as the owner under "General."
3. Use yourusername.github.io as the Repository name. For example, in a test, I used `statistics-at-colgate.github.io` because statistics-at-colgate is our GitHub classroom username.\
**Note**: You must use all lowercase letters, even if your name has uppercase letters.
4. Add a short description. Something like "A website for my statistics work at Colgate University."
5. Make sure visibility is set to "Public".
6. We won't be using a template, so "No template" should be selected for "Start with a template".
7. Turn the "add README" option on.
8. No need for a .gitignore or a license.
9. Click "Create repository"

At this point, you will be brought to your new repository. It should be empty, except for the `README.md` file we told GitHub to create. Click "Code", copy the HTTPS link, and download the repository in Positron.

Try accessing https://yourusername.github.io, you should see your README.

# Pointing GitHub Pages to Your Portfolio

Now, we need to configure the repository to store and publish your website.
1. Use `quarto::quarto_render()` to compile your portfolio website project.
2. Commit all of your portfolio files to your GitHub Repository.
3. Go to [github.com](https://github.com) and access your portfolio repository.
4. Click "Settings". 
5. Click "Pages" in the left navigation bar. 
6. Under the "Branch" menu, select the "main" branch and the `/docs` folder. Click "Save".\
**Note**: If you don't see the `/docs` folder option in the dropdown, it means you haven't rendered your project or pushed the `/docs` folder to GitHub yet.

# Quick Notes

`index.qmd` is the home page

`about.qmd` is the about me page

`_quarto.qmd` is the "brain" of your page. You can link other projects there. As an example, we included and example.qmd project, which is linked in the sidebar menu.
