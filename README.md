# WackyWebM

WackyWebM is a tool that allows you to create WebM video files with changing aspect ratios.

If you're having issues, want to share your custom modes, or learn from the community join the Discord at the bottom of this readme.

## Dependencies

 * [NodeJS](https://nodejs.org)
 * [FFmpeg](https://ffmpeg.org)
 * FFprobe

### NodeJS
 
 To begin installation, you must install NodeJS first. You can find the NodeJS download [here.](https://nodejs.org/en/)

  After that, if prompted to restart, it is recommended to do so.

### FFmpeg

  After installing NodeJS, you need to download FFmpeg next. To install FFmpeg you need to go to [this](https://ffmpeg.org) link and select the green Download button.
Unzip the folder, move it to your downloads and then rename it to "ffmpeg".

  Right click the unzipped folder, select "Cut", direct to This PC, enter your C: drive and paste the ffmpeg folder in there.

  After moving the ffmpeg folder into your C: drive, open Command Prompt with administrator and run this: setx /m PATH "C:\ffmpeg\bin;%PATH%" (If, for some reason, you are unable to run Command Prompt with administrator permissions, you can hit the windows key, then type "edit environment variables for your account" and hit enter, then you need to click "Path", then click "Edit," then you click "New" and paste in "C:\ffmpeg\bin" and then make sure to click "Ok" in both windows).

  Now, type in "ffmpeg" to the command prompt. If you get an error, you need to log out and log back in, run ffmpeg inside of the command prompt window once more, and if you do not get an error you're all set. If you still get an error, you can try restarting your computer, and typing "ffmpeg" into the command prompt again.

## How to Run

  Once you've downloaded the WackyWebM folder by going to the GitHub repository and selecting the green "Code" button, then clicking "Download ZIP"

  Once the ZIP is fully installed, you need to extract the folder inside. After doing this, you are set. 
  
  Use `node wackywebm.js [mode] <file>` to use WackyWebM



## It's not my code, i just forked it and modified it from the guy that made it. If you have problems get the original one.
