# MRI-image-super-resolution

labeling tool : MRI데이터가 3차원 데이터기 때문에 라벨링 툴을 따류 만들었다. 

image Read : MRI데이터를 불러오는 코드 GAN에 import시켜서 사용한다.

Voxel : 멘토링 하면서 멘토분이 주신 코드 labeling tool에서 3차원 공간을 만들거나 수정하는데 사용 labeling tool에 import 시켜서 사용

GAN : MRI데이터를 GAN알고리즘에 넣어서 새로 이미지를 만들때 사용 여기서 생성한 데이터를 Super Resolution에 넣어서 화질을 개선한다.

image : Dicom파일을 불러오거나 vtk를 사용해서 3D Randering을 하는 코드
