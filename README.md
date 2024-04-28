Question 1
  Consider the following color image in PNG format (four-channel image). Write a program that
  sets the transparency of the smallest and darkest rectangle shown in the middle of the image to
  ZERO. In the output image, the central rectangle will not appear while the rest will be the same.
  You cannot use OpenCV for this task.

Question 2
  Create a function ConvertToGray(img). It takes an image as input. If the input image is color,
  then convert it into grayscale. Return the converted image. Use the following formula to
  convert a color image to grayscale. Display both grayscale and color images. You cannot use
  OpenCV for this task.

  imgGray = 0.299 × R + 0.587 × G + 0.11 × B
  Here R, G and B represent red, green, and blue channels respectively.

Question 3
  Create a function called StackHorizontal(img1, img2) that concatenates two images and
  returns the result. The function must check that both img1 and img2 have same size and
  channels. It should display error if size is not same. Display the obtained result. You cannot
  use OpenCV for this task.
  Hint: Create a larger 2D array that can hold both images and then copy the pixels one by one
  from the source images.
  
Question 4
  Write a function called FlipImg(img, flag). Img is the input image while flag can be 0 or 1. If
  the flag is 0 flip the image horizontally and when flag is 1 then flip vertically. Default flag
  should be 0. Return the flipped image and display both the original and flipped images. You
  cannot use OpenCV for this task.

Question 5
  Consider the following two grayscale images. These have same dimensions. Write a function
  that CommonImg(img1, img2) that finds the common area between two image and displays
  the result. If no common area is found then it must display a black image otherwise, it will
  show the common area. You cannot use OpenCV for this task.
