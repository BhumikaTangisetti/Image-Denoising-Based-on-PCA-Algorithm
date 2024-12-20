
Image denoising:-
Image denoising is a process where noise (unwanted random variations in pixel values) is removed from an image to improve its quality. Using Principal Component Analysis (PCA) for image denoising is an interesting and effective approach that leverages PCA's ability to reduce dimensionality and capture the most significant features of the data.


About The Program:-
In this program we are going to add the noise like salt noise and the pepper noise to the original image  and  we are going to remove noise by applying the algorithms like Principal Component Analysis (PCA) . We are measuring the accuracy in terms of PSNR(Power Signal to Noise) ratio in dB


How to run the Program:-
Specify the location of the program and test images(using D Drive)
Open command prompt And go to D Drive from your current location in cmd
Type the command :-
D:\>python 143.py
Then it will display image in form of Original image, Noisy image, Denoised image. After closing the window of displayed image it will display another image from the testing images folder.After completion of all the images from the testing images folder it will give the Average PSNR of all images in dB.
Output:-
Average PSNR across all images: 38.50 dB