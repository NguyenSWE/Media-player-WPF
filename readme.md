## Windows programing 20_3

# Project 2: Media Player

*An simple Windows Desktop `.NET` app in `C#` using `WPF` UI framework to play media files locally supports popular audio and video formats like mp4, m4a, mp3, wav...*

### Usage

Run file `MediaPlayer.exe` in folder `release` to start the application.

### Demo

[Demo MediaPlayer on Youtube](https://www.youtube.com/watch?v=r0Xboh57hbA)

**Note:** Click the `CC` icon to turn on subtitle.

### Core requirements

 1. Add all media files you want to play into a playlist.

 2. Add and remove files from the playlist.

 3. Save and load a playlist.

 4. Show the current progress of the playing file, allow seeking.

 5. Play in shuffle mode.

 6. Play the next file in playlist, play the previous file in the playlist.

### Improvements

1. Store recently played files.

2. Keep last played position for continuous viewing.

3. Support both audio and video files.

4. Add hooking to support global shortcut key for pause / play / skip to next file:

      |  Hook event | Shortcut   |
      |---|---|
      |  Play/pause | Ctrl+Alt+B |
      |  Next | Ctrl+Alt+N |
      | Previous | Ctrl+Alt+P |


### Some screenshoots

![Giao diện của ứng dụng](https://i.postimg.cc/GtQ3yX7S/Screenshot-2023-01-14-014833.png)

![Play queue](https://i.postimg.cc/4x4r2LY1/Screenshot-2023-01-14-011035.png)
