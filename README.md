# TechieBunnies 
Safety Object Detection – YOLOv11

**PROJECT STRUCTURE**

TechieBunnies/
|-- best.pt
|-- data.yaml (Make sure you modify data.yaml accordingly to you before running)
|-- train.py
|-- predict.py
|-- requirements.txt
|-- report.pdf
|-- bonus_report.pdf
|
|-- train/ (REQUIRED for training – Add manually if using train.py)
| |-- images/
| |-- labels/
|
|-- val/ (REQUIRED for validation)
| |-- images/
| |-- labels/
|
|-- test/ (REQUIRED for prediction – Add manually if using predict.py)
| |-- images/
| |-- labels/
|

**Environment Setup**

**Mac / Linux** 
python3 -m venv venv (or) python -m venv venv 
source venv/bin/activate

**Windows**
python -m venv venv 
venv\Scripts\activate

**Installing Dependencies**
**To run train.py**

ultralytics>=8.3.50 
torch>=2.1.0 
torchvision>=0.16.0 
numpy 
opencv-python 
matplotlib 
pandas 
pyyaml 
tqdm 
psutil 
tensorboard

**To run predict.py**
pip install -r requirements.txt

**Dataset Requirements**
For Training (train.py)
train/
| |-- images/
| |-- labels/

For Prediction (predict.py) 
test/
| |-- images/
| |-- labels/

**Expected Outputs & Interpretation** 
You will receive: 
best.pt → highest mAP model 
last.pt → last epoch model 
results.png → plot of losses and metrics 
confusion_matrix.png 
precision_recall_curve.png

**Key Metrics:** 
mAP50 → primary accuracy metric 
Precision → how many detections are correct 
Recall → how many objects were found

**Google Drive Link** for predictions on test data: 
https://drive.google.com/drive/folders/1udKP3C7Q0TdLUMTEQXAHNPOjn2oH9lCi?usp=sharing
