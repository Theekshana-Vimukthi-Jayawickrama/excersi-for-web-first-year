# Bootstrap Practical 01

Five separate HTML exercises and three lab pages based on the supplied Bootstrap practical and lab sheet. No build tool is needed.

## Install Bootstrap

Open a terminal in this project folder and run:

```powershell
node --version
npm --version
npm install
```

If Node.js or npm is unavailable, install Node.js LTS and reopen the terminal. If PowerShell blocks `npm.ps1`, use `npm.cmd` instead of `npm` for the commands above.

## Open the project

Open `index.html` with VS Code's Live Server, or open it directly in a browser after installation. Serve this project folder as the root so that `node_modules` is accessible.

All nine HTML pages already reference the local Bootstrap files:

```html
<link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
<script src="node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"></script>
```

The npm package files are included. Run `npm install` after cloning to download Bootstrap. No internet connection is needed to view the pages afterwards.

## Files

| File | Exercise |
| --- | --- |
| `index.html` | Home page with links to all exercises |
| `exercise-01.html` | Basic container with a main heading |
| `exercise-02.html` | Heading and paragraph inside one container |
| `exercise-03.html` | Light background, dark text and padding |
| `exercise-04.html` | Blue full-width container with white text |
| `exercise-05.html` | Two containers with different background colors |
| `q1.html` | Centered blue heading and green button |
| `q2.html` | Styled responsive and full-width containers |
| `q3.html` | Student Web Workshop with three colored sections |

Each exercise preserves the text, heading level and Bootstrap classes in the practical. Navigation is separate from the exercise content. Resize the browser to compare `.container` and `.container-fluid`.

Official installation reference: https://getbootstrap.com/docs/5.3/getting-started/download/
