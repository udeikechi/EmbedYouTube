# EmbedYouTube Playlist / Video
YouTube Playlist Embed Optimization 
I modified this code from a version by https://github.com/paulirish/lite-youtube-embed/tree/master/src which allows you to embed a Youtube video using the video ID. However, this version I made can allow you to embed both a YouTube Playlist and a single YouTube video using either the video ID or the Playlist ID. The aim is to load only the video thumbnail with YouTube control button at page load to improve your page load speed. 

To embed a YouTube Playlist
<lite-youtube playlistid="YOUTUBE_PLAYLIST_ID" params="controls=1"></lite-youtube>

//replace YOUTUBE_PLAYLIST_ID with your actual playlist ID

To embed a YouTube Video
<lite-youtube videoid="fsBqi63VyZs" params="controls=1"></lite-youtube>

Ensure to properly link the JavaScript and CSS files.

