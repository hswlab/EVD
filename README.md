# Electron Video Downloader (EVD)
[![GitHub](https://img.shields.io/github/license/hswlab/EVD)](https://github.com/hswlab/EVD/blob/main/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/hswlab/EVD/total)](https://github.com/hswlab/EVD/releases/latest)
[![Downloads](https://img.shields.io/github/v/release/hswlab/EVD)](https://github.com/hswlab/EVD/releases/latest)

EVD is a graphical user interface for the well-known media downloader yt-dlp. In principle, this 
supports downloads from all video portals that would be possible with yt-dlp. A full list of supported 
pages can be found at this link.
https://raw.githubusercontent.com/yt-dlp/yt-dlp/master/supportedsites.md

The user interface is based on . NET6 and Electron. For the download and conversion of video and 
audio, the ffmpeg and yt-dlp library is required. The external libraries can be downloaded and set up 
automatically in the settings view. A detailed description can be found in the help PDF

![preview](https://github.com/hswlab/EVD/blob/main/Screenshot.png)

# Nuget packages and associated licenses used in EVD
- Newtonsoft.Json <a href="https://licenses.nuget.org/MIT">`license`</a>
- Esprima <a href="https://licenses.nuget.org/BSD-3-Clause">`license`</a>
- ElectronNET.API <a href="https://licenses.nuget.org/MIT">`license`</a>
- LiteDB <a href="https://www.nuget.org/packages/LiteDB/5.0.16/license">`license`</a>
- YoutubeDLSharp <a href="https://licenses.nuget.org/BSD-3-Clause">`license`</a>

# External libraries (Auto download available in the Settings-View)
- FFmpeg 6.0 <a href="https://ffmpeg.org/legal.html">`license`</a>
- yt-dlp <a href="https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE">`license`</a>

# More Details
- German: https://github.com/hswlab/EVD/blob/main/about-de.pdf
- English: https://github.com/hswlab/EVD/blob/main/about-en.pdf

# Known issues
The App seeps to not responsive, when adding big files for download. I think yt-dlp needs a little more time to grab the Information about the File. If the App still not respond, just restart it.

# Alternative Downloader "Downloadthek"
There is another implementation of this Video Downloader with the name "Downloadthek", which is not using yt-dlp. This App is a little faster but only support downloads from YouTube and XVideos
https://github.com/hswlab/downloadthek
