# 🕳️ Pothole Detection using Faster R-CNN & RetinaNet  

## 📌 Project Overview  
This project compares **Faster R-CNN (ResNet-50 & ResNet-101)** and **RetinaNet** for pothole detection. Using Detectron2, we analyze their performance based on **average precision (AP) and average recall (AR)**.  

---

## 📊 Results & Findings  

### 🔥 Key Takeaways  
- **RetinaNet outperforms both Faster R-CNN models** in AP (48.1%) and AR (65.5%).  
- **Faster R-CNN (ResNet-101)** is a close second, performing better than ResNet-50.  
- **RetinaNet provides better recall**, making it the most effective model for pothole detection.  

---

### 📈 Model Performance Comparison  

#### **Average Precision (AP) – IoU 0.50:0.95**  
| Model                | AP (%) | AP (S) | AP (M) | AP (L) |
|----------------------|--------|--------|--------|--------|
| **Faster R-CNN 50**  | 38.0%  | 22.0%  | 31.0%  | 50.0%  |
| **Faster R-CNN 101** | 47.1%  | 33.2%  | 41.9%  | 57.7%  |
| **RetinaNet**        | **48.1%**  | **34.1%**  | **37.3%**  | **62.0%**  |

#### **Average Recall (AR) – Max Detections = 100**  
| Model                | AR (%) | AR (S) | AR (M) | AR (L) |
|----------------------|--------|--------|--------|--------|
| **Faster R-CNN 50**  | 46.0%  | 26.0%  | 43.0%  | 56.0%  |
| **Faster R-CNN 101** | 61.1%  | 48.4%  | 56.7%  | 69.7%  |
| **RetinaNet**        | **65.5%**  | **53.6%**  | **62.6%**  | **72.4%**  |

---

### 📌 Conclusion  
**RetinaNet** stands out as the **best-performing model** in terms of both **precision and recall**. This makes it the most **reliable** choice for **real-world pothole detection applications**.  

**Further Considerations for Improvement:**  
✅ Larger, more diverse dataset 📊  
✅ Faster inference speeds ⚡  
✅ Model optimization for real-time detection 🎯  

---
