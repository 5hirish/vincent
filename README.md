# vincent

This template is made to help start your project based on Webpack + TailwindCSS. Setup is pretty simple, while keeping best performance practices set up.

### npm tasks
* `npm start` - runs dev server on `http://localhost:8080` and reloads the browser on changes
* `npm run build` - build assets in production mode, ready to deploy

## Notes
* Before every build, build directory is deleted to avoid deploying old assets

## Additional resources

* [Tailwind.run](https://tailwind.run/new) - sandbox for quickly mocking/debugging components in isolation
* [TailwindCSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet) - with search. Hopefully will be updated to the latest TailwindCSS version soon
* [VSCode IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - Custom config aware autocomplete for TailwindCSS
* [Webpack dynamic imports](https://medium.com/front-end-weekly/webpack-and-dynamic-imports-doing-it-right-72549ff49234) - How and why do the dynamic imports. See [`js/app.js`](src/js/app.js) for example.

## Happy coding!