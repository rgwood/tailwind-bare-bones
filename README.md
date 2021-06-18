## Tailwind CSS Bare-Bones Boilerplate 

A very simple starting point for writing no-framework web pages, using [the "Tailwind CLI" feature in v2.2](https://blog.tailwindcss.com/tailwindcss-2-2).

### Prerequisites

Node and something like [`devserver`](https://github.com/kettle11/devserver) to serve up a directory with hot reload

### Build

`npx tailwindcss -o tailwind.css --jit --purge="./**/*.html""`

### Hot Reload

Run at the same time:

- `npx tailwindcss -o tailwind.css --watch --jit --purge="./**/*.html""`
- `devserver --reload`

### To Do

- script or VS code command to launch both hot reload processes in parallel
- Solarized color scheme