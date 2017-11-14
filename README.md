# vue-2-boilerplate-expressapp
> A boilerplate for building medium to large Vue 2 single page applications with backend node server. Server will host the vue js application and also will have the backend server with REST endpoints which can be called from vuejs application.

vue js application + express app server.

I have added following files on top of [vue-2-boilerplate](https://github.com/petervmeijgaard/vue-2-boilerplate) repo.

> server.js for hosting the vuejs application on the express app. This will return the vue.js app home page and will expose server side rest endpoints. Try http://localhost:3000

> build/dev-server-integration.js for the deplying the vuejs dev middleware in express app. Dev server will be loaded using webpack dashboard.

> routes/index.js for sample server route.


## What's included ##
- `npm run dev`: first-in-class development experience.
  - Webpack dashboard + `vue-loader` for single file Vue components.
  - State preserving hot-reload
  - State preserving compilation error overlay
  - Lint-on-save with ESLint
  - Source maps

- `npm run build`: Production ready build.
  - JavaScript minified with [UglifyJS](https://github.com/mishoo/UglifyJS2).
  - HTML minified with [html-minifier](https://github.com/kangax/html-minifier).
  - CSS across all components extracted into a single file and minified with [cssnano](https://github.com/ben-eb/cssnano).
  - All static assets compiled with version hashes for efficient long-term caching, and a production `index.html` is auto-generated with proper URLs to these generated assets.


- `npm run start-prod`: It will start the server in production environment.
  - Execute this command to up application in non-dev mode.

Rest of the vue js boiler plate code is belongs to vue-2-boilerplate.

Refer [vue-2-boilerplate](https://github.com/petervmeijgaard/vue-2-boilerplate)



## Fork It And Make Your Own ##
What are you waiting for?!
Make something awesome!

## License ##

MIT License

Copyright (c) 2017 Ganeshkumar Ramachandran

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
