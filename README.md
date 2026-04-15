# CLEF Theme
A Hugo theme for CLEF conference websites.

## Building Locally

1. [Install Hugo](https://gohugo.io/installation/) and [Install NPM](https://nodejs.org/en/download)
2. Install tailwind
```bash
npm install --save-dev tailwindcss @tailwindcss/cli @tailwindcss/typography
```
3. (Optional) Run in local development mode to verify the page
```bash
hugo server -D --disableFastRender
```

You can view the result in your browser (usually at `localhost:1313`)

4. Built the static pages:
```bash
hugo
```

This will create a `public` directory where the rendered static site is located.

## Usage Outside CLEF

This theme is licensed under an [MIT License](LICENSE). Feel free to use it. We would be delighted if you acknowledge CLEF if you do, for example with a link back to this repository. And if you've made any improvements or fixes along the way, we'd love it if you considered contributing them upstream - it helps everyone using the theme. 
