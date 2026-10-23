# Sprint 1 Plan — Student Management Portal

**Sprint duration:** 1 week  
**Sprint goal:** Build the initial static Student Management Portal and publish the source code in GitHub.

## Sprint backlog
1. Create the GitHub repository and README.
2. Prepare and prioritize the product backlog.
3. Create the project files and shared stylesheet.
4. Develop Home and About pages.
5. Develop Student Registration, Courses, and Contact pages.
6. Test page links, responsive layout, and browser form validation.
7. Commit and push all files to GitHub.

## Definition of Done
- All five required HTML pages are available.
- Navigation works between all pages.
- Pages use HTML5 semantic structure and a shared CSS stylesheet.
- Form fields have labels and basic browser validation.
- Changes are committed and pushed to GitHub.
- Static form limitation is documented.

## Example branch and commit workflow
```bash
git checkout -b feature/home-about-pages
git add index.html about.html style.css
git commit -m "Add home and about pages"
git push -u origin feature/home-about-pages

git checkout -b feature/forms-courses-contact
git add registration.html courses.html contact.html
git commit -m "Add registration courses and contact pages"
git push -u origin feature/forms-courses-contact
```

After reviewing the branches on GitHub, merge them into `main` using pull requests, or use the workflow required by your instructor.
