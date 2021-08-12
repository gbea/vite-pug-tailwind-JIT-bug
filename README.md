# vite-pug-tailwind-bug

This shows a different behaviour between HTML and pug templates in a vuejs SFC, while using vite with tailwindcss in JIT mode.
With the html template, the HMR pickups when tailwindcss JIT mode detects a change, while the pug template does not.

## Reproduce
```bash
$ npm install
$ npm run dev
```

Then try to modify the classes in `components/TestPug.vue` and `components/TestHtml.vue` to observe the difference.

