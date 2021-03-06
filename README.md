# Spotify Music Downloader (SMD) 
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![GitHub repo size in bytes](https://img.shields.io/github/repo-size/artyshko/smd.svg) ![GitHub Release Date](https://img.shields.io/github/release-date/artyshko/smd.svg) ![GitHub issues](https://img.shields.io/github/issues/artyshko/smd.svg) ![Beerpay](https://img.shields.io/beerpay/artyshko/smd.svg) [![Beerpay](https://beerpay.io/artyshko/smd/make-wish.svg?style=flat)](https://beerpay.io/artyshko/smd?focus=wish)

<img align="center" src="https://raw.githubusercontent.com/artyshko/smd/telegram/Data/9.png"> 

<img align="left" height="50" wigth="50" src="https://i.ibb.co/6sLhjBk/telegram-logo-ad3d08a014-seeklogo-com-by-yagorocha-dbyy26q.png">

# **Get it on Telegram <a href="https://telegram.me/SpotifyMusicDownloaderBot"><b>@SpotifyMusicDownloaderBot</b></a>**

<img align="center" src="https://raw.githubusercontent.com/artyshko/smd/telegram-beta/Data/header1.png">

## **Now with Shazam support**

<img align="center" src="https://raw.githubusercontent.com/artyshko/smd/telegram-unstable/Data/header3.png">

## Desktop version

<img align="center" src="https://i.ibb.co/3Yrh7Qr/header.png"> 

## Usage

```
./main.py [without any parameters] - normal startup

./main.py [parameter][argument] - startup with arguments

Parameters

  -h, --help       Print a help message and exit.

  -s, --song       Spotify song URI.

  -p, --playlist   Spotify playlist URI.

  -q, --query      Search query.

  -y, --youtube    YouTube Music url.
                   Note that your link should be with quotation marks - "your_url"!

  -v, --video      YouTube url.(You will get a song but without any tags)
                   Note that your link should be with quotation marks - "your_url"!

  -a, --apple      Apple Music url.

  -f, --file       File with song URIs. (Spotify only)

```
## Installation

```
git clone https://github.com/artyshko/smd.git
```

### First you need to install all dependencies
```
pip3 install -r requirements.txt
```

### Make file executable
```
chmod +x main.py
./main.py
```
### Or use
```
python3 main.py
```
### How to get song URI

<img align="center" src="https://i.ibb.co/BzM7ZKp/image4.png">

### Example of Spotify URI Code
```
spotify:track:4tmwiN9YU7xMjh2hoqcVuI
```

### Song mode
Example:
```
./main.py -s spotify:track:7ARveOiD31w2Nq0n5FsSf8
```

### Query mode
Example:
```
./main.py -q "The XX - Intro"
```

### YouTube Music mode
Example:
```
./main.py -y "https://music.youtube.com/watch?v=HnXzzTIFu_U&list=RDAMVMHnXzzTIFu_U"
```

### YouTube video mode
Example:
```
./main.py -v "https://www.youtube.com/watch?v=JHi-WGFGWek"
```

### Apple Music mode
Example:
```
./main.py -a "https://itunes.apple.com/us/album/i-wanna-be-yours/663097964?i=663098065"
```

### File mode
#### Create file with songs
<img align="center" src="https://i.ibb.co/qJvgMXB/file.png">

Example:
```
./main.py -f songs.txt
```

### Playlist mode
#### Create playlist and make it secret
<img align="center" src="https://i.ibb.co/kBKtDys/image1.png">

#### Then copy playlist URI
<img align="center" src="https://i.ibb.co/yWHHBDX/image2.png">

Example:
```
./main.py -p spotify:user:spotify:playlist:37i9dQZF1DXcRXFNfZr7Tp
```
