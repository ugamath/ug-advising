# UG Advising Website (GitHub Pages)

## Files
- `index.html` — Home page
- `minor-specialization.html`
- `exams-grades-timetable.html`
- `documentation-course-admin.html`
- `ug-thesis.html`
- `other-matters.html`
- `form.html` — Query form (forwards to `uga.math@snu.edu.in` via FormSubmit)
- `thanks.html` — Optional thank-you page
- `style.css`

## Publish on GitHub Pages (Project site)
1. Create / open the repository: `ug-advising`.
2. Upload these files to the **root** of the repo (same level as `README.md`).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`)
   - Folder: **/(root)**
5. Save. GitHub will show your site URL (format: `https://<username>.github.io/ug-advising/`).

## Form setup note
The form uses FormSubmit (https://formsubmit.co/). The receiving mailbox may need to confirm/activate the form once.
To redirect to `thanks.html`, edit the `_next` hidden input in `form.html` and replace `YOUR_GITHUB_USERNAME` with your GitHub username.
