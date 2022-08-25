# AIStandfordCarsDistinction

## 1. 목표
* 이미지 기반 차량 종류 예측하는 프로젝트이고, 테스트 셋 기준 196가지 클래스에 대한 정확도 약 80% 이상 달성하는 것이 목표이다.

## 2. 데이터 셋
Link : [Cars Dataset][cars datasetlink]

[cars datasetlink]: http://ai.stanford.edu/~jkrause/cars/car_dataset.html
* 원본 데이터 셋은 스탠포드 대학에서 공개한 데이터 셋이고, 쉽게 사용할 수 있도록 수정하였다.

## 3. 개발 환경
* Google Colab
* pytorch 1.7.1
* torchvision 0.8.2
* cuda 9.2

## 4. 참조
* 학습 시 필요한 자료는 PyTorch Tutorial 등 확인하였다.

Link : [Transfer Learning for Computer Vision Tutorial][pytorch.org]

[pytorch.org]: https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

* 모델 구조 같은 경우 ResNet18을 사용하였다.

Link : [Very Deep Convolutional Networks for Large-Scale Image Recognition][arxiv.org]

[arxiv.org]: https://arxiv.org/abs/1409.1556

[Deep Residual Learning for Image Recognition][cv-foundation.org]

[cv-foundation.org]: https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf

* GPU가 없는 경우 CPU로 학습해도 되지만, 무료 GPU인 Colab 활용하여 학습을 진행하였다.

[How To Train Deep Learning Models In Google Colab][youtube.com]

[youtube.com]: https://www.youtube.com/watch?v=chQNuV9B-Rw
