If you are going to be using only the exe:

Just open the exe and paste a playlist/song link and let it download ,no pre-requsites needed unless you are downloading in mp3 format for which you will need ffmpeg to installed.Either ffmpeg has to be added to path or has to be copied to the directory where the exe file is.

Make sure you install all 3 exe provided with ffmpeg so that the program works as normal

FFMPEG Download links:

Windows: https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-essentials.7z (Inside the archive there will be a bin folder in which you will find 3 executables which will have to be installed)

Mac OS: https://evermeet.cx/ffmpeg/

Debian: https://tracker.debian.org/pkg/ffmpeg

Ubuntu: https://launchpad.net/ubuntu/+source/ffmpeg

The three required ffmpeg executables if you wish to download in mp3 format

![image](https://user-images.githubusercontent.com/74890659/154211073-fc63a638-789a-489f-883d-0b887176b620.png)

=======================Only if you are going to use the .py file=======================

Spotipy:
```pip install spotipy --upgrade```

youtube_search:
```pip install youtube-search```

pytube:
```pip install pytube```

mutagen:
```pip install mutagen```

pydub:
```pip install pydub```

1)You also require a client id and client secret for the program to work which you can obtain from https://developer.spotify.com/ 
by logging in and creating a new app from the dashboard which will then give you a client id and client secret 
which you paste in ```downloader.py```file 

![image](https://user-images.githubusercontent.com/74890659/130178928-61802ff8-c549-4509-b055-5c96a440e34d.png)

![image](https://user-images.githubusercontent.com/74890659/130178984-0243cc2a-d180-45c9-b132-0d1783feabc3.png)

2)Then download the repository and open the ```gui.py``` file and paste the link of 
the playlist you want to download and click on the "Download songs" button and let it download and convert 
the songs which will take time depending on your cpu and number of songs in the playlist or if you are 
unwilling to use the .py file you can instead use the .exe file which does not require the libraries to be
installed although ffmpeg has to installed and added to path for it to work

![image](https://user-images.githubusercontent.com/74890659/150334965-049446e5-8daa-4b65-8213-dcf2bb9247ff.png)

3)The songs will be downloaded to "Downloads" folder created within the directory itself where the py file exists

![image](https://user-images.githubusercontent.com/74890659/154210788-51e600d5-a0f9-477a-a958-a6dfbd7aa669.png)

If you have any problems,doubts,suggestion or any other queries you can reach me on discord at Fuji#4649
