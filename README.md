# DeepLabV3+ Semantic Segmentation Using TensorFlow

## **📌 Project Overview**
This project implements **DeepLabV3+ for semantic segmentation** using **TensorFlow**. It loads a **pretrained DeepLabV3+ model**, processes input images, and generates segmentation maps with **PASCAL VOC color mapping**.

### **🚀 Key Features**
✅ **Loads a pretrained DeepLabV3+ model (MobileNetV2/Xception)**  
✅ **Processes images for semantic segmentation using TensorFlow**  
✅ **Applies color maps for visualization**  
✅ **Runs inference on sample images**  
✅ **Supports different backbone architectures**  

---

## **📌 Model Architecture**
DeepLabV3+ is an advanced semantic segmentation model that improves over previous versions by incorporating:
- **Atrous Spatial Pyramid Pooling (ASPP)** to capture multi-scale context.
- **Depthwise separable convolutions** for faster computation.
- **Xception and MobileNetV2 backbones** for feature extraction.

---

## **📌 Step 1: Setup and Installation**
### **Install Required Libraries**
```bash
pip install tensorflow numpy matplotlib PILLOW
