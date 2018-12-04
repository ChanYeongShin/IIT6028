## Assignment 5

### Question 1. INITIALS (5pts) + Question 2. SUB-APERTURE VIEWS (20pts)

Given plenoptic camera image has 16 by 16 aperture domain source pixels. So, I set L = (16, 16, 400, 700, 3). Then, I put image to img_plenoptic pixel each by using 'for' matlab tool.

**Results**

**plenoptic image**

![Alt text](./Figure/img_plenoptic.png)

**mosaic image**

![Alt text](./Figure/img_mosaic.png)

I captured image each because of its size is So... big!

### Question 3. REFOCUSING AND FOCAL-STACK GENERATION (40pts)

I implement refocusing which the assignment document explains by using formula as shown below. And, I set d = 0 , 0.6, 1, 1.6, 2. 

![Alt text](./Figure/formula.refocus.png)

**Results**

**d = 0**
![Alt text](./Figure/img_depth_0.png)
**d = 0.6**
![Alt text](./Figure/img_depth_0.6.png)
**d = 1**
![Alt text](./Figure/img_depth_1.png)
**d = 1.6**
![Alt text](./Figure/img_depth_1.6.png)
**d = 2**
![Alt text](./Figure/img_depth_2.png)

As you see, in uniform weighting cases, Raw image is better thatn Rendered image. However, in weighting type tent and gaussian cases, especially, 'rendered image + logarithmic merge type' is much better than 'rendered image + linear merge type' in my view.

### Question 4. ALL-FOCUS IMAGE AND DEPTH FROM DEFOCUS (35pts)

**Results**

![Alt text](./Figure/linear_regression.jpg)

