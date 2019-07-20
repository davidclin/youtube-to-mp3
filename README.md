<img src="./images/youtube-dl.jpg" width=350>

Download videos from YouTube and convert them to mp3!


## Requirements

For Ubuntu,
  * [youtube-dl](https://github.com/rg3/youtube-dl)
  * wget
  * ffmpeg
  * lame

For Windows,
  * Microsoft Visual C++ 2010 Redistributable Package (x86)

## Installation

For Ubuntu, 

```
    $ apt-get install youtube-dl wget ffmpeg lame
```

For Windows 10,

```
    Command Prompt (as Administrator)
    > choco install youtube-dl
    > choco install ffmpeg
```

## Usage

```
Ubuntu terminal,
    $ youtube-dl --extract-audio --audio-format mp3 {VIDEO_URL_GOES_HERE}

Windows Command Prompt,
    .\youtube-dl.exe --extract-audio --audio-format mp3 {VIDEO_URL_GOES_HERE}

```


## Example

```
    $ youtube-dl --extract-audio --audio-format mp3 http://www.youtube.com/watch?v=0714IbwC3HA
```

## Simpler Solution
For Linux,
youtube-dl is a powerful tool, but if all you want to do is convert YouTube videos to mp3 without having to type the --extract-audio and --audio-format options, simply copy [youtube-dl.conf](https://github.com/davidclin/youtube-to-mp3/blob/master/youtube-dl.conf) to /etc directory then type

```
    $ youtube-dl videoURL
```



