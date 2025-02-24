# Color Compression
This project implements color compression using the K-means algorithm. The goal is to reduce the number of colors in an image while preserving its visual appearance.

### Overview
Color compression is a technique used to reduce the number of distinct colors in an image. This is particularly useful for reducing the file size of images and for various image processing tasks. In this project, we use the K-means clustering algorithm to achieve color compression.

### K-means Algorithm
The K-means algorithm is an iterative method that partitions the data into K clusters. The algorithm works as follows:
1. Initialize K centroids randomly or by selecting K points from the data.
2. Assign each data point to the nearest centroid.
3. Update the centroids by calculating the mean of all data points assigned to each centroid.
4. Repeat steps 2 and 3 until the centroids do not change significantly or a maximum number of iterations is reached.

## Getting Started
**Install Dependencies**
```bash
pip install -r requirements.txt
```

**Run the Jupyter Notebook**

```bash
jupyter notebook color-compression.ipynb
```

### How to Use
1. Provide the path to the image you want to compress.
2. Specify the number of colors (K) you want in the compressed image.
3. Choose the initialization method for the centroids (random or in_pixels).
4. Run the algorithm to compress the image.
5. The compressed image will be displayed and saved in the same directory as the original image.

### Results
The compressed image will have fewer colors, but it will still retain the visual appearance of the original image. This can be useful for reducing the file size of images and for various image processing tasks.

### Conclusion
This project demonstrates the use of the K-means algorithm for color compression. By reducing the number of colors in an image, we can achieve significant file size reduction while maintaining the visual quality of the image.
