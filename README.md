
this script was made by zzoitu on discord do not trust anyone who claims to own this other then me




This script allows you remove the dead air in a audio file (mp3 or wav etc).

-----------------------------------------------------------------------------------------------------------------------

Requirements
Python: Make sure you have Python installed on your system. The script is written in Python 3.
https://www.python.org/ftp/python/3.11.4/python-3.11.4-embed-amd64.zip when you download python make sure to click "add to system path" at the bottom

Required Python Packages: pydub
You can install the python package using this pip command: pip install pydub

-----------------------------------------------------------------------------------------------------------------------

you will also need ffmpeg (required for reading/writing audio files in various formats)

to install ffmpeg you will need to do download it from the site https://www.gyan.dev/ffmpeg/builds/packages/ffmpeg-6.0-essentials_build.zip

then drag the bin folder to where ever you want then

go to system on your windows then on the right click Advanced system settings https://imgur.com/kkkwD8A 

then click (Environment Variables...) on the bottom right https://imgur.com/0x5ihoP

In the "Environment Variables" window find the "Path" variable under "System variables" and click "Edit." https://imgur.com/bFf5tDl

and add the path of the bin folder for me it was (D:\clips\dataset\bin) but yours will depend on where you downloaded it to

Click "OK" to save the changes.

Restart any open command prompts or terminals for the changes to take effect.

-----------------------------------------------------------------------------------------------------------------------

Audio File: Prepare the audio file you want to process and ensure it is in a supported format (e.g., mp3 or wav).

Running the Script

run the script by clicking it twice

then it will say " Enter the input file path: "

Navigate to the directory containing your audio file. (e.g., D:\clips\dataset\Test\Test.mp4)

Next, it will ask for the output format. Enter either "mp3" or "wav" (without quotes) to choose the desired output format. and do not add a . make sure its (wav) and not (.wav)

The script will then process the audio file, split it on silence, combine the chunks, and save the result in a new file named "output.mp3" or "output.wav" based on your selection.

Important Notes
The script uses the pydub library for audio processing, which relies on ffmpeg to read and write audio files in various formats. Make sure you have ffmpeg installed and accessible in your system's PATH.

The script splits the audio based on silence. The parameters min_silence_len and silence_thresh can be adjusted to fine-tune the silence detection. Feel free to modify these values within the script to suit your needs.

For best results, ensure your audio file has sufficient silence gaps between the parts you want to split. The script may not work optimally for continuous audio with no significant silence.

Make sure to follow the instructions carefully and enjoy using the audio splitter script! If you have any questions or encounter any issues, feel free to reach out for assistance. Happy audio processing!

-----------------------------------------------------------------------------------------------------------------------

to check how close it is to being done open (error_log.txt) the bigger the file the longer it will take 20 mins could take like 4 = 5 minutes on my bad pc
