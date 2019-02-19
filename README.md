# DCGAN-on-Butterfly
This project uses the DCGAN to generate butterfly images.  
The train dataset is in the [butterfly.rar](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/Butterfly.rar), as shown below. 
![Image](https://raw.githubusercontent.com/gg1036419175/DCGAN-on-Butterfly/master/TrainDataset.jpg)  
These butterfly images were copied from the 《中国蝶类志》(ISBN:7-5349-1574-0) by me，as a total of 3447 and the size of the images is 96×96.The source codes are here [DCGAN](https://github.com/carpedm20/DCGAN-tensorflow/tree/master/assets). Put the folder named hudie2 into the folder named data.  
  
To train a model with Butterfly dataset:  
`python main.py --input_height 96 --output_height 96 --dataset hudie2 --crop True --train True --epoch 500`  
  
The generated butterfly images are as as follows:
image1:  
![Image](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/generated%20image1.png)  
image2:  
![Image](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/generated%20image2.png)  
image3:  
![Image](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/generated%20image3.png)  
image4:  
![Image](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/generated%20image4.png)  
image5:  
![Image](https://github.com/gg1036419175/DCGAN-on-Butterfly/blob/master/generated%20image5.png)  


