# Git 자주 사용하는 명령어 정리
자주 사용하는 기본적인 명령어들을 정리했습니다.

--작성일 2019.11.16(토)

## 저장소 생성(초기화) 하기
```bash
git init # 저장소 생성
```

## 커밋하기
```bash
git add README.md
git status
git commit -m "init: README.md"
git log --decorate=full --oneline --graph

## 브렌치 생성하기
```bash
git checkout -b readme
```
