
# 🚀 TechieBunnies – SafetySense  
### AI-Powered Detection of Space Station Safety Equipment (YOLOv11x)

🎥 **Demo Video (YouTube)**  
👉 *https://youtu.be/ModwTd9uXd0*

📁 **Google Drive – Report Documents**  
👉 *https://drive.google.com/drive/folders/1_vyTuObF4elS56UXTzZkcPZIiKbR5qEN?usp=share_link*

SafetySense is an advanced AI-driven safety detection system built for the **Duality AI Space Station Challenge**. It detects **7 critical safety objects** across synthetic environments with varying lighting, clutter, room layouts, occlusion, and spatial configurations using a fine‑tuned **YOLOv11x** model.

---

# 🧠 Detected Classes
| ID | Object |
|----|--------------------|
| 0 | OxygenTank |
| 1 | NitrogenTank |
| 2 | FirstAidBox |
| 3 | FireAlarm |
| 4 | SafetySwitchPanel |
| 5 | EmergencyPhone |
| 6 | FireExtinguisher |

---

# 📂 Project Structure (Final Submission)
**Note:**
- Ignore the hello folder  
- Open Desktop/Hackwithblr and download TechieBunnies.zip


```
TechieBunnies/
│── best.pt
│── data.yaml (Make sure you modify data.yaml accordingly to you before running)
│── train.py
│── predict.py
│── requirements.txt
│── report.pdf
│── bonus_report.pdf
│
│── train/ (REQUIRED for training - Add manually if using train.py)
│   ├── images/
│   └── labels/
│
│── val/ (REQUIRED for validation)
│   ├── images/
│   └── labels/
│
│── test/ (REQUIRED for prediction - Add manually if using predict.py)
│   ├── images/
│   └── labels/
```

---

# ⚙️ Environment Setup

## 🖥 macOS / Linux
```
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
```

## 🪟 Windows
```
python -m venv venv
venv\Scripts\activate
pip install --upgrade pip
```

---

# 📦 Install Dependencies
```
pip install ultralytics torch torchvision numpy opencv-python matplotlib pandas pyyaml tqdm psutil tensorboard
```

or

```
pip install -r requirements.txt
```

---


# 🏋️ Training the Model
```
python train.py
```

Outputs:
- best.pt  
- last.pt  
- results.png  
- confusion matrix  
- PR curves  
- mAP metrics  

---

# 🔍 Running Inference
```
python predict.py
```

Results saved in:
```
optimized_predictions/
```

---

💾 **Model Download (Test Predictions)**  
👉 *https://drive.google.com/drive/folders/1udKP3C7Q0TdLUMTEQXAHNPOjn2oH9lCi?usp=sharing*
---

# 🌐 Bonus Web App – SafetySense Dashboard

Sci‑fi animated web app for:
- Image upload  
- YOLO inference  
- Safety scoring   
- Analytics dashboard  

Built with:
- Next.js  
- TailwindCSS  
- shadcn/ui  
- Framer Motion  

---

# 🚧 Challenges Faced
- Dataset imbalance  
- Occlusions in cluttered scenes  
- GitHub LFS file limits  
- Large model handling  
(detailed description is given in report)

---

# 🏁 Conclusion
SafetySense provides:
- A high-performing YOLOv11x model  
- A complete evaluation pipeline  
- A futuristic safety analysis web interface  
- Robust synthetic‑to‑real generalization strategies  

---

# 👥 Team TechieBunnies
- Sahiti Potini  
- Navya  
- Varun E  
- Tejas Kollipara  
- Adithya Kommuri  
