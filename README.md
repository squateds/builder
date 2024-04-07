![palette](palette.jpg)
# Web/Mobile HTML Builder & Editor 🚀
### No-code HTML builder for your web and mobile apps based on [AWDEV](https://www.awdev.eu.org) and [Tailwind](https://tailwindcss.com/docs).

###### Built for you by [Builder](https://awdev.eu.org/builder/index.html)) with love 🤍
# 
Feel free to use as-is, and contribute (it's really easy):

🥇[ONLINE BUILDER](https://awdev.eu.org/builder/index.html)

## Summary
`TL;DR` Simply click ONLINE BUILDER and start building your HTML page.

-- Currently, to change components content click the component settings (cog wheel) then use this ugly hack: click "update" then add a character to the following input, then hit "tab" to update your component. 
Feel free to provide a better way --

Click the `</>` button to inspect and copy your HTML and CSS.
Paste code in your app and don't forget to add DaisyUI and Tailwind CSS in your html page, in the `header`:
```html
<link href="https://cdn.jsdelivr.net/npm/daisyui@2.38.1/dist/full.css" rel="stylesheet" type="text/css" />
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2/dist/tailwind.min.css" rel="stylesheet" type="text/css" />
```
Auto-saves on your browser, no need to save!

## 🥰 PR are welcome!

If you'd like to contribute but don't want to download and install stuff, simply FORK this repository and change `blocks.js` and `components.js` in `src/`, then PR (Pull Request) from your fork to this project.

## Download

* CDN
  * `https://unpkg.com/builder`
* NPM (not sure)
  * `npm i builder`
* GIT
  * `git clone https://github.com/squateds/builder.git`


## Development

Clone the repository

```sh
git clone --depth 1 https://github.com/squateds/builder.git
cd builder
```

### Install dependencies

```sh
npm i
npm i -g grapesjs-cli
(you will need this one to test and build easily)
```

### Start the dev server

```sh
npx grapesjs-cli serve
```

### Tweak

Simply change 2 files in `src/`

* components.js (the HTML code in your page)
* blocks.js (the menu elements to drag in your HTML page)

### Build the source

```sh
npx grapesjs-cli build
```

### Test your project before PR
```sh
http-server ./dist/
```

## License

MIT
