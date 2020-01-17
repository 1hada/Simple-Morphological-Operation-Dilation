# Make Space for the future

Hi ! The program follows the edge of a letter in order to make it more bold!

Here's a demo of what it can do !

![Directory Flasher Demo](https://raw.githubusercontent.com/1hada/Simple-Morphological-Operation-Dilation/master/dilation_demo.gif)



The program scans the image and uses a kernel to determine if it is on a letters edge.



### Prerequisites

I will be assuming that you have Ubuntu 18.04 for this first instruction. 

Get numpy or matplotlib libraries if you don't have them on your machine.
```
sudo apt-get install python3-numpy
sudo apt-get install python3-matplotlib
```

### If you only want to run the app.

Please allow a few minutes for the whole image to be scanned.

```
python3 MorphologicalOperation_Dialation.py
```

If you want to use your own black and white text image please change line # 18

```
chars = plt.imread('text_image_file_name.jpg')
```


