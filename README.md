# adaptive-thresholding-javascript

For images with uneven lighting, converting images to black and white with one threshold cannot achieve a good result.

![image](https://github.com/user-attachments/assets/76b5bdda-cf1b-4a09-9213-90141fa7cbe7)

![image](https://github.com/user-attachments/assets/42c104e0-00f6-4551-8a50-239e66b159b7)

For such cases, we can use adaptive thresolding, which calculates the threshold for each pixel based on neighbouring pixels.

![image](https://github.com/user-attachments/assets/a1ec094c-2d1a-41fe-89ae-c45fa0c32cac)


The demo in this repo contains two implmentation to perform adaptive thresholding.

* A pure JavaScript solution.
* A WASM solution based on [Dynamsoft Barcode Reader](https://www.dynamsoft.com/barcode-reader/overview/).

## Online Demos

* [Simple thresholding](https://tony-xlh.github.io/Color-Conversion-JavaScript/black-white.html)
* [Adaptive thresholding](https://tony-xlh.github.io/adaptive-thresholding-javascript/)

