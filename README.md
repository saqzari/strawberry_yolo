Forked from:
https://github.com/ultralytics/yolov5

Google colab environment available at:
https://colab.research.google.com/drive/1P2ty_B936idQxGEN86P9vS-BEzRbSCJC?usp=sharing

Setup commands:
git clone https://github.com/saqzari/strawberry_yolo.git
cd strawberry_yolo
pip install -U --no-cache-dir gdown --pre
gdown https://drive.google.com/uc?id=1LTTB_U9Mx91Z-wnHdHvkReY-NDjlOrX-
unzip strawberry_weights.zip
pip install -qr requirements.txt

Detect command:
python detect.py --weights strawberry_best.pt --conf-thres 0.8 --line-thickness 2 --source Group14/images/471.png


