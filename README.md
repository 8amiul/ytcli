<h1 align="center">ytcli</h1>

<p align="center">A script to watch videos with the help of dmenu</p>


<p align="center"> 
<img src="/x.webp" alt="Video Preview" width="500px">
</p>


### How does this work?
It scrape Invidious instances and with some grep,sed and cut it gets the link of the desired video url. You might need Dmenu, youtube-dlp and MPV to make the script work.

### Requirements
* Dmenu
* Mpv
* Youtube-dlp

### Alternatives
You have to modify the script a little bit. Such as if you got fzf instead dmenu then you you can also use fzf on that place. For mpv it is little hard to say cause I am only familiar with Mpv. But if you can manage any other video player which can work with yt-dlp then yes it is also possible to use that with this script.

### Installation

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/8amiulyt/ytcli/main/ytcli" -o /usr/local/bin/ytcli
$ sudo chmod +x /usr/local/bin/ytcli
```
