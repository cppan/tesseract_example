# With CPPAN


# Tesseract Example

A very basic Tesseract-OCR example with C++ Archive Network building.

## Building

Prerequisites:

1. Download git, cmake and add them to PATH
2. Download the latest CPPAN (https://cppan.org/) client from https://cppan.org/client/
3. Add cppan to PATH too.
4. Run

```

Run `cppan --build main.cpp` to build your simple application that uses tesseract.
```

## Testing

1. Download tesseract english data to `tessdata` dir near the `main` binary.
2. Copy test image `img/phototest.tif`
3. Run ``main phototest.tif``
