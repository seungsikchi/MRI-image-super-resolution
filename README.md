# MRI-image-super-resolution

|파일이름|설명|
|------|---|
|labeling tool|영상에 대해서 친숙해지기 위해 MRI데이터를 3차원 데이터기 때문에 라벨링 툴을 따로 만들어보면서 3차원데이터를 다뤄봤다. |
|loader|MRI데이터를 불러오는 코드 GAN과 Cycle GAN에 import시켜서 사용한다.|
|Voxel|멘토링 하면서 멘토분이 주신 코드 labeling tool에서 3차원 공간을 만들거나 정규화를 하는데 사용 labeling tool과 CycleGAN을 학습시키는 부분에서 함수를 호출해서 사용|
|plan1(GAN)|MRI데이터를 DC GAN알고리즘에 넣어서 새로 이미지를 만들때 사용 여기서 생성한 데이터를 Super Resolution에 넣어서 화질을 개선한다.|
|plan2(CycleGAN)|MRI데이터를 Cycle GAN알고리즘에 넣어서 새로 이미지를 만들떄 사용 이 알고리즘으로 Flare image를 Routine 이미지로 점점 바꾸는 작업을 수행함|
|image|Dicom파일을 불러오거나 vtk를 사용해서 3D Randering을 하는 코드|
|CycleGAN|EPI이미지와 Routine이미지를 들고와서 EPI이미지를 점점 Routine이미지로 서로의 스타일을 학습하여 변형시키는 코드|
