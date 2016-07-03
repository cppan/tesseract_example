# Tesseract Example

A very basic Tesseract-OCR example with CPPAN.

## Building & Testing

Prerequisites:

1. Download git, cmake and add them to PATH
2. Download CPPAN client (cppan) and add it to PATH too.

```
git clone https://github.com/cppan/tesseract_example tesseract_example
cd tesseract_example
cppan
mkdir build && cd build
cmake ..
cmake --build . --config Release
./bin/main ../img/phototest.tif
```
