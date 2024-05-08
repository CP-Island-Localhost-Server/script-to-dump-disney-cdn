# Usage:


## CD into the bin folder and then run:

wayback_machine_downloader https://1263cf72.content.disney.io/* -a -e


## Requirements:

You will need Ruby installed. I am recommending the installer with the DevKit packages. The Windows installer can be found here: https://rubyinstaller.org/


## Notes:

I have sat the dump cooldown to 10 seconds, otherwise the script missed a lot of files and the Wayback Machine Internet Archive's API would limit your connections due to how fast the script was moving. After it gets done dumping the CDN, the dumped folder should be around 17.6GB. You might have to re-run the download command a few times to be able to get everything downloaded correctly.
