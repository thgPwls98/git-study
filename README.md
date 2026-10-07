# Git & GitHub 원격 저장소 커밋 및 푸시 가이드
--> 언젠가 잊어버릴지도 모를 나를 위해....


## 1단계: 로컬 저장소 초기화 및 원격 저장소 연결

  ```
git init
git remote add origin https://github.com/thgPwls98/git-study.git
git remote -v    # 원격 저장소 주소가 올바르게 등록되었는지 확인
  ```


## 2단계: 파일 작성, Staging 및 Commit
  ```
git status
git add 파일명
git commit -m "Docs: Add Git & GitHub study summary"
  ```
* 특정 파일 하나만 올릴 때는 git add 파일명을 사용하고, 수정되거나 추가된 파일 전체를 한 번에 올려두고 싶을 때는 git add .을 사용

## 3단계: GitHub Public Repository로 Push

  ```
git push -u origin main
  ```
* -u 옵션을 한 번 붙여두면, 다음부터는 단순히 git push만 입력해도 자동으로 origin의 main 브랜치로 자동 푸시된다!
