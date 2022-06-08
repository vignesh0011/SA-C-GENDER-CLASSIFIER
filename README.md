# SA-C-GENDER-CLASSIFIER
# Algorithm
1.Install deepface

2.Import necessary packages

3.Read the image

4.Analyze the gender using deepface

## Program:
```python
"""
Program to implement Gender Classification
Developed by   : M VIGNESH
RegisterNumber :  212220233002
"""
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

img=cv2.imread('vignesh.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

```

## OUTPUT:

1. CODE :

![image](https://user-images.githubusercontent.com/53014593/172695858-87867338-4b2a-4f4a-b0ef-57de04f6a68e.png)


2. DEMO VIDEO YOUTUBE LINK:
https://youtu.be/kRpayUPLq1w
