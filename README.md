# Image-Anti-OCR

### In the background

Images containing political infomation that you want to share to social platforms, but it could be blocked by govt.

To avoid images being blocked, this repo makes sure you can successfully share images in a political censorship machine.

The anti algrithm was copied from [anti-ocr.git](https://github.com/yuzu233/anti-ocr.git).

### how to run it:

``` shell script
cd Image-Anti-OCR
python3 -m http.server
```

And then you can open [http://{IP}:8000/](http://localhost.8000) in your web-browser.



### In addition

I'm very sorry! this algorithm may has little bug. Not all images works with it very well.

After executed some of special size of image, this algorithm will make human beings not recognize words from covered images. In that case, you can try to edit js to get it be recognized.
