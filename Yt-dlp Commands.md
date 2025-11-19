#### best available quality for both audio and video

yt-dlp -f URL

#### audio-only with the best quality

yt-dlp -f bestaudio URL
yt-dlp --no-playlist -x --audio-format mp3 URL

#### download only audio

yt-dlp -x --audio-format mp3 URL 

#### list all available quality formats

yt-dlp -F URL

#### download video only

yt-dlp -f 136 URL

#### video and audio combined

yt-dlp -f 136+140 URL

#### download best video quality

yt-dlp -f best 136 URL
yt-dlp -f bestaudio 136 URL

#### downlaod video mp4

yt-dlp -f mp4
