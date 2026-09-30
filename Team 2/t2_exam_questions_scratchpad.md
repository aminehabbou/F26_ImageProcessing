# Exam Question Proposals

## General hints:
* Only questions, no answers! Keep answers elsewhere
* No yes-no questions!
* Per week, three questions on three levels (reproduce, apply, analyze)

## Example questions for one week:
* Reproduce: State the Nyquist sampling theorem and describe its significance for image sampling.
* Apply: Given an image containing details up to a specified spatial frequency, determine the minimum sampling frequency needed to avoid aliasing.
* Analyze: Explain how undersampling causes aliasing and compare the resulting image artifacts with those produced by sampling at or above the Nyquist rate.

## Week 2 — Image Sampling and Geometric Alignment

* Reproduce: What requirement does the Nyquist sampling theorem place on the spatial sampling frequency of an image?
* Apply: Which geometric transformation should be used to align two overlapping photographs of the same flat map taken from different viewing angles?
* Analyze: Under otherwise identical capture conditions, a low-resolution map photograph is enlarged to the same pixel dimensions as a high-resolution photograph. How do the two images compare for map reconstruction?

## Week 3 — Homography and Alignment

* Reproduce: What is Homography used for in image stitching?
* Apply: Image A and Image B have matching points. After RANSAC(i.e. Random Sample Consensus) finds a Homography H(A->B), what should be done to align image A with image B?
* Analyze: If most matching points agree with Homography but a few do not, how does RANSAC help decide which matches are reliable?
