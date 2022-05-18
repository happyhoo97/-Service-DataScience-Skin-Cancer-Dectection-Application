# Skin Cancer Detection Application
KHU Service DataScience project


### git clone
```
git clone https://github.com/happyhoo97/Skin-Cancer-Dectection-Application.git
```

### git 강제 pull 방법
```
git fetch --all
git reset --hard origin/main
git pull origin main
```

### Python 환경

Conda Python 3.8 - 구글링해서 패키지 환경 세팅 방법 확인 후 세팅 바람

### conda 환경 세팅
```
conda create -n 가상환경이름 python=3.8
conda activate 가상환경이름
```


### Requirement install (./Skin-Cancer-Dectection-Application 폴더에서 명령어 입력)
```
pip install -r requirements.txt
```

### 주의사항
- 작업 전 "git pull"하고 수행하기
- 작업 마친 후 git add . | git commit -m "작업 완료" | git push 수행하기
- 각자 작업하는 폴더 이외의 코드는 수정하기 않기, 꼭 수정이 필요하면 먼저 알리고 수정 (충돌 방지)

### Flow
```
git pull
--- 작업 수행 --- 
git add .
git commit -m "작업 종료"
git push
```
