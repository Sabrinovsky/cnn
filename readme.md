#cnn sports classification

#### treinamento:
`python train.py --dataset sports-classifier-data --model model/activity.model --label-bin model/lb.pickle --epochs 50`

#### classificação de video com keras:
`python predict_video.py --model model/activity.model --label-bin model/lb.pickle --input videos/tennis.mp4 --output output/tennis_1frame.avi --size 128`




