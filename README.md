# Node.js-LAN-File-Sharing
A small Node.js app designed for sharing files while on the same network. Especially useful when you are trying to get a file from a friend and their device has a single broken USB port.

## Features
- Easy to use Drag and Drop file upload.
- Faster than uploading to a server then downloading since you are the server.
- Works with large files (tested with >2gb).
- Fast loading and opening due to light weight (no library) Javascript and customized bootstrap.

## How to use
0. Clone (or download as zip) this project from github
0. Open terminal (or command line) in project's folder.
0. First run ```npm install``` then ```node main.js```.
0. Project will display your LAN ip and port (8080 by default) in terminal once running.
0. On another device in the LAN, go to the url:port.
0. Drag & Drop any file in browser to transfer.

Project saves sent files in "files" folder. Also files in "files" folder can be downloaded from the browser.

PORT enviroment varible is used to change the port. e.g. ```export PORT=3030; node main.js```

