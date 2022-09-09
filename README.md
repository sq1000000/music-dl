# music-dl
An easy yt-dlp alias that downloads metadata and album art

Technically, this script just runs yt-dlp with ```--add-metadata --embed-thumbnail --output "%(playlist_index)s - %(track)s.%(ext)s"```

I keep forgetting these flags exist, so I made an easier method to call it. Hopefully somebody else can benefit from this existing

#### Requirements:
  yt-dlp or youtube-dl must be installed. yt-dlp is included in all major Linux package managers

#### To install on Linux:

    sudo false
  	wget https://raw.githubusercontent.com/sq1000000/music-dl/main/music-dl
  	sudo chmod +x music-dl
  	sudo mv touchup /usr/bin/music-dl
  
#### To run:

	music-dl example.com
