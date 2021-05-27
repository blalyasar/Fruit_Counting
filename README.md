# Fruit_Counting

# optional and proposal create virtualenv.
! pip install requirements.txt

! and downloadn yolo5

! git clone https://github.com/ultralytics/yolov5.git

for run
! python yolov5/detect.py --weights yolov5s.pt --img 640 --conf 0.25 --source yolov5/data/images --save-txt --project results
