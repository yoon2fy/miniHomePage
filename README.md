# 양양의 미니 홈페이지

## Git 기초

### 목차
<ul>
  <li>Git이란?</li>
  <li>Git 기본 명령어</li>
  <li>브랜치와 병합</li>
  <li>GitHub 사용</li>
  <li>추가 리소스</li>
</ul>
  
### Git이란?

**Git**은 분산형 버전 관리 시스템입니다. 여러 명이 동시에 작업할 수 있도록 코드를 관리하고, 작업 내역을 기록하는 데 사용됩니다.

*예를 들어*, 다음과 같은 상황에서 유용합니다:
<ul>
  <li>여러 개발자가 동시에 코드를 수정할 때</li>
  <li>프로젝트의 특정 시점으로 되돌리고 싶을 때</li>
  <li>실수로 파일을 지웠을 때 복구하고 싶을 때</li>
</ul>
"분산형 버전 관리 시스템 Git은 모든 파일의 변경 이력을 기록하여 협업을 쉽게 해줍니다." - Git 사용자

### Git 기본 명령어

#### 1. Git 저장소 초기화

`git init`

<ul><li>새로운 Git 저장소를 초기화합니다.</li></ul>

#### 2. 파일 추가 및 커밋

```git add <파일명>
git commit -m "첫 번째 커밋"```

<ul><li>스테이징 영역에 파일을 추가하고, 커밋을 생성합니다.</li></ul>

# GitHub 사용

GitHub는 Git을 기반으로 한 협업 플랫폼입니다. 다음 단계를 통해 원격 저장소를 사용할 수 있습니다:
<ol>
<li>GitHub 계정 생성</li>
새로운 리포지토리 생성
원격 저장소 연결:

git remote add origin <GitHub 저장소 URL>
git push origin main

![Git 로고](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

## 추가 리소스
- Git에 대해 더 알고 싶다면, Git 공식 문서(https://git-scm.com/doc)를 확인하세요.
- GitHub 사용법에 대한 자세한 정보는 [GitHub Docs](https://docs.github.com/en)에서 찾아볼 수 있습니다.


## 스타일 구성
- style.md 파일 추가