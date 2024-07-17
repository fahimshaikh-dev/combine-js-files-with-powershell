# JavaScript Bundler

This repository contains a simple script to bundle JavaScript files from a `src` directory into a single file in the `dist` directory. The bundling process combines all `.js` files in the `src` directory into a single `bundle.js` file in the `dist` directory.

## Script Description

The following PowerShell command is used to perform the bundling:

```powershell
Get-Content src\*.js | Set-Content dist\bundle.js
