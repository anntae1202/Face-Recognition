# Face-Recognition

1. 작업 툴

python3.6, opencv, dlib, numpy, matplotlib

2. 작품소개

기존 Dlib 패키지 함수를 활용하여 특정인물들의 얼굴 데이터를 학습시킨 뒤,
학습이 가장  잘 이루어지는 파라미터 값을 찾고 이후 test 데이터를 제시했을때
AI가 학습된 인물을 정확하게 인식할 수 있게 개선하였습니다.


이미지 파일의 경우,

1) 4개의 모델들을 다운로드 받은후, models 폴더에 넣습니다.
2) train_img 에 학습시킬 인물사진을 넣습니다.
저는 무한도전 인원들 7명을 넣었습니다.(유재석, 박명수, 정준하, 하하, 노홍철, 길, 정형돈)
동시에 얼굴인식을 할 사진 또한 넣어줍니다.(무한도전 단체사진)
3) result 폴더를 만들어둡니다.
4) 'infinite challenge6.ipynb' 코드를 통해 모델을 생성한후,
train_img에서 단체사진을 불러와 모델을 적용하면 AI가 얼굴을 인식한 사진을 출력합니다.

동영상의 경우, 
4번 모델을 생성한후, test_video에서 동영상이름을 수정하고 실행시키면
AI가 영상에서 학습한 인물의 사진을 지속적으로 추적하여 인식합니다.
