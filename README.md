# simple-youtube2mp3

A simple Youtube to MP3 converter website.

## Setup

### Commands needed:

Prerequisites:

- ffmpeg

Installation (Linux):

```
sudo apt install ffmpeg
```

```sh
git clone https://github.com/XD14/simple-youtube2mp3
cd simple-youtube2mp3
npm install
npm install pm2 -G
pm2 start index.js
```

Once you run the aforementioned commands, the server will begin listening in the background on port `8080`, or at `127.0.0.1:8080`.
