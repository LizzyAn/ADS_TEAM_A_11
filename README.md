# ADS_TEAM_A_11
                                                  Abstract
                                                   
Tamil is a script-based language with characters that are written in various styles and fonts. 
Recognizing Tamil letters from images is a challenging task due to the high similarity and variability among the characters.
The intricate challenge of Prehistoric Tamil character recognition from stone images, which is inherently more complex due to the characters' intricate shapes, numerous holes, loops, and curves. 
Despite previous efforts, significant challenges persist in this domain. This study proposes an innovative approach employing Deep Neural Networks (DNN) to tackle the issue of recognizing prehistoric Tamil characters. 
The image preprocessing pipeline includes binarization, denoising, character segmentation, and size normalization, which are crucial steps for enhancing recognition accuracy.Moreover, feature extraction plays a pivotal role, 
and in this context, both Fourier feature mappings and Zernike moments are employed as effective feature descriptors, enriching the recognition process with valuable information. 
Character classification is performed utilizing Back Propagation DNN, while optimization of neural networks leverages the Simplex method during backpropagation. 
The proposed system strives to provide an improved approach to address the inherent complexities of prehistoric Tamil character recognition, 
offering a promising avenue for historical and archaeological research applications.

Steps to run the Project:
1.Import Libraries
Ensure that all dependencies are correctly installed by executing the following command:
pip install -r requirements.txt
2. Correct Skew
Apply the correct_skew function to correct any skewness present in the input image.
3. Preprocess Image
Convert the image to grayscale, apply thresholding, and remove lines to enhance character visibility.
4. Character Segmentation
Identify contours in the preprocessed image, filter out small contours, and create bounding rectangles around characters.
5. Boxing the characters
Optionally, draw rectangles around identified characters for visual reference.
6. Display Processed Image
Display the processed image to verify the effectiveness of the preprocessing steps.
7. Denoising
Apply various filters for denoising, including median blur and Gaussian blur.
8. Install OCR
Install Tesseract OCR and its dependencies as outlined in the Setup section.
9. Perform OCR
Utilize Tesseract OCR to extract text from each segmented character.
10. Display Characters
Optionally, display each segmented character separately for visual inspection.
11. Filter Contours
Filter out contours based on their area to exclude smaller artifacts.
12. Save Characters
Save segmented characters as individual images for further analysis if needed.
13. Display Final Image
Optionally, display the final image with rectangles around characters for a comprehensive view.
14. Clean Text
Clean up whitespaces in the recognized text to improve readability.
15. Define Tamil Mapping
Define a mapping of recognized characters to meaningful sounds in Tamil.
16. Display Final Result
Display the final recognized text with meaningful Tamil characters.
Dependencies
Ensure that the following dependencies are installed:
OpenCV
NumPy
Matplotlib
SciPy
Imutils
Pytesseract
Langid
