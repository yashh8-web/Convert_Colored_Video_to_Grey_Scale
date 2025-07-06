# Convert_Colored_Video_to_Grey_Scale
## ✅ Objective

To automatically convert an uploaded colored video to grey scale frame-by-frame and save the output video using OpenCV.

---

## 🧰 Tools & Libraries Used

- Python 3
- OpenCV (`cv2`)
- Google Colab
- tqdm (for progress bar)

---

## 🔄 Workflow

1. **Upload Video**  
   User uploads any `.mp4` video file from their system.

2. **Process with OpenCV**  
   - Video is read frame-by-frame  
   - Each frame is converted from `BGR` to `GRAY`  
   - Grey frames are saved to a new output video file.

3. **Download Output**  
   A grey scale version of the original video is generated and made available for download.

---

## 🚀 How to Run (Step-by-Step)

### 1. Setup (Import Libraries)
```python
import cv2
from google.colab import files
import tqdm
