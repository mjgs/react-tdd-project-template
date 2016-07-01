# react-tdd-project-template

Simple boilerplate/template for building [React](https://facebook.github.io/react/) apps with [TDD](https://en.wikipedia.org/wiki/Test-driven_development).

For something a bit more involved that's more configurable check out [react-webpack-project-template](https://github.com/mjgs/react-webpack-project-template).
  
Uses [Quik](https://github.com/satya164/quik) for fast environment setup (webpack based)
  
  * Development server with hot module replacement
  * Test runner with watch mode
  * Javascript bundler for generating production bundles

## Howto

  * Clone repo: `git clone https://github.com/mjgs/react-tdd-project-template my-new-project`
  * Install dependencies: `cd my-new-project && npm install`
  * Update package.json with your project details
  * Delete .git folder, then create your own repo: `git init` ... add all files to the repo
  * Start dev server: `npm run dev`, browser should open `http://localhost:3030`
  * Start test runner: `npm run test-watch`
  * Add your code to `./components.js` and tests to `./components.spec.js`
  * Create `bundle.js` for deployment by running run `npm run build`  

## Credits

  * Dave Ceddia - [Getting Started with TDD in React](https://semaphoreci.com/community/tutorials/getting-started-with-tdd-in-react)