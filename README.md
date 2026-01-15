# Skn25_1team# 👥 팀원 소개

| 이름 |
|------|
| 김찬영 | 
| 박범수 | 
| 이수영 |
| 이하윤 | 
| 최현우 | 
> ※ 역할은 과제 진행 상황에 따라 유동적으로 협업함


## 🛠 Git / GitHub 사용 규칙

### 1️⃣ 브랜치 정책
- `main` : 최종 결과물 브랜치
- 모든 작업은 개인 또는 기능 브랜치에서 진행
- `main` 직접 커밋 금지


### 2️⃣ 작업 절차
1. git 열어서 환경만들기 ( branch 생성 )
```bash
 git clone https://github.com/hwc2000/Skn25_1team.git # 저장소 클론
 cd Skn25_1team # 디렉토리 이동
 git branch # 브랜치 상태확인
 git checkout -b 'hw' # hw라는 이름의 브랜치 생성 (각자 이름같은거 써주세요)
```
2. 작업하기
- 각자 생성한 브랜치에서 파일 수정 또는 코드 작성
- 예: README.md 수정, 코드 파일 추가 등

```bash
notepad README.md # ex) 리드미 수정-> README.md 열림 -> 수정 후 저장후 닫기
git status # 변경 사항 확인 ex) modified : README.md
git add README.md # 변경 사항 스테이징 ( 전체 스테이징은 git add . )
git commit -m "README 작업 내용 추가" # 커밋
git push origin hw # 원격 저장소로 푸시 (hw는 본인 브랜치 이름 각자 이름으로 변경)
```

3. Git hub에서 PR 생성
4. merge

