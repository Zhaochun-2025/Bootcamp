This project processes a 500x500 grayscale PNG image by applying a Gaussian blur, analysing histogram differences, and saving processed images.
LLM used: This project was written with guidance from OpenAI's GPT-3.5 model

Features includes
Gaussian blur applied to the original image
Histograms plotted for the original and blurred versions of pixel intensity (x-axis) and frequency (y-axis)
Kolmogorov-Smirnov test to determine the statistical difference between the original and blurred image histograms

Output includes:
Original image (PNG)
Blurred image (PNG)
Histogram (pixel intensity vs frequency) of the original image and the blurred image
Downscaled 250x250 image

Requirements:
install numpy, matplotlib. pyplot, scipy and pillow.
