# YOLOv8_coin_detection

1. 100원, 500원 동전 정면 촬영한 이미지 데이터셋 생성
2. roboflow 웹페이지에서 detection 라벨링
3. google cloud platform인스턴스에서 YOLOv8으로 object detection 학습

- google cloud platform
  - gpu : Tesla V100 1개
  - cpu : 4개
  - ram : 15GB
  - python 3.10.13
    - torch 1.13.1+cu117
    - torchvision 0.14.1+cu117
    - ultralytics 8.0.20
    - IPython 8.17.2
