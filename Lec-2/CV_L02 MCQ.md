# MCQs — Computer Vision Lecture 2: Image Enhancement (Pre-processing Stage)


## Questions

### Q1
**The main purpose of image enhancement in Computer Vision is:**

A) To reduce the file size of the image  
B) To improve the visual appearance of an image or to convert the image to a form better suited for analysis  
C) To change the image format  
D) To store images in a database  

**Correct Answer:** B

---

### Q2
**Image enhancement is considered part of which stage in the vision pipeline?**

A) Image acquisition  
B) Pre-processing  
C) Segmentation  
D) Recognition  

**Correct Answer:** B

---

### Q3
**Which of the following is NOT a common spatial domain image enhancement technique?**

A) Histogram equalization  
B) Image smoothing  
C) Fourier transform filtering  
D) Image sharpening  

**Correct Answer:** C

---

### Q4
**Point processing in image enhancement operates on:**

A) Groups of neighboring pixels  
B) Individual pixels independently  
C) The entire image spectrum  
D) Only image edges  

**Correct Answer:** B

---

### Q5
**Which of the following is an example of a point processing technique?**

A) Contrast stretching  
B) Median filtering  
C) Gaussian smoothing  
D) Edge detection  

**Correct Answer:** A

---

### Q6
**Contrast stretching is mainly used to:**

A) Increase image size  
B) Improve the dynamic range of intensity levels in an image  
C) Remove noise from an image  
D) Perform edge detection  

**Correct Answer:** B

---

### Q7
**Histogram equalization is a technique for:**

A) Reducing spatial resolution  
B) Redistributing the intensity levels of an image to achieve better contrast  
C) Removing blur  
D) Compressing images  

**Correct Answer:** B

---

### Q8
**In histogram equalization, the output image has:**

A) Intensities concentrated in a narrow range  
B) Intensities uniformly distributed across the full range  
C) Only black and white pixels  
D) Intensities reduced by half  

**Correct Answer:** B

---

### Q9
**A key difference between contrast stretching and histogram equalization is:**

A) Contrast stretching redistributes intensities, histogram equalization does not  
B) Histogram equalization redistributes intensities automatically, contrast stretching uses a linear transform  
C) Both are identical  
D) Histogram equalization reduces resolution  

**Correct Answer:** B

---

### Q10
**Spatial filtering techniques use:**

A) Fourier transforms  
B) Neighborhood operations on pixels  
C) Single pixel values only  
D) File compression  

**Correct Answer:** B

---

### Q11
**Filtering masks (kernels) are applied to an image by:**

A) Division  
B) Convolution  
C) Subtraction  
D) Resizing  

**Correct Answer:** B

---

### Q12
**Low-pass spatial filters are mainly used for:**

A) Image sharpening  
B) Image smoothing by reducing noise and details  
C) Histogram equalization  
D) Edge detection  

**Correct Answer:** B

---

### Q13
**Which of the following is an example of a low-pass filter?**

A) Laplacian filter  
B) Gaussian filter  
C) Sobel operator  
D) Prewitt operator  

**Correct Answer:** B

---

### Q14
**High-pass filters are primarily used for:**

A) Blurring images  
B) Enhancing edges and fine details  
C) Reducing intensity range  
D) Contrast stretching  

**Correct Answer:** B

---

### Q15
**Which of the following is an example of a high-pass filter?**

A) Median filter  
B) Laplacian filter  
C) Gaussian filter  
D) Average filter  

**Correct Answer:** B

---

### Q16
**Median filtering is mainly used to remove:**

A) Gaussian noise  
B) Salt-and-pepper noise  
C) Motion blur  
D) Frequency artifacts  

**Correct Answer:** B

---

### Q17
**Which filter replaces each pixel with the average of its neighborhood?**

A) Median filter  
B) Mean (average) filter  
C) Sobel filter  
D) Laplacian filter  

**Correct Answer:** B

---

### Q18
**The Gaussian smoothing filter is preferred over the mean filter because:**

A) It increases noise  
B) It weights nearby pixels more heavily than distant ones, preserving structure better  
C) It produces only binary images  
D) It removes edges completely  

**Correct Answer:** B

---

### Q19
**Which of the following is NOT a smoothing filter?**

A) Mean filter  
B) Gaussian filter  
C) Median filter  
D) Laplacian filter  

**Correct Answer:** D

---

### Q20
**Edge detection is typically achieved by:**

A) Low-pass filters  
B) High-pass filters such as Sobel, Prewitt, and Laplacian  
C) Histogram equalization  
D) Median filtering  

**Correct Answer:** B

---

### Q21
**Which operator uses horizontal and vertical masks to detect edges?**

A) Gaussian filter  
B) Sobel operator  
C) Median filter  
D) Histogram equalization  

**Correct Answer:** B

---

### Q22
**The Prewitt operator is similar to Sobel but differs in:**

A) Using different kernel weights  
B) Working only on color images  
C) Producing binary outputs  
D) Not detecting vertical edges  

**Correct Answer:** A

---

### Q23
**Which edge detection operator computes the second derivative of intensity values?**

A) Sobel operator  
B) Prewitt operator  
C) Laplacian operator  
D) Median filter  

**Correct Answer:** C

---

### Q24
**A drawback of the Laplacian operator is that:**

A) It is too slow for real-time use  
B) It is sensitive to noise  
C) It cannot detect edges  
D) It requires color images  

**Correct Answer:** B

---

### Q25
**The Laplacian of Gaussian (LoG) operator is used to:**

A) Detect colors  
B) Smooth the image first, then apply Laplacian for edge detection  
C) Compress images  
D) Equalize histograms  

**Correct Answer:** B

---

### Q26
**Canny edge detection includes which main steps?**

A) Thresholding only  
B) Smoothing, gradient calculation, non-maximum suppression, double thresholding, edge tracking  
C) Histogram equalization and contrast stretching  
D) Fourier analysis  

**Correct Answer:** B

---

### Q27
**Which method among edge detectors provides thin and continuous edges with less noise sensitivity?**

A) Sobel  
B) Prewitt  
C) Canny  
D) Laplacian  

**Correct Answer:** C

---

### Q28
**The primary goal of image denoising is to:**

A) Remove irrelevant details while retaining important features  
B) Compress image data  
C) Detect edges  
D) Convert images to grayscale  

**Correct Answer:** A

---

### Q29
**Gaussian noise appears in images as:**

A) Bright and dark isolated pixels  
B) Random variations following a normal distribution  
C) Repeated horizontal lines  
D) Large blurred regions  

**Correct Answer:** B

---

### Q30
**Salt-and-pepper noise appears as:**

A) Continuous wavy patterns  
B) Isolated white and black pixels scattered in the image  
C) Smooth gradient changes  
D) Only blurred regions  

**Correct Answer:** B

---

### Q31
**Which filter is typically used to reduce Gaussian noise?**

A) Median filter  
B) Gaussian smoothing filter  
C) Laplacian filter  
D) Histogram equalization  

**Correct Answer:** B

---

### Q32
**Which filter is most effective for reducing salt-and-pepper noise?**

A) Gaussian smoothing  
B) Median filtering  
C) Laplacian filtering  
D) Sobel operator  

**Correct Answer:** B

---

### Q33
**Why is median filtering better than mean filtering for salt-and-pepper noise?**

A) It averages all pixels equally  
B) It preserves edges while removing outliers  
C) It converts the image to binary  
D) It enhances frequency content  

**Correct Answer:** B

---

### Q34
**Which of the following statements about Gaussian smoothing is correct?**

A) It sharpens image details  
B) It blurs the image while reducing Gaussian noise  
C) It enhances contrast  
D) It is only used for binary images  

**Correct Answer:** B

---

### Q35
**A common drawback of smoothing filters is that:**

A) They may blur important edges and details  
B) They increase image size  
C) They convert grayscale to color  
D) They always reduce histogram contrast  

**Correct Answer:** A

---

### Q36
**Which edge detection technique combines smoothing and differentiation in a single process?**

A) Sobel  
B) Prewitt  
C) Laplacian of Gaussian (LoG)  
D) Median filter  

**Correct Answer:** C

---

### Q37
**An image filter that reduces high-frequency content while preserving low-frequency information is called:**

A) Low-pass filter  
B) High-pass filter  
C) Edge detector  
D) Histogram equalizer  

**Correct Answer:** A

---

### Q38
**An image filter that emphasizes high-frequency content is called:**

A) Low-pass filter  
B) High-pass filter  
C) Median filter  
D) Gaussian smoothing  

**Correct Answer:** B

---

### Q39
**The process of enhancing the edges of objects in an image is known as:**

A) Smoothing  
B) Sharpening  
C) Histogram equalization  
D) Blurring  

**Correct Answer:** B

---

### Q40
**Which type of filter emphasizes transitions in intensity?**

A) Low-pass filter  
B) High-pass filter  
C) Median filter  
D) Gaussian filter  

**Correct Answer:** B

---

### Q41
**In Canny edge detection, non-maximum suppression is used to:**

A) Remove weak edges  
B) Thin out detected edges by suppressing non-maximum gradient values  
C) Smooth the image  
D) Equalize histograms  

**Correct Answer:** B

---

### Q42
**The double thresholding step in Canny edge detection is used to:**

A) Create a binary image  
B) Classify edges into strong, weak, and non-relevant  
C) Remove Gaussian noise  
D) Compress images  

**Correct Answer:** B

---

### Q43
**Edge tracking in Canny detection is performed to:**

A) Connect weak edges if they are connected to strong edges  
B) Eliminate all weak edges  
C) Apply histogram equalization  
D) Blur the image  

**Correct Answer:** A

---

### Q44
**Which of the following is not an edge detection method?**

A) Sobel  
B) Prewitt  
C) Laplacian  
D) Histogram equalization  

**Correct Answer:** D

---

### Q45
**Which filter gives more weight to the central pixels of a neighborhood?**

A) Mean filter  
B) Gaussian filter  
C) Median filter  
D) Laplacian filter  

**Correct Answer:** B

---

### Q46
**Image sharpening can be achieved by:**

A) Adding the Laplacian result back to the original image  
B) Applying Gaussian smoothing only  
C) Using histogram equalization  
D) Applying median filtering  

**Correct Answer:** A

---

### Q47
**Which enhancement method is suitable for improving global contrast in an image?**

A) Histogram equalization  
B) Median filtering  
C) Gaussian smoothing  
D) Laplacian operator  

**Correct Answer:** A

---

### Q48
**Which method is more suitable for local contrast improvement?**

A) Global histogram equalization  
B) Adaptive histogram equalization  
C) Fourier transform  
D) Gaussian noise filtering  

**Correct Answer:** B

---

### Q49
**Which filter is nonlinear in nature?**

A) Mean filter  
B) Gaussian filter  
C) Median filter  
D) Laplacian filter  

**Correct Answer:** C

---

### Q50
**The main challenge in image enhancement is:**

A) Choosing the right technique that improves the image without distorting important information  
B) Reducing file size  
C) Converting images to grayscale  
D) Increasing storage capacity  

**Correct Answer:** A

---

## End of questions (50 total)

