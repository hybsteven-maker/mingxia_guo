# Mingxia Guo Personal Website

This repository contains a single-page personal website built in HTML and CSS for **Mingxia Guo / 郭明霞**.

## Files

* `index.html` — the main website file

## How to run locally

Because this is a standalone HTML file, you can open it directly in a browser.

### Option 1: Open directly

1. Save the website code as `index.html`
2. Double-click the file
3. It will open in your default browser

### Option 2: Use VS Code with Live Server

1. Open the folder in VS Code
2. Install the **Live Server** extension
3. Right-click `index.html`
4. Choose **Open with Live Server**

This is helpful if you want the page to refresh automatically while editing.

## How to publish with GitHub Pages

### 1. Create a repository

Create a GitHub repository, for example:

`mingxia-guo-website`

### 2. Upload the file

Upload `index.html` to the root of the repository.

### 3. Enable GitHub Pages

In GitHub:

* Go to **Settings**
* Open **Pages**
* Under **Build and deployment**:

  * **Source**: Deploy from a branch
  * **Branch**: `main`
  * **Folder**: `/root`

### 4. Wait for deployment

GitHub will generate a public URL for your site.

## Recommended repository structure

```text
.
├── index.html
└── README.md
```

If you later add files such as a CV or profile image, the structure may look like this:

```text
.
├── index.html
├── README.md
├── CV.pdf
└── profile.jpg
```

## Customization

You can edit the following parts inside `index.html`:

* **Name section**
* **About**
* **Experience**
* **Research Areas**
* **Selected Publications**
* **Awards**
* **Talks & Conference Presentations**
* **Editorial & Professional Service**
* **Links / Contact**


## Adding a CV

If you want to add a CV download button later:

1. Place the CV file in the repository, for example `CV.pdf`
2. Add a link in `index.html`

Example:

```html
<a href="CV.pdf" target="_blank" rel="noopener">Download CV</a>
```

## Notes

* The website is written as a hybrid academic–industry personal webpage.
* The site is fully static and does not require any backend.
* For long-term stability, it is recommended to store all images and downloadable files directly inside the repository.

## License

This website content is personal and intended for Mingxia Guo’s professional webpage.
