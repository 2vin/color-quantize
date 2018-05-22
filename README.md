# color-quantize
Image segmentation using K-Means clustering technique

# Compile
g++ color-quantize.cpp -o executable \`pkg-config --cflags --libs opencv\` -std=c++11

# Usage
./executable image_path number_of_clusters

# Example
./executable /home/2vin/myphoto.jpg 5
(Note: Substitute "/home/2vin/myphoto.jpg" by path of an existing image)

Here is a demo of performing different number of clusters on same image:

Raw image    
![alt text](https://github.com/2vin/color-quantize/blob/master/data/test.jpg)

Number of clusters = 2    
![alt text](https://github.com/2vin/color-quantize/blob/master/data/result_2.jpg)

Number of clusters = 4    
![alt text](https://github.com/2vin/color-quantize/blob/master/data/result_4.jpg)

Number of clusters = 8    
![alt text](https://github.com/2vin/color-quantize/blob/master/data/result_8.jpg)

Number of clusters = 16    
![alt text](https://github.com/2vin/color-quantize/blob/master/data/result_16.jpg)
