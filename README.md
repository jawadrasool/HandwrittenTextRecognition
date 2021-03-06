# Hand-written Text Recognition

The goal of this project was to develop Deep Learning Models to recognize Handwritten text in an Image. The model takes an input image (e.g. handwritten document scan), find segments of hand-written text, and translate the text content into ASCII letters

![](Images/Image1.PNG)

## Dataset 

For this project, we used the publically available dataset ["IAM Handwriting Database"](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database). It contains:

- 1539 pages of scanned text
- 13353 labelled text lines
- 115320 labelled words

We focussed on the text lines.

## Data Preparation

- Discarded badly formed lines
- Convert to Binary Image
- Rescaling the Image keeping same aspect ratio

## Modeling

### Model 1

![](Images/Model1.PNG)

![](Images/Model1_performance.PNG)

### Model 2

![](Images/Model2.PNG)

![](Images/Model2_performance.PNG)

