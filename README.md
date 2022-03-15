### Data Set

* UCF101 dataset (https://www.crcv.ucf.edu/data/UCF101.php) 사람들의 101가지 동작을 녹화한 비디오 데이터셋
* UCF101 데이터 셋의 비디오를 학습해서 비디오 분류
* top3('CricketShot', 'Punch', 'TennisSwing') 
* top5('CricketShot', 'PlayingCello', 'Punch', 'ShavingBeard', 'TennisSwing') 두가지 버전으로 진행

#### Model

* top5 Xception loss: 0.24 - acc: 95.16 %
* top3 VGG16 loss: 0.009 - acc: 99.6 %
