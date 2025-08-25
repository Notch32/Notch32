# How to Publish Your Portfolio (Step by Step)

## A) Profile README
1. Go to GitHub and create a **new repository** named **Notch32** (exactly your username).
2. Upload the file from `Notch32_Profile_README/README.md`.
3. Commit. Your profile page will now show this README.

## B) Portfolio Website (GitHub Pages - User Site)
1. Create another repository named **notch32.github.io** (all lowercase).
2. Upload the contents of the `notch32.github.io/` folder:
   - `index.html`
   - `style.css`
   - `Belal_Mohmed_CV_OnePage.pdf`
   - The entire `projects/` folder
3. Commit the files to the **main** branch.
4. Open the repo **Settings → Pages** and confirm that **Build and deployment** is set to **Deploy from a branch: main / root**.
5. After it finishes building, your site will be live at: **https://notch32.github.io**
6. Test the links:
   - The **Download CV** button should download your PDF.
   - The **Projects** links should open the markdown pages in the browser.

## C) Next Steps
- Add project screenshots to a new folder `assets/` and link them inside each `.md`.
- When you publish code for each project, create a new repo per project and add a link inside its markdown page.
- Keep your CV PDF in this repo updated when you make changes.
