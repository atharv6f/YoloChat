# YoloChat

<h1 align="center">
  <br>
  <img src="https://github.com/atharv6f/YoloChat/blob/master/assets/images/react_app_logo.png" alt="Yolo Chat" width="160">
</h1>

<h4 align="center">A desktop chat application based on <a href="http://electron.atom.io" target="_blank">Electron.js, React.js and Firebase</a></h4>

## Installation
[YLZ]: https://drive.google.com/file/d/1RV6MkcHz_DeWQBLLPoB1UgT7R_Av-UIk/view?usp=sharing
[YL]: https://drive.google.com/file/d/1517h1pDa6HgAarL65MNWEvzVUNMMSlWT/view?usp=sharing
### Windows

1. Download [Yolo Chat.exe][YL] or [Yolo Chat.zip][YLZ]
2. Open or unzip the file
3. Done!

### OS-X
coming soon :stuck_out_tongue_closed_eyes:

### Linux
coming soon :stuck_out_tongue_closed_eyes:

### For developers
Clone the source locally:

```sh
$ git clone https://github.com/atharv6f/YoloChat.git
$ cd YoloChat
```
If you're on Debian or Ubuntu, you'll also need to install
`nodejs-legacy`:

Use your package manager to install `npm`.

```sh
$ sudo apt-get install npm nodejs-legacy
```

Install project dependencies:

```sh
$ npm install
```

### Build installers

Build app for Windows
```sh
$ npm run build
$ npm run make:win
```

Build app for OSX
```sh
$ npm run build
$ npm run make:macos
```
Build app for Linux
```sh
$ npm run build
$ npm run make:linux
```
## Usage

<kbd>ctrl + R</kbd> - Reload

<kbd>ctrl + W</kbd> - Quit App (while window is open).
Start the app:

```sh
$ npm start
```
## Built with
- [Electron](https://electron.atom.io)
- [React](https://reactjs.org/)
- [Firebase](https://firebase.google.com/)

## Tiny features

* You provide a username to enter a chat room. Server endpoint is configurable.
* Supports Markdown.
* List of connected users.
* Informs connection and disconnection events.
* Informs when someone is typing.
* Supports multiple instances



