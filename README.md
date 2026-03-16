# Logan Heft — Windows XP Desktop Portfolio

A Windows XP-themed interactive desktop portfolio. The full TPM Dashboard opens inside an Internet Explorer window.

## Folder Structure

```
winxp/
├── index.html          ← Windows XP desktop (main entry point)
├── dashboard_v2.html   ← Full TPM Dashboard (loads inside IE window)
├── resume/
│   └── LoganHeft_Resume.pdf
└── README.md
```

## How to Use

- **Internet Explorer** → Double-click to open the full TPM Dashboard
- **My Computer** → Browse to programs and files
- **About Me.txt** → Opens Notepad with career summary
- **Resume Folder** → Double-click PDF to download
- **Minesweeper** → Fully playable classic game
- **Start Menu** → Click the green Start button bottom-left
- **Right-click desktop** → Context menu

## Deploy

### GitHub Pages (recommended)

1. Create repo `yourusername.github.io`
2. Upload all files maintaining folder structure:
   ```
   index.html
   dashboard_v2.html
   resume/LoganHeft_Resume.pdf
   ```
3. Settings → Pages → Deploy from branch: main
4. Live in ~60 seconds

### Vercel / Netlify

Drag the `winxp/` folder to netlify.com/drop — done instantly.

## Customize

- **Change name**: Search for "Logan Heft" in index.html and replace
- **Update contact**: Search for "LoganHeft1@gmail.com" and "908-334-2696"  
- **Replace resume**: Drop new PDF in `resume/` folder, update filename in `downloadResume()` function
- **Edit About Me.txt**: Find `.notepad-content` div in index.html
- **Update dashboard**: Edit `dashboard_v2.html` for full portfolio content changes
