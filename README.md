# Video Doorbell, Lab 7

*A lab report by Ziyu Liu*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[video](https://youtu.be/3OFHXAw95xA)

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

Other than the SerialPort input from USB, we also need to initialize input for node-webcam to enable functions for webcamera.

**b. Include a video of your working video doorbell**

[video doorbell](https://youtu.be/cMnmYMs_4Rs)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

The package I was using was the GM. The GM package is a pretty comprehensive one that have so many features that can add aftereffect to the pictures that you taken. I tried some functions such as resize, blur, contrast and other functions that can be used to change the image.

**b. Upload a video of your working modified project**

I added a button that is the blur button that blur the image after your take an image. However, on the second day, I cannot connect to the pi and do not have any idea why I cannot ping or ssh the pi. I used image that I saved with blur implementation last day and here is the [original image.](https://github.com/dlydb/IDD-Fa19-Lab7/blob/master/test_picture.jpg) [blur image](https://github.com/dlydb/IDD-Fa19-Lab7/blob/master/blur.jpg)
