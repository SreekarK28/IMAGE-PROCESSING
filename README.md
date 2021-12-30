# Image Steganography
# Steps to run the code:
1) Download and install python onto your system or the system you'll use to run the code.The link for downloading python can be found [here](https://www.python.org/downloads/).
2) Install [VScode](https://code.visualstudio.com/download), follow the installation instruction mentioned in their website.
3) Install the requirements mentioned in the 'requirements.txt' file , steps to install from packages from a requirements.txt file can be found [here](https://github.com/SreekarK28/Image-Steganography/blob/main/requirements.txt)
4) without changing the name of any directories, run the hiding text in image steganography.py file
5) press 1 to encode
   press 2 to decode
   press 3 to comapare the two new images with original image.
   
6) Encoding:
   i)   After pressing 1, enter the image name with extension which is in Original_image folder.
   ii)  enter the secret message you want to hide.
   iii) Encoding is done, images are stored in Encoded_image folder.
   
7) Decoding:
   i)  Press 2 after encoding is done.
   ii) The text files which contain secret message for each algorithm are saved in Decoded_output folder. 
  
8) Comparison:
   i)  press 3, after decoding is done.
   ii) its shows the graph of MSE values for both algorithms, close the graph to proceed next.
   iii) next it shows the graph of PSNR values for both algorithms, close that graph also to run the remaining code.
   iv)  after closing the both graphs, Comparison.xls will be created in Comparison_result folder which shows the MSE and PSNR values in a table.
   
