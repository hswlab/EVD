# Electron Video Downloader (EVD)
[![GitHub](https://img.shields.io/github/license/hswlab/EVD)](https://github.com/hswlab/EVD/blob/main/LICENSE) 
![GitHub issues](https://img.shields.io/github/issues/hswlab/EVD)
[![Downloads](https://img.shields.io/github/v/release/hswlab/EVD)](https://github.com/hswlab/EVD/releases/latest) 

EVD is a graphical user interface for the media downloader yt-dlp. 
A complete list of which websites are supported by yt-dlp can be viewed at [this link](https://raw.githubusercontent.com/yt-dlp/yt-dlp/master/supportedsites.md).
The user interface is based on .NET6 and Electron. For the download and conversion of video and 
audio, the ffmpeg and yt-dlp library is required. The external libraries can be downloaded and set up 
automatically in the settings view. A detailed description can be found in the help PDF

[![GitHub release (with filter)](https://img.shields.io/github/downloads/hswlab/EVD/total?style=for-the-badge&label=download%20EVD
)](https://github.com/hswlab/EVD/releases/latest)

![preview](https://github.com/hswlab/EVD/blob/main/Screenshot.png)

![preview](https://github.com/hswlab/EVD/blob/main/Screenshot2.png)

# Nuget packages and associated licenses used in EVD
- Newtonsoft.Json <a href="https://licenses.nuget.org/MIT">`license: MIT`</a>
- Esprima <a href="https://licenses.nuget.org/BSD-3-Clause">`license: BSD-3-Clause`</a>
- ElectronNET.API <a href="https://licenses.nuget.org/MIT">`license: MIT`</a>
- LiteDB <a href="https://www.nuget.org/packages/LiteDB/5.0.16/license">`license: MIT`</a>
- YoutubeDLSharp <a href="https://licenses.nuget.org/BSD-3-Clause">`license: BSD-3-Clause`</a>

# External libraries (Auto download available in the Settings-View)
The following libraries must be downloaded additionally for the download and video/audio processing to work. These libraries can be downloaded automatically by pressing a button in the settings view.
- FFmpeg 6.0 <a href="https://ffmpeg.org/legal.html">`license`</a>
- yt-dlp <a href="https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE">`license`</a>

# More Details
- German: https://github.com/hswlab/EVD/blob/main/about-de.pdf
- English: https://github.com/hswlab/EVD/blob/main/about-en.pdf

# Known issues
- The App seems to be not responsive, when adding big files for download. I think yt-dlp needs a little more time to grab the Information about the File. If the App still not respond, just restart it.
- Downloads not working anymore. Probably there is a new version of yt-dlp, that can fix this problem. Try to make a new download of yt-dlp in settings view.

