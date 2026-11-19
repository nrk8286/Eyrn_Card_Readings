# Eyrn Card Readings

This repository currently contains placeholder source files, not a working card
reading application. A successful build verifies the toolchain only; the UI,
content, and application behavior still need to be implemented.

## Build

Use Node.js and npm, then run `npm ci` and `npm run build`. Create React App writes
the result to `build/`. The checked-in `vercel.json` selects this toolchain and
output directory so connected projects do not try to run Vite or publish `dist/`.

Generated dependencies and build output are ignored by Git.
