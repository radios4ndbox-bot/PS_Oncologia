{
  "name": "ps-oncologia",
  "version": "1.0.0",
  "description": "PS Oncologia — Raccolta dati Pronto Soccorso Oncologico",
  "main": "main.js",
  "author": "Reparto Oncologia",
  "license": "UNLICENSED",
  "private": true,
  "scripts": {
    "start": "electron .",
    "build": "electron-builder --win --x64"
  },
  "devDependencies": {
    "electron": "^31.0.0",
    "electron-builder": "^24.0.0"
  },
  "build": {
    "appId": "it.ospedale.ps-oncologia",
    "productName": "PS Oncologia",
    "asar": false,
    "directories": {
      "output": "dist"
    },
    "win": {
      "target": [
        { "target": "portable", "arch": ["x64"] },
        { "target": "nsis",     "arch": ["x64"] }
      ],
      "icon": "src/ps_oncologia.ico"
    },
    "nsis": {
      "oneClick": false,
      "allowToChangeInstallationDirectory": true,
      "installerIcon": "src/ps_oncologia.ico",
      "installerHeaderIcon": "src/ps_oncologia.ico",
      "createDesktopShortcut": true,
      "shortcutName": "PS Oncologia"
    },
    "files": [
      "main.js",
      "preload.js",
      "src/**/*"
    ]
  }
}
