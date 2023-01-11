# Image Comparison GUI

This GUI is a tool for comparing the similarity of two images. The comparison is done using Centroid Linkage Clustering of key-points and graph similarity matching. The GUI allows users to select two images and displays the images along with the similarity score between them.

## Method
The images are compared using a combination of two techniques: Centroid Linkage Clustering and graph similarity matching. First, SIFT features are extracted from the images and clustered using Centroid Linkage Clustering. The clustering results are then used to construct a graph of the image, and the similarity between the two images is calculated using graph similarity matching.

## Limitations
1. The GUI is limited to comparing two images at a time.
2. The images must be in JPG format.
3. The comparison is limited to the method described above and may not be suitable for all types of images or use cases.
4. The tool may produce false positives or false negatives depending on the image dataset and the threshold value used.

## Usage
1. Clone the repo
2. Run the GUI FINAL PROJECT MULTIMEDIA FORENSICS.ipynb script
3. Select an original image and a forgery image
4. Click compare
5. Result of the comparision will be displayed as similarity score and show the original and forgery images side by side.
