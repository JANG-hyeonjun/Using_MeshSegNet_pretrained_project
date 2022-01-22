# Using_MeshSegNet_pretrained_project

본 프로젝트는 MeshSegNet pretrained model을 사용하는데 의의가 있으며 pretrain을 통해 나온 결과를 Open3D 라이브러리 및 자동화 하는 알고리즘를 통해 자동으로 .ply를 만들어낸다.

만들어진 .ply 파일은 치아 3D segmentation 결과가 Label0~14로 나눠져있으며 결과는 아래 사진과 같다.

![Resul1](https://user-images.githubusercontent.com/60414838/150639325-f2219f7c-da93-4082-b3e0-14ed05bfa5aa.jpg)
![Result2](https://user-images.githubusercontent.com/60414838/150639328-4087170d-c2c0-4165-bc21-326f8682a421.jpg)

추후 개발 사항에 관해선 
1.이를 모듈화 하여 제품에 적용하는것을 연구할 예정 
2.또한 데이터를 얻게 된 뒤 라벨링을 진행하여 학습을 진행할 예정
