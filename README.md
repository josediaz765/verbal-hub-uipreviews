# xlqp ui previews

A dark, clean, galaxy-style UI preview gallery made for showing off interface screenshots in a better way.
Built with a fully black layout, moving star background, smooth preview cards, fullscreen image viewing, zoom, drag, swipe, and next/previous controls.

## Preview

The gallery is designed to look sharp on desktop and mobile with a black glass style and animated galaxy background.

## Features

* Fully black galaxy theme
* Live moving stars background
* High-quality image previews
* Clean custom names for every preview
* Short descriptions for each UI preview
* Fullscreen viewer
* Next and previous buttons
* Mobile swipe support
* Keyboard controls
* Zoom controls
* Drag-to-pan image viewer
* Open original image button
* Search/filter previews
* Responsive layout for phones, tablets, and PC
* Single HTML file setup

## Controls

| Action         | Control                                           |
| -------------- | ------------------------------------------------- |
| Open preview   | Click **View** or the image                       |
| Next image     | Click **Next** or press `Arrow Right`             |
| Previous image | Click **Previous** or press `Arrow Left`          |
| Close viewer   | Click **X**, outside the image, or press `Escape` |
| Zoom in/out    | Use zoom buttons                                  |
| Pan image      | Drag while zoomed in                              |
| Mobile switch  | Swipe left or right                               |

## Setup

1. Download or clone this repository.
2. Make sure `index.html` is in the main folder.
3. Open `index.html` in your browser.

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

Then open:

```bash
index.html
```

## GitHub Pages

You can host it for free with GitHub Pages.

1. Go to your repository settings.
2. Open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your main branch.
5. Save it.
6. Wait for GitHub to publish the site.

Your gallery will be live as a website.

## File Structure

```txt
.
├── index.html
└── README.md
```

## Customizing Images

Inside the HTML, edit the image list to change names, descriptions, and image links.

Example:

```js
{
  name: "Dark Dashboard UI",
  desc: "A clean black dashboard interface with modern panels and glowing accents.",
  url: "https://example.com/image.webp"
}
```

## Customizing the Title

The main title is:

```txt
xlqp ui previews
```

You can rename it inside the HTML if you want a different project name.

## Notes

This project is made to keep everything simple.
No build tools, no install steps, no extra framework.

Just upload the HTML and it works.

## License

Use it however you want for your own UI preview gallery.
