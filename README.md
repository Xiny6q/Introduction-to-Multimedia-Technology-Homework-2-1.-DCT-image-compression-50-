Download link :https://programming.engineering/product/introduction-to-multimedia-technology-homework-2-1-dct-image-compression-50/


# Introduction-to-Multimedia-Technology-Homework-2-1.-DCT-image-compression-50-
Introduction to Multimedia Technology Homework #2 1. DCT image compression (50%)
1. DCT image compression (50%)

Transform the image cat1.jpg & Barbara.jpg from spatial domain to frequency domain with DCT

for compression and reconstruct the compressed image using inverse DCT with reduced numbers

and bits of DCT coefficients.

DCT compression process:

Divide the image into blocks of 8 × 8 pixels and apply 2D DCT for each block.

For each block, only keep the lower-frequency (i.e. upper-left n-by-n) coefficients in the 2D DCT domain by setting the remaining coefficients to zero.

Apply uniform quantization for DC and AC coefficients with suitable quantization tables and save each coefficient with m bits.

Reconstruct the image by taking inverse 2D DCT with the modified DCT coefficients for each block.

Implement the simplified DCT compression process above for n = 2, 4 and m = 4, 8 respectively, and then apply it to the attached image.

Show the reconstructed images for these four different cases. [2×4 images]

Compute the compression ratios and the PSNR values of these four reconstructed images and discuss the best rate-distortion choice.

Use the same process in (a) with image transformed to YCbCr color space with 4:2:0 chrominance subsampling.

Show the reconstructed images in RGB space. [2×4 images]

Compute the compression ratios and the PSNR values of the four reconstructed images and discuss the best rate-distortion choice at the report.

Report:

Compare the differences between the results with DCT compression performed in two color spaces in (a) and (b) and discuss the results.

2. Create your own FIR filters to filter audio signal (40%)

“HW2_Mix.wav” is a mix of 3 songs. Based on the ideal impulse responses given in slide #72 and the windowing functions in slide #75, you need to design and apply different FIR filters in time domain to separate the three audio signals from the given audio file. You can refer to the algorithm on slide #76. Next, you are asked to reduce the sampling rates of signals and compare them. Finally, the output audio signals are too simple so you should apply one-fold echo and multiple-fold echo (slide #69) to produce wonderful music. Please following the steps given below:

Transform the input signal into frequency domain.

Implement 3 different FIR filters to separate the three audio signals with Blackmann window function (You have to pick the appropriate window size and cut-off frequency). Please Implement 1-D convolution on the input signal of the given audio with your filters.

Reduce the sampling rates of the three separated songs to 2000Hz.

Apply one-fold echo and multiple-fold echo on the audio signal that pass through the low-pass filter. (Please use the audio files before reducing sampling rates)

For question2 you need to turn:

Image results:

The spectrum of the input signal.

The spectrums of the output signals. (Before echo.) [3 images]

The spectrums of the filters. [3 images]

The shapes of the filters (time domain) [3 images]

Audio results:

Store the three filtered audio files before reducing the sampling rates and name

“Filter1Name_[para1]_[para2].wav”. “Filter2Name_[para1]_[para2].wav”. “Filter3Name_[para1]_[para2].wav”.

Store the filtered audio files after reducing the sampling rates and name

“Filter1Name_[para1]_[para2]_2kHZ.wav”. “Filter2Name_[para1]_[para2] _2kHZ.wav”. “Filter3Name_[para1]_[para2] _2kHZ.wav”.

Store the echo audio files and name “Echo_one.wav” and “Echo_multiple.wav”.

Report:

Discuss how you determine the filters.

How you implement the filter and convolutions to separate the mixed song and one/multiple fold echo?

Compare spectrum and shape of the filters.

Briefly compare the difference between signals before and after reducing the sampling rates.

Reminder

You should not use any function which can generate the result directly in each step.

Your code should display and output your results so that we can judge if your code works correctly.

You should provide a README file about your execution instructions.

Please compress your code, input images, result images, report and README in a zip file named HW2_{Student-ID}.zip and upload it to eeclass.

If you encounter any problem, please post your problems/questions on eeclass.

Please follow the file structure below:
