# MCQs — Computer Vision Lecture 6: Feature Detection and Matching (Corner Detection)

**Course:** Computer Vision  
**Lecture:** 6 – Feature Detection and Matching (Corner Detection)  
**Instructor:** [Not Specified]  
**Purpose:** Multiple Choice Questions (MCQs) covering all lecture contents. Each question includes 4 choices (A, B, C, D), the correct answer, and a short explanation directly based on the lecture text.

---

### Q1
**A feature detector is used to:**

A) Identify distinctive and repeatable points or regions in an image  
B) Adjust image brightness  
C) Perform histogram equalization  
D) Detect color only  

**Correct Answer:** A

---

### Q2
**Corner features are preferred because they:**

A) Provide stable and unique information for matching  
B) Are easily affected by noise  
C) Represent flat regions  
D) Are sensitive to rotation  

**Correct Answer:** A

---

### Q3
**The Harris Corner Detector is based on:**

A) Local autocorrelation function of the image intensity  
B) Histogram equalization  
C) Fourier transforms  
D) Edge linking  

**Correct Answer:** A

---

### Q4
**The main goal of the Harris Corner Detector is to:**

A) Detect points where the image intensity changes significantly in all directions  
B) Detect color variations  
C) Find straight lines  
D) Segment the image into regions  

**Correct Answer:** A

---

### Q5
**The mathematical basis of Harris corner detection involves:**

A) Taylor series expansion of image intensity  
B) Fourier series  
C) Gradient descent optimization  
D) Histogram binning  

**Correct Answer:** A

---

### Q6
**The structure tensor (second moment matrix) in Harris detection is:**

A) \( M = \begin{bmatrix} I_x^2 & I_x I_y \\ I_x I_y & I_y^2 \end{bmatrix} \)  
B) \( M = \begin{bmatrix} I_x & I_y \\ I_y & I_x \end{bmatrix} \)  
C) \( M = [I_x + I_y] \)  
D) \( M = [I_x / I_y] \)  

**Correct Answer:** A

---

### Q7
**The Harris response R is calculated as:**

A) \( R = det(M) - k(trace(M))^2 \)  
B) \( R = trace(M) - det(M) \)  
C) \( R = M^2 - k \)  
D) \( R = I_x + I_y \)  

**Correct Answer:** A

---

### Q8
**In the Harris corner formula, k is a:**

A) Empirical constant (typically between 0.04 and 0.06)  
B) Image intensity value  
C) Sigma parameter for Gaussian filter  
D) Gradient threshold  

**Correct Answer:** A

---

### Q9
**A corner point in Harris detection is identified when:**

A) Both eigenvalues of M are large  
B) One eigenvalue is large, one small  
C) Both eigenvalues are small  
D) Eigenvalues are zero  

**Correct Answer:** A

---

### Q10
**When one eigenvalue is large and the other small, the point represents:**

A) An edge  
B) A corner  
C) A flat region  
D) A texture  

**Correct Answer:** A

---

### Q11
**If both eigenvalues of M are small, the region is:**

A) Flat  
B) A strong corner  
C) An edge  
D) Textured  

**Correct Answer:** A

---

### Q12
**The Harris detector is invariant to:**

A) Rotation and small illumination changes  
B) Scale and reflection  
C) Large affine transformations  
D) Color shifts  

**Correct Answer:** A

---

### Q13
**The main disadvantage of the Harris corner detector is:**

A) Lack of scale invariance  
B) Low accuracy  
C) Noise sensitivity  
D) Color dependence  

**Correct Answer:** A

---

### Q14
**Scale invariance can be added to Harris by:**

A) Combining it with Laplacian or DoG-based scale selection  
B) Using color normalization  
C) Removing eigenvalues  
D) Applying histogram equalization  

**Correct Answer:** A

---

### Q15
**The Shi-Tomasi corner detector improves on Harris by:**

A) Using the minimum eigenvalue as the corner strength measure  
B) Increasing k value  
C) Reducing the number of pixels  
D) Using color gradients  

**Correct Answer:** A

---

### Q16
**Feature descriptors represent:**

A) Local image information around a detected keypoint  
B) The full image histogram  
C) Noise statistics  
D) Only pixel colors  

**Correct Answer:** A

---

### Q17
**A good feature descriptor should be:**

A) Distinctive, invariant, and compact  
B) Sensitive to rotation  
C) Large and redundant  
D) Randomly distributed  

**Correct Answer:** A

---

### Q18
**SIFT is an example of a:**

A) Feature descriptor  
B) Edge detector  
C) Histogram equalizer  
D) Segmentation method  

**Correct Answer:** A

---

### Q19
**PCA-SIFT uses:**

A) Principal Component Analysis to reduce descriptor dimensionality  
B) Gaussian filters for edge enhancement  
C) Histogram normalization  
D) Gradient magnitudes directly  

**Correct Answer:** A

---

### Q20
**GLOH (Gradient Location-Orientation Histogram) improves SIFT by:**

A) Using log-polar bins instead of rectangular ones  
B) Removing gradient magnitudes  
C) Ignoring rotation  
D) Using single-pixel orientation  

**Correct Answer:** A

---

### Q21
**MOPS stands for:**

A) Multi-Scale Oriented Patches  
B) Maximum Oriented Pixels  
C) Multi-Orbit Pixel Sampling  
D) Multi-Output Pattern Synthesis  

**Correct Answer:** A

---

### Q22
**Steerable filters allow:**

A) Computing responses at arbitrary orientations efficiently  
B) Ignoring directional gradients  
C) Applying fixed-angle filters only  
D) Enhancing contrast  

**Correct Answer:** A

---

### Q23
**Feature matching involves comparing:**

A) Feature descriptors from different images  
B) Pixel intensities directly  
C) Histograms of color  
D) Edge thickness  

**Correct Answer:** A

---

### Q24
**The matching distance between descriptors is typically computed using:**

A) Euclidean distance  
B) Manhattan distance  
C) Cosine similarity  
D) Histogram intersection  

**Correct Answer:** A

---

### Q25
**False positives in matching occur when:**

A) Two non-corresponding features are matched  
B) Matching fails between correct points  
C) Descriptors are identical  
D) Gradient magnitudes are low  

**Correct Answer:** A

---

### Q26
**False negatives occur when:**

A) Correct matches are missed  
B) Incorrect matches are accepted  
C) Noise increases  
D) Descriptors overlap  

**Correct Answer:** A

---

### Q27
**The confusion matrix in matching evaluates:**

A) Performance of the feature matching algorithm  
B) Image brightness  
C) Color contrast  
D) Filter response  

**Correct Answer:** A

---

### Q28
**Efficient feature matching can be achieved using:**

A) KD-Trees or Approximate Nearest Neighbor (ANN) methods  
B) Sequential search  
C) Pixel-by-pixel comparison  
D) Fourier transform  

**Correct Answer:** A

---

### Q29
**Feature tracking aims to:**

A) Follow detected features across consecutive video frames  
B) Detect color variation  
C) Apply thresholding  
D) Perform static segmentation  

**Correct Answer:** A

---

### Q30
**In the detect-then-track approach:**

A) Features are first detected and then tracked frame-by-frame  
B) Tracking is done before detection  
C) Detection is skipped  
D) Only edges are followed  

**Correct Answer:** A

---

### Q31
**Normalized Cross Correlation (NCC) is used for:**

A) Template-based feature tracking  
B) Histogram equalization  
C) Edge enhancement  
D) Scale normalization  

**Correct Answer:** A

---

### Q32
**The NCC value ranges between:**

A) -1 and 1  
B) 0 and 1  
C) -10 and 10  
D) -∞ and ∞  

**Correct Answer:** A

---

### Q33
**An NCC value close to 1 indicates:**

A) Strong correlation between template and target  
B) Weak correlation  
C) No match  
D) Negative similarity  

**Correct Answer:** A

---

### Q34
**Hierarchical search improves feature tracking by:**

A) Using image pyramids for coarse-to-fine matching  
B) Increasing brightness  
C) Reducing the number of keypoints  
D) Ignoring large displacements  

**Correct Answer:** A

---

### Q35
**Feature detectors can be classified into:**

A) Edge-based, corner-based, and blob-based  
B) Color-based only  
C) Texture-based only  
D) Frequency-based  

**Correct Answer:** A

---

### Q36
**Corners are preferred over edges because:**

A) They are more distinct and repeatable under transformations  
B) They provide less information  
C) They are easier to detect  
D) They change with illumination  

**Correct Answer:** A

---

### Q37
**The eigenvalues of the structure tensor represent:**

A) Intensity variation in orthogonal directions  
B) Color components  
C) Noise levels  
D) Filter coefficients  

**Correct Answer:** A

---

### Q38
**The trace of M equals:**

A) Sum of its eigenvalues  
B) Product of its eigenvalues  
C) Determinant of M  
D) Inverse of M  

**Correct Answer:** A

---

### Q39
**In the Harris response, a large determinant and small trace indicate:**

A) Strong corner  
B) Flat region  
C) Edge  
D) Weak texture  

**Correct Answer:** A

---

### Q40
**The Gaussian weighting window in Harris detection is used to:**

A) Reduce noise and emphasize nearby pixels  
B) Enhance distant edges  
C) Normalize brightness  
D) Remove gradients  

**Correct Answer:** A

---

### Q41
**A high R value in Harris output means:**

A) Corner detected  
B) Flat region  
C) Edge region  
D) Noisy area  

**Correct Answer:** A

---

### Q42
**Harris detector can fail under:**

A) Scale changes  
B) Small rotations  
C) Illumination normalization  
D) Gaussian blur  

**Correct Answer:** A

---

### Q43
**In Shi-Tomasi, a corner is accepted if:**

A) The minimum eigenvalue exceeds a threshold  
B) The maximum eigenvalue is zero  
C) The trace is constant  
D) The determinant is negative  

**Correct Answer:** A

---

### Q44
**Feature descriptors must be invariant to:**

A) Rotation, scale, and illumination  
B) Color space  
C) Random noise  
D) Perspective only  

**Correct Answer:** A

---

### Q45
**Matching performance can be evaluated using:**

A) Precision, recall, and F-measure  
B) Mean intensity  
C) Gradient direction  
D) Histogram width  

**Correct Answer:** A

---

### Q46
**The detect-then-track pipeline is important for:**

A) Motion estimation and video analysis  
B) Color segmentation  
C) Histogram normalization  
D) Edge enhancement  

**Correct Answer:** A

---

### Q47
**Feature tracking algorithms assume that:**

A) Features move smoothly across frames  
B) Features disappear instantly  
C) Illumination changes randomly  
D) Scale is constant only  

**Correct Answer:** A

---

### Q48
**The computational complexity of matching can be reduced by:**

A) Using approximate nearest neighbor search  
B) Using brute force search only  
C) Ignoring descriptor normalization  
D) Removing keypoints  

**Correct Answer:** A

---

### Q49
**The primary output of a feature detection and matching system includes:**

A) Matched keypoints across multiple images  
B) Histogram plots  
C) Edge maps  
D) Color filters  

**Correct Answer:** A

---

### Q50
**Corner detection and feature matching together form the foundation for:**

A) Object recognition, tracking, and 3D reconstruction  
B) Color enhancement  
C) Histogram equalization  
D) Image compression  

**Correct Answer:** A

---

## End of Questions

