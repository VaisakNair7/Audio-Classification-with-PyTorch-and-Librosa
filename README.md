# Audio Classification with PyTorch and Librosa
This notebbok contains Python code for classifying audio files. Librosa has been utilized to load audio files and create mel-spectrograms and PyTorch Resnet50 for classifying audios using transfer learning. 

<br>
The dataset used is Environmental Sound Classification 50 , which contains 50 classes with 40 examples per class.<br>
Link to dataset - https://github.com/karolpiczak/ESC-50

<br>

## Spectrograms

![rain](https://user-images.githubusercontent.com/37840005/169344323-0eae14fa-2801-4adf-9f9d-5f2c95a0939d.png)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Rain

![siren](https://user-images.githubusercontent.com/37840005/169344371-0db5210c-5ee6-49ef-8e22-796e7a3de0ba.png)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Siren

<br>
The Resnet50 model produces 66.6% accuracy on validation split when trained for 10 epochs. Performance can be increased by training it for more epochs or using a bigger and better model.

## Libraries

* PyTorch
* torchvision
* Librosa
* Matplotlib
* Numpy
* Pandas

