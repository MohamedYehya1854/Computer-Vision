# MCQs — Computer Vision Lecture 3: Feature Detection and Edge Detection

## Questions

### Q1
**Feature detection in computer vision is mainly used to:**

A) Detect colors in an image  
B) Identify distinctive image structures like corners, edges, or blobs  
C) Enhance image brightness  
D) Compress image data  

**Correct Answer:** B  
**Explanation:** Feature detection locates image regions with distinct characteristics that can be used for matching or tracking.

---

### Q2
**Edges in images represent:**

A) Uniform areas of brightness  
B) Rapid changes in intensity or color  
C) Low-frequency regions  
D) Smoothed gradients  

**Correct Answer:** B  
**Explanation:** Edges correspond to locations of strong intensity gradients, which often indicate object boundaries.

---

### Q3
**A key point or interest point is defined as:**

A) A pixel with constant intensity  
B) A point in the image where local neighborhood changes significantly in all directions  
C) A flat region  
D) A point outside image boundaries  

**Correct Answer:** B

---

### Q4
**Edge detection is important in computer vision because:**

A) It enhances the background  
B) It extracts structural information such as object boundaries and shape  
C) It reduces image resolution  
D) It adds artificial textures  

**Correct Answer:** B

---

### Q5
**The first step in detecting edges typically involves:**

A) Thresholding directly on pixel values  
B) Smoothing the image to reduce noise  
C) Using binary operations  
D) Histogram equalization  

**Correct Answer:** B  
**Explanation:** Edge detection begins with smoothing to minimize noise, preventing false edges.

---

### Q6
**Image gradients are computed using:**

A) Derivatives of the image intensity function  
B) Histogram analysis  
C) Fourier transforms  
D) Averaging  

**Correct Answer:** A  
**Explanation:** The gradient represents the rate of change of intensity, calculated using derivatives.

---

### Q7
**The gradient magnitude indicates:**

A) The direction of edges  
B) The strength of edges  
C) The smoothness of regions  
D) The pixel color intensity  

**Correct Answer:** B

---

### Q8
**The gradient direction represents:**

A) The color of the edge  
B) The orientation perpendicular to the edge  
C) The pixel position in the image  
D) The average brightness of the neighborhood  

**Correct Answer:** B

---

### Q9
**Which operator uses simple integer masks for computing gradients?**

A) Laplacian  
B) Sobel  
C) Gaussian  
D) LoG  

**Correct Answer:** B  
**Explanation:** The Sobel operator uses horizontal and vertical masks with integer weights for gradient estimation.

---

### Q10
**The Prewitt operator differs from Sobel in that:**

A) It uses uniform weights instead of weighted center values  
B) It cannot detect vertical edges  
C) It operates in the frequency domain  
D) It detects only corners  

**Correct Answer:** A

---

### Q11
**The Laplacian operator is based on:**

A) The first derivative of intensity  
B) The second derivative of intensity  
C) The color difference  
D) The histogram distribution  

**Correct Answer:** B

---

### Q12
**The Laplacian operator enhances:**

A) Low-frequency components  
B) High-frequency regions like edges and fine details  
C) Constant regions  
D) Noise removal only  

**Correct Answer:** B

---

### Q13
**The Laplacian of Gaussian (LoG) operator is used to:**

A) Combine edge detection and noise reduction  
B) Equalize histograms  
C) Sharpen colors  
D) Detect corners only  

**Correct Answer:** A

---

### Q14
**Zero-crossings in the Laplacian of Gaussian represent:**

A) The smooth regions  
B) Edge locations where intensity changes sign  
C) Color transitions  
D) Flat areas  

**Correct Answer:** B

---

### Q15
**The Canny edge detector is known for:**

A) Simplicity but poor accuracy  
B) Producing thin, continuous, and noise-resistant edges  
C) Detecting only horizontal edges  
D) Being non-linear and inaccurate  

**Correct Answer:** B

---

### Q16
**Which of the following is a step in the Canny edge detection algorithm?**

A) Fourier transformation  
B) Gradient computation and non-maximum suppression  
C) Image quantization  
D) Morphological erosion  

**Correct Answer:** B

---

### Q17
**In Canny edge detection, the double threshold step helps to:**

A) Convert the image to binary  
B) Distinguish between strong and weak edges  
C) Remove gradient noise  
D) Equalize the histogram  

**Correct Answer:** B

---

### Q18
**Edge linking in the Canny algorithm is used to:**

A) Discard all weak edges  
B) Connect weak edges if they are adjacent to strong ones  
C) Remove color transitions  
D) Perform convolution  

**Correct Answer:** B

---

### Q19
**Which of the following filters detects edges in multiple orientations?**

A) Gaussian filter  
B) Steerable filter  
C) Median filter  
D) Prewitt filter  

**Correct Answer:** B  
**Explanation:** Steerable filters can be adjusted to detect edges at arbitrary orientations.

---

### Q20
**The purpose of smoothing before edge detection is to:**

A) Remove noise and avoid false edges  
B) Increase edge thickness  
C) Highlight intensity transitions  
D) Reduce computation time  

**Correct Answer:** A

---

### Q21
**Noise can cause false edges because:**

A) It reduces gradients  
B) It introduces random intensity changes  
C) It increases brightness  
D) It smooths the image  

**Correct Answer:** B

---

### Q22
**The Marr-Hildreth edge detection method is based on:**

A) Sobel operator  
B) Laplacian of Gaussian  
C) Prewitt operator  
D) Canny detector  

**Correct Answer:** B

---

### Q23
**Color edge detection considers:**

A) Only grayscale intensity  
B) Gradients computed for each color channel (R, G, B)  
C) Histogram equalization per channel  
D) Binary thresholding  

**Correct Answer:** B

---

### Q24
**In color edge detection, combining gradients from multiple channels improves:**

A) Image compression  
B) Edge accuracy and completeness  
C) Noise intensity  
D) Pixel duplication  

**Correct Answer:** B

---

### Q25
**Edge linking is the process of:**

A) Merging edge fragments into meaningful boundaries  
B) Enhancing histogram contrast  
C) Removing small details  
D) Smoothing the entire image  

**Correct Answer:** A

---

### Q26
**Edge linking can be performed using:**

A) Gradient direction and magnitude continuity  
B) Random thresholding  
C) Binary erosion  
D) Frequency filtering  

**Correct Answer:** A

---

### Q27
**A good edge detector should produce:**

A) Many edges with thick lines  
B) Fewer, thin, and accurate edges that correspond to real object boundaries  
C) Blurred edge maps  
D) Color gradients only  

**Correct Answer:** B

---

### Q28
**Gradient-based edge detectors respond strongly to:**

A) Constant regions  
B) Rapid changes in intensity  
C) Homogeneous areas  
D) Histogram peaks  

**Correct Answer:** B

---

### Q29
**Which operator is based on the difference between neighboring pixels?**

A) Sobel  
B) Prewitt  
C) Both A and B  
D) Gaussian  

**Correct Answer:** C

---

### Q30
**An ideal edge has which characteristics?**

A) Gradual intensity change  
B) Sharp intensity discontinuity  
C) Uniform color  
D) No gradient  

**Correct Answer:** B

---

### Q31
**Edge localization refers to:**

A) The accuracy of edge position  
B) The number of detected edges  
C) The color accuracy  
D) The smoothing factor  

**Correct Answer:** A

---

### Q32
**Which step in edge detection ensures thin edges?**

A) Thresholding  
B) Non-maximum suppression  
C) Smoothing  
D) Convolution  

**Correct Answer:** B

---

### Q33
**A high threshold in Canny detection results in:**

A) More detected edges including noise  
B) Fewer but stronger edges  
C) Complete loss of all edges  
D) Wider edge lines  

**Correct Answer:** B

---

### Q34
**A low threshold in Canny detection results in:**

A) Only strong edges detected  
B) More edges, including weak and noisy ones  
C) No edges detected  
D) Blurred results  

**Correct Answer:** B

---

### Q35
**The main limitation of the Laplacian method is:**

A) Sensitivity to noise  
B) Complexity  
C) Inability to detect vertical edges  
D) Poor localization  

**Correct Answer:** A

---

### Q36
**Sobel and Prewitt filters are examples of:**

A) Gradient-based edge detectors  
B) Second derivative operators  
C) Frequency-based filters  
D) Histogram equalizers  

**Correct Answer:** A

---

### Q37
**In the context of edge detection, the term 'gradient' refers to:**

A) The change in color  
B) The rate of change of intensity in a specific direction  
C) The mean intensity value  
D) The histogram slope  

**Correct Answer:** B

---

### Q38
**Edges can be categorized as:**

A) Step, ramp, ridge, or roof edges  
B) Bright, dark, and neutral  
C) Thick and thin  
D) Global and local  

**Correct Answer:** A

---

### Q39
**A step edge occurs when:**

A) There is an abrupt change in intensity  
B) The intensity changes gradually  
C) The region is uniform  
D) There is color blending  

**Correct Answer:** A

---

### Q40
**A ramp edge occurs when:**

A) The intensity transition is gradual over several pixels  
B) The image is binary  
C) The noise level is low  
D) The image has high contrast  

**Correct Answer:** A

---

### Q41
**Ridge edges are often found in:**

A) Object boundaries  
B) Thin elongated bright structures such as veins or roads  
C) Low contrast regions  
D) Uniform areas  

**Correct Answer:** B

---

### Q42
**Edge detection performance depends on:**

A) Noise level, illumination, and texture  
B) File size  
C) Image format  
D) Display brightness  

**Correct Answer:** A

---

### Q43
**The main objective of feature detection is to:**

A) Identify and describe regions of interest for matching and recognition  
B) Reduce image size  
C) Compress image color  
D) Adjust brightness  

**Correct Answer:** A

---

### Q44
**Corner points differ from edges because:**

A) They have intensity change in only one direction  
B) They have significant changes in intensity in all directions  
C) They are flat regions  
D) They do not have gradients  

**Correct Answer:** B

---

### Q45
**Edges typically occur:**

A) In homogeneous regions  
B) Where there are discontinuities in depth, color, or illumination  
C) In frequency domain only  
D) At image centers  

**Correct Answer:** B

---

### Q46
**The difference between edge detection and feature detection is:**

A) Edge detection focuses on intensity changes, feature detection on distinctive patterns  
B) Both detect only color changes  
C) Feature detection ignores corners  
D) Edge detection uses histograms only  

**Correct Answer:** A

---

### Q47
**Edge detection algorithms are evaluated based on:**

A) Detection accuracy, localization, and response  
B) Image color depth  
C) Filter kernel size only  
D) Histogram width  

**Correct Answer:** A

---

### Q48
**The second derivative-based detectors (like Laplacian) are sensitive to:**

A) Large regions  
B) Noise and small intensity variations  
C) Flat areas  
D) Binary transitions  

**Correct Answer:** B

---

### Q49
**Edge maps are binary representations that:**

A) Indicate edge and non-edge pixels  
B) Store pixel colors  
C) Display gradient values  
D) Contain smoothing filters  

**Correct Answer:** A

---

### Q50
**A key advantage of the Canny edge detector is:**

A) Multi-step process providing optimal detection, localization, and response  
B) Fastest execution with low accuracy  
C) Minimal computation without smoothing  
D) Works only on color images  

**Correct Answer:** A

---

## End of Questions

