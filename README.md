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
    C:\Users\David\Desktop\youtube-dl.exe --extract-audio --audio-format mp3 {VIDEO_URL_GOES_HERE}

```


## Example

```
    $ youtube-dl --extract-audio --audio-format mp3 http://www.youtube.com/watch?v=0714IbwC3HA
```

## Simpler Solution
If you don't want to type the --extract-audio and --audio-format options all the time, you can create [youtube-dl.conf](https://github.com/davidclin/youtube-to-mp3/blob/master/youtube-dl.conf) and place the file in the /etc directory for Ubuntu or on your Desktop for Windows assuming that's where you installed youtube-dl. 

Windows youtube-dl.conf example,
```
# Always extract audio
-x

# Always convert to mp3
--audio-format mp3
```

## Final Solution
```
Ubuntu
    $ youtube-dl videoURL
    
Windows
    C:\Users\David\Desktop\youtub-dl videoURL
```



