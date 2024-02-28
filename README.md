# react-skeleton
React Skeleton - as bare bones as I can make it

## Setup

`npm init --init-author-name <<name>> --init-license MIT --init-version 1.0.0 -y`

`npm i --save react react-dom`

`npm i --save-dev vite @vitejs/plugin-react`

`echo "lts/<<version>>" > .nvmrc`

```sh
echo "
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';
export default defineConfig({
  plugins: [react()],
});
" > vite.config.js
```
## NPM Scripts

Update `package.json` by adding these to the `"scripts":` node:
```json
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "vite --open --port 8787",
    "build": "vite build",
    "preview": "vite preview"
  },
```

### Build

`npm run build`

### Dev

`npm run dev`

## 