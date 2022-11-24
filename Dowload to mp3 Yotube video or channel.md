**To extract the audio from a youtube video:**

`youtube-dl.exe --ffmpeg-location "C:\ffmpeg\bin" -f bestaudio --extract-audio --audio-format mp3 https://www.youtube.com/watch?v=0FPZdkgDIlI&t=12s`

**To download age restricted youtube videos:**

1. Sign in to Youtube on Web Browser.

2. Install the extension Get cookies.

3. While browsing youtube, click on the extension and export the cookies captured by the extension to a file, say ~/cookies.txt

4. Run youtube-dl with the option --cookies

Sample command:

`youtube-dl -f best https://www.youtube.com/watch?v=mgDtC61bH98 --cookies ~/cookies.txt`
