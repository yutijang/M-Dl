# M-Dl - Multi downloader tool

This tool transitions the usage of aria2c and yt-dlp from command line to GUI.
With BitTorrent, the tool only downloads and does not seed.

## Usage
This is a portable version, no installation needed, run the file `M-Dl.exe` directly.

This tool uses the following softwares: `aria2c`, `yt-dlp` and `ffmpeg`.

You can find and download at the following link:

* aria2c [https://aria2.github.io/](https://aria2.github.io/)
* yt-dlp [https://github.com/yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)
* ffmpeg [https://ffmpeg.org/](https://ffmpeg.org/) or [yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds)


Or they are automatically downloaded to the latest version when selecting the `About` > `Check Support update` button,
they are downloaded according to the following links:
* aria2c: [https://github.com/aria2/aria2/releases/latest](https://github.com/aria2/aria2/releases/latest)
* yt-dlp: [https://github.com/yt-dlp/yt-dlp/releases/latest](https://github.com/yt-dlp/yt-dlp/releases/latest)
* ffmpeg: [https://github.com/yt-dlp/FFmpeg-Builds/releases/latest](https://github.com/yt-dlp/FFmpeg-Builds/releases/latest)

All three files `aria2c.exe`, `yt-dlp.exe` and `ffmpeg.exe` must be placed in the directory declared in `Options` > `Support software directory`. By default, the `Support` folder is at the same level as the `M-Dl.exe` file.


The Add single link button ![add-2](https://github.com/yutijang/M-Dl/assets/5685320/419abd74-e788-4ca9-9b3a-453f9464843c) is used to analyze and add types of links: `direct`, `torrent`, `magnet`, `playlist`, `media album` from video and audio sharing websites, `.torrent` files from your computer.

Main GUI
![image](https://github.com/user-attachments/assets/72f992bc-dbc9-44da-96a1-71617c4b2654)

Parse YouTube link
![image](https://github.com/user-attachments/assets/72a4a6d3-b43a-4311-a5f8-f2fe886feb0f)

Parse YouTube playlist link
![image](https://github.com/user-attachments/assets/0c5e1f3a-ad54-454c-8e86-afd81ee08516)

Parse YouTube user link
![image](https://github.com/user-attachments/assets/b6090d9a-7506-4aa5-8457-dc86e473818c)

Parse Tiktok user link
![image](https://github.com/user-attachments/assets/20c4fa93-f43b-46d2-a3f7-6c3704f8e5e6)

Parse torrent link
![image](https://github.com/user-attachments/assets/74c0076a-9ca7-4551-b909-22660535f764)

Parse torrent file
![image](https://github.com/user-attachments/assets/a9f0c463-340b-4706-8684-78270987e4f7)

Parse magnet link
![image](https://github.com/user-attachments/assets/29733bc7-9d28-460a-a678-bb54ca38894a)

Parse Google Drive link
![image](https://github.com/user-attachments/assets/5f3f5aaf-b9e3-4bf8-a826-cb663c61f575)


You can also add link lists (of the same type) using the Create link list button ![create-2](https://github.com/yutijang/M-Dl/assets/5685320/6bd7719d-271d-44d5-be56-df746fd1ae28)

YouTube links list
![image](https://github.com/user-attachments/assets/ebf7ce42-154f-4091-b414-00d0e2c4da71)

Direct links list
![image](https://github.com/user-attachments/assets/e571e1f4-ce18-4e53-bf59-edeab98e43e2)

---
This tool is written in the AutoIt programming language so it will inevitably be mistakenly recognized as a virus by anti-virus softwares. It's up to you whether you want to use it or not
