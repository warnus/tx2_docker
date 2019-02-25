
# Jetson TX2 Docker

## Getting Started

```
$ docker pull warnus/tx2-opencv:0.1
```

```
$ ./tx2-docker run -it warnus/tx2-opencv:0.1
```

## Check OpenCV Version on container

```
$ python3
Python 3.5.2 (default, Nov 12 2018, 13:43:14)
	[GCC 5.4.0 20160609] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>> import cv2
	>>> cv2.__version__
	'3.4.1-dev'
```
