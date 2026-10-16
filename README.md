# Image-Processing-Lab-8

Applies erosion, dilation, opening, and closing to a synthetic binary image (4 shapes + salt noise) using a 5×5 square kernel and a circular kernel (radius 5), then compares the results.

**Requirements:** Python 3, OpenCV, NumPy, Matplotlib (`pip install opencv-python numpy matplotlib`)

**Run:** open the notebook in Jupyter or Colab and run all cells in order.

**Key finding:** opening removes the noise and keeps the solid shapes with both kernels; the circular kernel rounds the rectangle's corners, while the square kernel keeps them sharp.

