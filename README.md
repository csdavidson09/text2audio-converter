
[![Build Status][1]][2]
[![Coverage Status][3]][4]

## Building the Project
* **gradle clean build**
* **gradle cobertura**

## Note
 
MARY TTS Server should be running locally.
* Step 1: Download the MARY TTS Standalone server
* Step 2: Start the MARY TTS Server at (installDir)/bin/maryserver.
* Step 3: Verify the MARY TTS Server status at http://localhost:59125/
* Step 4: Download FFmpeg (tested on 3.2.4)
* Step 5: Update WaveToMp3Converter.pathToFFmpegBin to the bin path where you installed FFmpeg
 
## Links
* http://mary.dfki.de/download/index.html
* https://github.com/marytts/marytts/releases/tag/v4.3.1
* [Mary TTS API Parameters details](http://blog.bickle.co.uk/it-technology/maryspeak-a-command-line-wrapper-for-marytts)
* https://ffmpeg.zeranoe.com/builds/

[1]: https://secure.travis-ci.org/SwaroopG/text2audio-converter.png
[2]: http://www.travis-ci.org/SwaroopG/text2audio-converter

[3]: https://coveralls.io/repos/SwaroopG/text2audio-converter/badge.svg
[4]: https://coveralls.io/r/SwaroopG/text2audio-converter
