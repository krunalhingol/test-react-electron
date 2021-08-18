## Project structure

- `electron/`: Code for the main Electron process
- `src/react/`: Code for the React renderer process
- `src/shared/`: Code shared between React and Electron
- `package.json`: Contains scripts for running the app in development, building it, and packaging it for production using electron-builder

## Build Commands
1. npm run clean => cleans dist folder.
2. npm run build => creates react build
3. npm run electron-build => creates electron build
4. npm run package-linux => creates electron linux package (use -win for windows)

## Build Folder
/dist