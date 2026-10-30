# Portfolio Page (Grid + Flexbox)

A responsive, multi-section personal portfolio page built with plain HTML and CSS. It combines **CSS Grid** for the page layout and **Flexbox** for content alignment inside each section.

**Author:** Pratiksha Bhende
**GitHub:** [pratiksha0604](https://github.com/pratiksha0604)

## Live Demo

https://pratiksha0604.github.io/portfolio-grid-flexbox/

## Features

- Two-column desktop layout built with CSS Grid
- Flexbox used inside the header, About, Projects and Contact sections
- Contact section spans the full width on desktop
- Responsive breakpoints at 768px and 480px that stack sections on smaller screens
- No frameworks or dependencies

## Sections

| Section  | Description                                    |
|----------|------------------------------------------------|
| Header   | Name and navigation links                      |
| About    | Avatar and a short introduction                |
| Projects | List of project cards                          |
| Contact  | Email, GitHub and LinkedIn buttons             |

## Layout

```
Desktop                         Mobile
+----------------------------+  +----------+
| Header / Nav               |  | Header   |
+--------------+-------------+  +----------+
| About        | Projects    |  | About    |
+--------------+-------------+  +----------+
| Contact (full width)       |  | Projects |
+----------------------------+  +----------+
                                | Contact  |
                                +----------+
```

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Media Queries)

## Project Structure

```
portfolio-grid-flexbox/
├── index.html
├── style.css
└── README.md
```

## How to Run

No installation is needed.

**Option 1: Open directly**
Double-click `index.html` to open it in your browser.

**Option 2: Live Server (VS Code)**
1. Install the **Live Server** extension.
2. Right-click `index.html` and choose **Open with Live Server**.
3. The page opens at `http://127.0.0.1:5500/index.html`.

**Option 3: Python local server**

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Responsive Testing

1. Press `F12` to open DevTools.
2. Press `Ctrl + Shift + M` to toggle device mode.
3. Resize below 768px to see the sections stack into one column.

## Browser Support

Tested on Chrome, Edge and Firefox.

## Deployment (GitHub Pages)

1. Push the project to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under Source, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.

## Author

**Pratiksha Bhende**
GitHub: [@pratiksha0604](https://github.com/pratiksha0604)