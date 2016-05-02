The following steps are were tested on Ubuntu 15.10 on Intel i5 based system.
Steps to setup the environment for development:
• Download OpenCV source file from this link:
http://opencv.org/downloads.html .
You will need version 3 and above.
• Download OpenCV-contrib form this link:
https://github.com/Itseez/opencv contrib.
• You will need to install cmake or cmake-gui using sudo apt-get command. Use sudo apt-get install cmake OR sudo apt-get install cmakegui
• Download tesseract-ocr source from this link :
https://github.com/tesseract-ocr/tesseract
and follow the instructions given at :
https://github.com/tesseract-ocr/tesseract/wiki/Compiling
to compile the project from source. It is important to compile from
source because on then you will get the *.so files which will be required
by OpenCV.
• After installing tesseract-ocr compile and install OpenCV with the contrib library and tesseract using cmake OR cmake-gui. Make sure that
you give the right paths while configuring the source.
• You can use Netbeans IDE for development which can be downloaded
from here:
https://netbeans.org/features/cpp/. Make sure that you set the
path variables correctly so that all the dependencies are resolved.
• A handy tool in linux for working with videos is FFMPEG. You can
download it using the following command: sudo apt-get install ffmpeg.
