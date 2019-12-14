Image Captiptioning is generating meaningful text from images. It's not converting text from images into strings. It's about making sense of the picture and describing what's going in the picture. 

Here's the pre-trained model which we uploaded after training it on Google Colab.


### Download Model
<a href="https://mega.nz/file/TkMkyYgC#NpL8WcKHMsYEMf-QCikFuIKk3A7_061KbXuziCraPZs">Download pre-trained model here.</a> Model trained on MSCOCO-2014 dataset.

Directory contain two sub-directories```photos```and```results```.

```photos``` All input images store in this directory.

```results``` output log file store here.


### Generating Captions
Run ```imageCaptioning.ipynb``` file for generating caption.


### Example
![plane.jpeg](imageCaptioning-master/photos/plane.jpeg)

caption generated for this image is,
```
./photos/plane.jpeg
0): a plane is flying in blue sky .
1): a plane is flying in cloudy sky .
2): a plane is flying in blue and cloudy sky .
``` 
