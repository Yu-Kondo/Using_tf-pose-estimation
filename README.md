# Using_tf-pose-estimation
tf-pose-estimationで画像および動画を解析

## 1) tf-pose-estimationを指定する
conda activate pose

cd tf-pose-estimation

## 2) 画像解析
python run.py --model=mobilenet_thin --resize=432x368 --image=./images/"−画像名−"

## 3) 動画解析
python run_video2.py --model=mobilenet_thin --resize=432x368 --video=/"−動画のフルパス−"

## 4) Webカメラ
python run_webcam.py --model=mobilenet_thin --resize=432x368 --camera=0
