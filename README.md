# 2021_capstone_design2
안녕하세요. 경희대학교 컴퓨터공학과 2017104020 임은나입니다.
본 모델은 아이템 속성 분류기 모델입니다.
CUDA를 기반으로 하기 때문에 NVIDIA GPU가 아닐 경우 실행할 수 없습니다.
모델을 colab에서 실행할 수 있도록 ipynb 파일을 추가하였습니다.

# Requirements
- pip install -r requirements.txt

# 테스트 데이터 셋 성능 테스트 
### 패션 특성 분류 
- python test.py

## 개별 데이터셋에 대한 성능 수치 확인
### 패션 특성 분류
- 아래 파일들을 통해 각 row 별 예측 결과를 확인
```
output/category_correct.csv
output/category_wrong.csv
output/detail_correct.csv
output/detail_wrong.csv
output/print_correct.csv
output/print_wrong.csv
output/texture_correct.csv
output/texture_wrong.csv
```
