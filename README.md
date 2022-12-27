# Poisonous_Mushroom_Classification

CNN 계열 딥러닝 모델을 활용해 독버섯을 분류했습니다.

kaggle 버섯 이미지 데이터셋을 활용했습니다.
https://www.kaggle.com/datasets/maysee/mushrooms-classification-common-genuss-images

# 0. mushroom_random
kaggle dataset은 8종류의 버섯에 대한 이미지를 제공하기에 독이 있는 것과 없는 것으로 나눠야 합니다.
독 여부를 나눈 후 train test 를 랜덤하게 나누었습니다.

# 1. mushroom_classification_1
주피터 노트북에서 Resnet18(86.4%), Googlenet(88%), Alexnet(79.4%)을 finetuning 했습니다.

# 2. mushroom_classification_2
메모리 부족 문제로 colab에서 VGG16(89%), MNASnet(86%)을 finetuning 했습니다.

# 3. mushroom_classification_3
epoch를 늘려서 Googlenet과 VGG16에 대해 학습을 진행했고 Accuracy와 Recall을 고려해 GoogleNet을 선택했습니다.

자세한 설명은 아래 tistory 블로그에서 확인할 수 있습니다.
https://changdaelee.tistory.com/11





