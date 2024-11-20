# Contrast-Correction
This project focuses on enhancing grayscale images by applying contrast adjustment techniques.

# Comments
The histogram of the original image is spread over a wide intensity range and shows a significant concentration between 100-200 pixel intensity. This shows that the original image has a generally balanced brightness and contrast structure.

During the contrast reduction process, pixel intensities are compressed to the range of 150 and 160. As a result of the process, the contrast of the image is significantly reduced and a less contrasty image is obtained where details are lost.
While the original histogram is spread over a wide intensity range, after the contrast reduction process, the histogram is concentrated only in the range of [150,160].
This situation is achieved by confining the details in the image to a limited range.
During the contrast enhancement process, the histogram is expanded to make the details in the image more distinct and the pixel intensities are rescaled according to the original distribution.

While the original histogram was spread over a wide intensity range, the histogram after the contrast enhancement process exhibited a homogeneous distribution. It was observed that the pixel values ​​were more distinct in both dark and bright areas.
