# hello git

## git 명령어 요약

- clone : 원격 저장소 복사
- add : staging area에 파일 추가
- commit : staging area에 있는 파일들을 save
- push : 원격 저장소에 커밋 업로드


- sourcetree에서 '코드뭉치 버리기'를 통해 변경사항 취소할 수 있음! (마지막 commit 시점으로 되돌아감)

## branch 변경하기

- branch : 기존 내용을 유지한 채, 새로운 내용을 추가하고 싶을 때 사용.
- checkout : 특정 branch(또는 commit) 으로 돌아가고 싶을 때 사용.

## 병합하기 1 (v3)

- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로부터 시작된 경우
- 아주 쉽게 병합 가능 = fast-forward

## 병합하기 2 (v4)
- 헤드 브랜치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 안 나면 좋은데, 충돌이 나도 겁내지 말자.