# AI and Coding Agents: Demo Start

Bookshelf is a small React app with TypeScript and tests. You manage a list of books: filter by genre, search by title, mark books as read and remove them. It has no known bugs and all tests pass.

We use it in the demo to take the first steps with Claude Code: ask questions about the project, read a permission prompt, and make a small change together.

Nothing in this project is secret. If you break something, `git restore .` brings it back (initialize a git repository first with `git init -b main`, `git add .` and `git commit -m "Initial commit"`).

## Development

Install the dependencies with `npm i` first (Node.js 22.22 or newer is required).

- `npm run dev` starts the app in the browser
- `npm run test` runs the tests in the watch mode, `npm run test:run` runs them once
- `npm run check` checks the types
