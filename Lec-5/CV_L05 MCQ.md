# MCQs — Computer Vision Lecture 5: Feature Detection and Matching (Lines and Shapes)

**Course:** Computer Vision  
**Lecture:** 5 – Feature Detection and Matching (Lines and Shapes)  
**Instructor:** [Not Specified]  
**Purpose:** Multiple Choice Questions (MCQs) covering all lecture contents. Each question includes 4 choices (A, B, C, D), the correct answer, and a short explanation directly based on the lecture text.

---

### Q1
**Shape-based feature detection focuses on identifying:**

A) Edges, corners, and geometric primitives like lines and circles  
B) Color gradients only  
C) Histogram equalization  
D) Texture mapping  

**Correct Answer:** A

---

### Q2
**A line in image processing can be defined by:**

A) y = mx + c  
B) x² + y² = r²  
C) x² + y² + z² = 1  
D) f(x, y) = 0 only  

**Correct Answer:** A

---

### Q3
**The main goal of line fitting is to:**

A) Estimate a mathematical model that best represents a set of edge points  
B) Detect pixel color values  
C) Enhance image contrast  
D) Remove noise  

**Correct Answer:** A

---

### Q4
**Which of the following is a method used for line fitting?**

A) Successive Approximation  
B) Fourier Transform  
C) Edge Linking  
D) Histogram Thresholding  

**Correct Answer:** A

---

### Q5
**The Successive Approximation method works by:**

A) Iteratively refining a line model to fit a set of points  
B) Averaging pixel intensities  
C) Computing image gradients  
D) Subsampling the image  

**Correct Answer:** A

---

### Q6
**The Least Squares method minimizes:**

A) The sum of squared perpendicular distances from points to the line  
B) The number of detected points  
C) The maximum deviation  
D) The edge strength  

**Correct Answer:** A

---

### Q7
**In line fitting, outliers are:**

A) Points that do not conform to the model due to noise or occlusion  
B) The best inliers  
C) Perfectly aligned points  
D) Edge endpoints only  

**Correct Answer:** A

---

### Q8
**RANSAC is used for:**

A) Robust model fitting in the presence of outliers  
B) Image smoothing  
C) Frequency analysis  
D) Edge enhancement  

**Correct Answer:** A

---

### Q9
**The full form of RANSAC is:**

A) Random Sample Consensus  
B) Rapid Sampling Calculation  
C) Random Selection and Classification  
D) Recursive Approximation Scheme  

**Correct Answer:** A

---

### Q10
**RANSAC operates by:**

A) Randomly selecting subsets of data to estimate a model and verifying consensus  
B) Using the entire dataset at once  
C) Computing histograms  
D) Averaging residuals  

**Correct Answer:** A

---

### Q11
**The Hough Transform is used to detect:**

A) Geometric shapes like lines, circles, and ellipses  
B) Color patterns  
C) Texture directions  
D) Image intensity values  

**Correct Answer:** A

---

### Q12
**The basic equation used in the Hough Transform for a line is:**

A) ρ = x cos θ + y sin θ  
B) y = mx + c  
C) x² + y² = r²  
D) f(x, y) = 0  

**Correct Answer:** A

---

### Q13
**In Hough space, each point in the image corresponds to:**

A) A sinusoidal curve  
B) A straight line  
C) A circular region  
D) A constant value  

**Correct Answer:** A

---

### Q14
**The intersection of multiple curves in Hough space indicates:**

A) The parameters (ρ, θ) of a detected line  
B) The image center  
C) Noise accumulation  
D) Edge strength  

**Correct Answer:** A

---

### Q15
**The advantage of Hough Transform is:**

A) It can detect shapes even with missing or noisy edge points  
B) It requires no edge detection  
C) It works only for perfect edges  
D) It ignores orientation  

**Correct Answer:** A

---

### Q16
**The main drawback of Hough Transform is:**

A) High computational and memory cost  
B) Inability to detect circles  
C) Sensitivity to scaling  
D) Low accuracy  

**Correct Answer:** A

---

### Q17
**Circle detection using Hough Transform uses parameters:**

A) (a, b, r) where (a, b) is the center and r is the radius  
B) (ρ, θ)  
C) (x, y, σ)  
D) (m, c)  

**Correct Answer:** A

---

### Q18
**The equation of a circle used in Hough Transform is:**

A) (x - a)² + (y - b)² = r²  
B) y = mx + c  
C) ρ = x cos θ + y sin θ  
D) f(x, y) = 0  

**Correct Answer:** A

---

### Q19
**The Generalized Hough Transform (GHT) is used for:**

A) Detecting arbitrary shapes that do not have a specific mathematical representation  
B) Detecting only straight lines  
C) Frequency filtering  
D) Edge sharpening  

**Correct Answer:** A

---

### Q20
**The GHT works by using:**

A) A model shape and its R-table to find matches in the image  
B) Gradient magnitude alone  
C) Gaussian smoothing  
D) Random point selection  

**Correct Answer:** A

---

### Q21
**The R-table in the Generalized Hough Transform stores:**

A) Vectors from the reference point to boundary points indexed by gradient orientation  
B) Pixel intensity values  
C) Edge magnitude values only  
D) Histogram counts  

**Correct Answer:** A

---

### Q22
**The reference point in GHT is usually chosen as:**

A) The shape’s centroid  
B) Any random pixel  
C) The top-left corner  
D) The farthest boundary point  

**Correct Answer:** A

---

### Q23
**The main advantage of GHT over classical Hough Transform is:**

A) It can detect arbitrary shapes defined by a template  
B) It is faster and requires less memory  
C) It only detects circles  
D) It uses no edge detection  

**Correct Answer:** A

---

### Q24
**Line segments are often represented in computer vision by:**

A) Their two endpoints  
B) Only their midpoint  
C) Their slope only  
D) Their intensity  

**Correct Answer:** A

---

### Q25
**Vanishing points occur when:**

A) Parallel lines in the real world appear to converge in the image plane  
B) Two lines intersect physically  
C) Perspective distortion is absent  
D) Lines diverge infinitely  

**Correct Answer:** A

---

### Q26
**Vanishing points are important for:**

A) Camera calibration and 3D reconstruction  
B) Histogram equalization  
C) Edge detection  
D) Gradient computation  

**Correct Answer:** A

---

### Q27
**In perspective projection, parallel lines appear to meet at:**

A) The horizon or vanishing point  
B) The image center  
C) The camera origin  
D) A random position  

**Correct Answer:** A

---

### Q28
**The Hough Transform accumulator array stores:**

A) The number of edge points supporting each parameter combination  
B) Pixel intensities  
C) Gradient directions  
D) Gaussian weights  

**Correct Answer:** A

---

### Q29
**In circle detection, each edge point votes for:**

A) Possible circle centers at a fixed radius  
B) Fixed line angles  
C) Random orientations  
D) Edge gradients only  

**Correct Answer:** A

---

### Q30
**The performance of the Hough Transform can be improved using:**

A) Gradient information to limit voting angles  
B) Random sampling only  
C) Thresholding all edges equally  
D) Ignoring gradients  

**Correct Answer:** A

---

### Q31
**Least Squares line fitting assumes:**

A) Gaussian noise distribution  
B) Uniform noise  
C) No noise  
D) Poisson distribution  

**Correct Answer:** A

---

### Q32
**The success of RANSAC depends on:**

A) The number of iterations and the inlier threshold  
B) Image brightness  
C) Edge thickness  
D) Histogram bin size  

**Correct Answer:** A

---

### Q33
**RANSAC repeats the fitting process until:**

A) The largest consensus set is found  
B) The first model fits all points  
C) All points are removed  
D) Gradient magnitude increases  

**Correct Answer:** A

---

### Q34
**The Generalized Hough Transform requires prior knowledge of:**

A) A model shape or template  
B) Edge magnitudes  
C) Histogram thresholds  
D) Gradient normalization  

**Correct Answer:** A

---

### Q35
**A common application of line detection is:**

A) Lane detection in autonomous driving  
B) Histogram matching  
C) Color segmentation  
D) Texture filtering  

**Correct Answer:** A

---

### Q36
**Circle detection is often used in:**

A) Coin recognition and eye detection  
B) Edge thinning  
C) Histogram stretching  
D) Object tracking only  

**Correct Answer:** A

---

### Q37
**The Hough Transform can detect multiple shapes by:**

A) Using multi-dimensional parameter spaces  
B) Reducing image resolution  
C) Thresholding the accumulator  
D) Filtering outliers only  

**Correct Answer:** A

---

### Q38
**When detecting ellipses, the Hough Transform parameter space includes:**

A) Center coordinates, major and minor axes, and orientation  
B) Only radius  
C) Slope and intercept  
D) Frequency and amplitude  

**Correct Answer:** A

---

### Q39
**The computational cost of ellipse detection is higher because:**

A) It requires a 5-dimensional parameter space  
B) It ignores gradients  
C) It uses fixed voting  
D) It doesn’t use edges  

**Correct Answer:** A

---

### Q40
**Edge detection is typically a prerequisite for:**

A) Hough-based shape detection  
B) Histogram matching  
C) Fourier transform  
D) Smoothing  

**Correct Answer:** A

---

### Q41
**The orientation of detected lines can be derived from:**

A) The angle θ in the Hough representation  
B) The histogram of gradients  
C) The color channel difference  
D) The intensity mean  

**Correct Answer:** A

---

### Q42
**Voting peaks in the Hough accumulator correspond to:**

A) Detected shapes or lines  
B) Noise clusters  
C) Unused bins  
D) Gradient directions  

**Correct Answer:** A

---

### Q43
**One limitation of the Generalized Hough Transform is:**

A) High computational and memory requirements  
B) Inability to detect circles  
C) Lack of rotation invariance  
D) Failure in edge detection  

**Correct Answer:** A

---

### Q44
**The robustness of RANSAC increases with:**

A) More iterations and better sampling  
B) Fewer data points  
C) Ignoring outliers  
D) Larger error thresholds  

**Correct Answer:** A

---

### Q45
**Line fitting using Least Squares fails when:**

A) There are too many outliers  
B) Data points are linear  
C) Noise is Gaussian  
D) Inliers dominate  

**Correct Answer:** A

---

### Q46
**For real-world applications, the combination of edge detection and Hough Transform is used for:**

A) Detecting road lanes and building edges  
B) Noise filtering  
C) Color segmentation  
D) Histogram equalization  

**Correct Answer:** A

---

### Q47
**The concept of perspective geometry explains:**

A) How 3D parallel lines project to 2D vanishing points  
B) How histograms are normalized  
C) How edges are detected  
D) How noise affects brightness  

**Correct Answer:** A

---

### Q48
**The intersection of multiple vanishing points forms:**

A) The vanishing line or horizon  
B) A single perspective center  
C) The image origin  
D) The focal plane  

**Correct Answer:** A

---

### Q49
**Vanishing points can be used to infer:**

A) Camera orientation and scene geometry  
B) Pixel intensities  
C) Image sharpness  
D) Color channels  

**Correct Answer:** A

---

### Q50
**Hough Transform-based methods are widely used in:**

A) Road lane detection, object recognition, and industrial inspection  
B) Audio recognition  
C) Histogram analysis  
D) Image compression  

**Correct Answer:** A

---

## End of Questions

