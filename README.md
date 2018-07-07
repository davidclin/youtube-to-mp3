<img src="./images/youtube-dl.jpg" width=350>

Download videos from YouTube and convert them to mp3!


## Requirements

  * [youtube-dl](https://github.com/rg3/youtube-dl)
  * wget
  * ffmpeg
  * lame


## Installation

On Ubuntu, 

```
    $ apt-get install youtube-dl wget ffmpeg lame
```


## Usage

```
    $ youtube-dl --extract-audio --audio-format mp3 videoURL
```


## Example

```
    $ youtube-dl --extract-audio --audio-format mp3 http://www.youtube.com/watch?v=0714IbwC3HA
```

## Simpler Solution
youtube-dl is a powerful tool, but if all you want to do is convert YouTube videos to mp3 without having to type the --extract-audio and --audio-format options, simply copy [youtube-dl.conf](https://github.com/davidclin/youtube-dl-mp3/blob/master/youtube-dl.conf) to /etc directory then type

```
$ youtube-dl videoURL
```

## Useful Resources
[youtube-dl](http://rg3.github.io/youtube-dl/)
[YouTube DL Tutorial](https://steemit.com/utopian-io/@steemmaster/tutorial-install-youtube-dl-and-download-playlists-and-channels-from-youtube)

