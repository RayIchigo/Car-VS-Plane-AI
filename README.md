# Car-VS-Plane-AI

This project uses trained AI model built with Teachable Machine to classify an image as either a car or a plane. The code is executed in Google Colab, allowing easy testing.

---

##  Getting Started

### 1.  Open Google Colab
- Open [Google Colab](https://colab.research.google.com)
- Upload the code
  
### 2. Upload Required Files
Upload the following files to your Colab environment:
- keras_model.h5
- labels.txt
- Your image (e.g., test.jpg)

### 3. Update Image Path in Code
Update this line in the code with your image name:
`python
image = Image.open("/content/test.jpg").convert("RGB")
