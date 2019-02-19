# DCGAN-on-Butterfly
This project uses the DCGAN to generate butterfly images.  
The train dataset is in the [butterfly.rar](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/Butterfly.rar), as shown below. 
![Image](https://raw.githubusercontent.com/gg1036419175/DCGAN-on-Butterfly/master/TrainDataset.jpg)  
These butterfly images were copied from the 《中国蝶类志》 by me，as a total of 3447 and the size of the images is 96×96.  
The source codes are here [DCGAN](https://github.com/carpedm20/DCGAN-tensorflow/tree/master/assets).  
Put the folder named hudie2 into the folder named data
To train a model with downloaded dataset:  
`python main.py --input_height 96 --output_height 96 --dataset hudie2 --crop True --train True --epoch 500`

