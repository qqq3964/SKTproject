# Hash tag generate with bert model

### Archive contents
```
wanso/
├── pickle_data/
│   ├── common_tag.pickle
│   ├── dic.pickle
│   ├── hash_table.pickle
│   └── img_table.pickle
├── weights/
│   └── classification_model.pt
├── ko.bin
├── adot_clf_model.py
├── adot_tag_generate.py
└── adot_tag_run.py
```

### 설치 파일
requirements.txt
- 필요한 라이브러리 설치
```
!pip install -r requirements.txt
```
### Word2Vec 설치
```
!gdown https://drive.google.com/file/d/1-0FZyuS9gt1Avb8vY_VtCsksVL_JMTUv/view?usp=share_link
```
### gz 파일 압축해제
```
!gzip -d ko.bin
```
### 모델 weights 다운로드 weights folder에 넣어줘야한다.
```
!wget https://drive.google.com/file/d/1-XnfaC5az-1pVzixhQZkMLnSgxz7cv0e/view?usp=sharing
```
### 실행 방법
```
python3 adot_tag_run.py
```


