# JavaScript Bundler

This repository contains a simple script to bundle JavaScript files from a `src` directory into a single file in the `dist` directory. The bundling process combines all `.js` files in the `src` directory into a single `bundle.js` file in the `dist` directory.

## Project Structure

Here is an overview of the project structure:

my_project/
├── src/
│ ├── file1.js
│ ├── file2.js
│ └── file3.js
├── dist/
│ └── (empty initially) // bundle.js (combined JavaScript file)
├── index.html // references bundle.js

- **`src/`**: Contains individual JavaScript files to be bundled.
- **`dist/`**: Initially empty; will contain the `bundle.js` file after bundling.
- **`index.html`**: HTML file that includes the `bundle.js` script.

## Script Description

The following PowerShell command is used to perform the bundling:

```powershell
Get-Content src\*.js | Set-Content dist\bundle.js
```
