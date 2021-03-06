# Book Spine Cataloguer
Use OpenCV and Tessaract to turn photos of a bookshelf into a catalogue of books.

## Getting Started
 - [Get OpenCV >= 3.2](http://docs.opencv.org/trunk/d7/d9f/tutorial_linux_install.html)

## Building
```
mkdir build
cd build
cmake ..
make
./DisplayImage image.png
```

## Roadmap

#### Application
 - [x] Set up OpenCV
 - [ ] Brighten an image using OpenCV
 - [ ] Locate the rectangles of a book spine for simple cases (1 book spine)
 - [ ] Set up Tessaract
 - [ ] Using Tessaract, OCR a very simple spine
 - [ ] OCR for many spines
 - [ ] Output in a format (JSON?)
 - [ ] Tweaking to support more cases and such
 - [ ] Link to frontend? Planning too far ahead at this point

#### Frontend
 - [ ] Basic page working on Google App Engine
 - [ ] Web interface to accept images
 - [ ] Run program from frontend, output JSON
