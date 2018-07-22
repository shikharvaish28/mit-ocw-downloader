
# MIT-OCW Downloader

Download all video lectures from a MIT-OCW course with a single command.

## Features

* Intentionally detailed names, so that it will display and sort properly
    on most interfaces (e.g., MX Video, or VLC on Android devices).
  * URL and lecture name filters to download only video files.
  * Tested on Mac (Python 3.6).

## Instructions to download OCW using this

* [mit-ocw-scrapper][1] basically needs a link to the video lectures page of a MIT-OCW course
    (which of course has video lectures). The link would be something like [<https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/lecture-videos/]> 

  * Make a [virtual environment][4] for this project on your local machine and activate it.
  
  * Install all of the dependencies from ```requirements.txt``` file.
  
  * Copy the ```download.py``` file to the folder where you want to download the video lectures.
  
  * Run ```python download.py <Lecture Link>``` or ```python3 download.py <Lecture Link>``` in case you have more than one versions of python installed on your system.  
  
  * Voila! Download must have started by now.
  
## Contributions

   If you want to contribute to this project, feel free to fork it and send a PR :)

## Coming Up

* [mit-ocw-dl][1] only supports video content of the course presently
  but attempts are on to make it download entire contents (lecture slides, assignments, solutions etc.)

## Contact  

  Shoot a mail at shikarvaish@gmail.com
  
## Author

  [Shikhar Vaish][2]

## Inspiration

  [coursera-dl/coursera][3]

[1]: https://github.com/shikharvaish28/mit-ocw-scrapper
[2]: https://shikharvaish.me
[3]: https://github.com/coursera-dl/coursera
[4]: https://www.pythonforbeginners.com/basics/how-to-use-python-virtualenv/
