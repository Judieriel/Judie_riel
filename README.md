# Gabriel Judith — Data Portfolio

A personal portfolio site showcasing data analysis case studies, starting with a Telecom Customer Churn & Revenue Analysis built in Excel.

## Files
- `index.html` — homepage / project list
- `project-telecom.html` — full case study for the telecom churn project
- `assets/` — put your dashboard screenshot here (e.g. `assets/dashboard.png`)

## How to add your dashboard screenshot
1. Save your Excel dashboard as an image (Export/Screenshot → PNG).
2. Name it `dashboard.png` and place it in the `assets` folder.
3. Open `project-telecom.html`, find the section that says:
   ```html
   <div class="dash-placeholder">...</div>
   ```
4. Replace it with:
   ```html
   <img src="assets/dashboard.png" alt="Telecom churn dashboard">
   ```

## How to publish this on GitHub Pages (free hosting)

1. **Create a GitHub account** at github.com if you don't have one yet.
2. **Create a new repository**:
   - Click the "+" icon (top right) → "New repository"
   - Name it exactly: `your-username.github.io` (replace `your-username` with your actual GitHub username — this exact naming makes it your main portfolio URL)
   - Set it to **Public**
   - Click "Create repository"
3. **Upload these files**:
   - On the repo page, click "Add file" → "Upload files"
   - Drag in `index.html`, `project-telecom.html`, and the `assets` folder
   - Click "Commit changes"
4. **Turn on GitHub Pages**:
   - Go to repo **Settings** → **Pages** (left sidebar)
   - Under "Source", select the `main` branch and `/ (root)` folder
   - Click **Save**
5. **Visit your site**:
   - After a minute or two, your site will be live at:
     `https://your-username.github.io`

## Adding more projects later
Copy `project-telecom.html`, rename it (e.g. `project-yourname.html`), edit the content, then add a new project card in `index.html` linking to it.

## Contact
gabrielugonnajudith@gmail.com
