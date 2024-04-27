# Yet another ui template 
## Commands
1. `npm start` runs esbuild-server. The serverdir is `public`.
2. `npm styles` runs compilation scss-styles from `app/scss` to `public/dist/app.css`.
3. `npm styles-min` minifies built styles via csso and saves it to `public/dist/app.min.css`.
4. `npm build` compiles styles and build js-bundle. Javascript location is `public/dist/app.js`.
5. `npm prod` does `npm build` but also minifies javascript- and css-files. 