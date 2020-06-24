# HW/WS 
okpy로 자동화 테스트

## 설치
### 1. 과제 다운로드
`git clone`을 통해 프로젝트 다운로드
```bash
> git clone [프로젝트 URL]
```

### (선택) 2. 가상환경 설정
강권하나 반드시 필요하진 않음
- Mac/Linux

- Windows

- `pyenv virtualenv` 등 다른 패키지로 설정 가능

### 3. Python Package 설치
```
> pip install -r requirements.txt
```


## 실행
### 1. 코드 테스트
```bash
> python ok
```

### (첫 실행시) 2. 이메일 등록 요구
- HPHK 강사들의 경우 교육용 이메일 사용
- 로그인 및 Web 화면 확인

### 3. 제출
```bash
> python ok --submit
```