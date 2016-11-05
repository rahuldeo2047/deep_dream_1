# deep_dream_challenge
Deep Dream Challenge code by @SIrajology on [Youtube](https://youtu.be/MrBzgvUNr4w)

##Overview

This is the code for the Deep Dream challenge for 'Learn Python for Data Science #5' by @Sirajology on [YouTube](https://youtu.be/MrBzgvUNr4wY). The code uses the Tensorflow Machine Learning library to generate a trippy image
from a given input image. 

##Dependencies

* numpy (http://www.numpy.org/)
* functools (usually comes preinstalled with python [link](http://stackoverflow.com/questions/17871784/installing-functools-gives-me-attributeerror-module-object-has-no-attribute-c))
* PIL (http://stackoverflow.com/questions/20060096/installing-pil-with-pip)
* tensorflow (to be safe run with Virtualenv)(https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html#pip-installation)
* matplotlib (http://matplotlib.org/1.5.1/users/installing.html)
* urllib (https://pypi.python.org/pypi/urllib3)
* os (this also comes preinstalled)
* zipfile (?)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

Meanwhile I got problem with matplotlib: http://tkinter.unpythonic.net/wiki/How_to_install_Tkinter solves it.

do 

wget https://storage.googleapis.com/download.tensorflow.org/models/inception5h.zip

extract to ../data/

copy paste the tensorflow_inception_graph.pb

in data folder

##Demo Usage

Once dependencies installed via pip, run the demo script in terminal via

```
python deep_dream.py
```

##Challenge statement

The instructions are 

1. Add a function to the existing deep dream python file that converts not just an image, but a video clip to deep dream. 

*HINT* Think of a video as a collection of images (frames). 

If you want to use your own template, that's fine too. Submit your code in the comments section and I'll announce the winner in
the next video. Good luck!

##Credits

Always [Sirajology](https://github.com/llSourcell)
Thanks Google and [Liu](https://github.com/LiuzcEECS) I've reformatted this code to make it easier to grok. 
