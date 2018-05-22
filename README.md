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
