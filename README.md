# Tesseract Example

A very basic Tesseract-OCR example with C++ Archive Network building.

## Building

Supported OS: Windows (32, 64).

Linux and macOS may fail because of issues with dependent image packages.

Prerequisites:

1. Download git, cmake and add them to PATH
2. Download the latest CPPAN (https://cppan.org/) client from https://cppan.org/client/
3. Add cppan to PATH too.

```
git clone https://github.com/cppan/tesseract_example tesseract_example
cd tesseract_example
cppan
mkdir build && cd build
cmake ..
cmake --build . --config Release
```

## Testing

Download tesseract english data to `tessdata` dir near the `main` binary, copy test image `img/phototest.tif` and run
```
main phototest.tif
```
