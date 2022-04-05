### Data Set

* UCF101 dataset (https://www.crcv.ucf.edu/data/UCF101.php) 사람들의 101가지 동작을 녹화한 비디오 데이터셋
* UCF101 데이터 셋의 비디오를 학습해서 비디오 분류
* top3('CricketShot', 'Punch', 'TennisSwing') 
* top5('CricketShot', 'PlayingCello', 'Punch', 'ShavingBeard', 'TennisSwing') 두가지 버전으로 진행

#### Model

* top5 Xception loss: 0.24 - acc: 95.16 %
* top3 VGG16 loss: 0.009 - acc: 99.6 %

![ucf1](https://user-images.githubusercontent.com/86470595/161680794-38312293-5b57-4308-a299-67d0a0b6f88b.png)
![화면 캡처 2022-04-05 134727](https://user-images.githubusercontent.com/86470595/161680805-d27256b7-e3a8-4fb5-91de-ce6d4f8707b2.png)
![ucf2](https://user-images.githubusercontent.com/86470595/161680817-6a29aa16-9656-4642-881a-110bb16ac95e.png)
![화면 캡처 2022-04-05 134857](https://user-images.githubusercontent.com/86470595/161680933-9e2319ab-91a9-463b-87c4-a970e4cf352c.png)
