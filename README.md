# Coding Farm
### 코딩테스트 스터디 매칭 / 학습 도움 웹사이트
_________
## Commit Convention
### Commit 메시지 구성
예시)   
``` 
git commit -m "Docs/README.md 작성

               본문 : commit message 통일을 위해 작성
               
               footer 부분"
```
    

``` 
type : 
(한 줄 띄고)
body(본문내용) :
(한줄 띄고)
footer(꼬리말) : 
```
### Rule
1. 제목은 첫 글자를 대문자로
2. 제목은 명령문으로 (Fixed -> Fix)
3. 본문은 제목과 한칸 띄워 작성
3. 본문은 "무엇을", "왜"를 설명
4. 본문에 여러줄의 메시지를 작성할 땐 "-"로 구분
### Commit Type(제목)
+ Feat : 새로운 기능
+ Fix : 버그 수정
+ Design : CSS 등 사용자 UI 디자인 변경
+ Docs : 문서 수정(추가, 삭제, 수정, README)
+ Style : 스타일 (코드 형식, 세미콜론 추가, production code에 변경 X)
+ Refactor : 코드 리팩토링
+ Test : 테스트 코드, 리팩토링 테스트 코드 추가 (production code에 변경 X)
+ Chore : 기타 변경 사항(빌드 업무 수정, 패키지 매니저 수정, production code 변경 X)
+ Remove : 파일 삭제하는 작업만 수행한 경우
+ Rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만 수행한 경우
+ Comment : 주석 추가 및 변경
+ Init : 초기 생성

### Footer
+ Fixes : 이슈 수정중 (미해결)
+ Resolves : 이슈 해결했을 때 사용
+ Ref : 참고할 이슈가 있을 때 사용
+ Related to : 해당 커밋에 관련된 이슈번호 (미해결인 경우)   
ex) Fixes : #47 Realted to: #32, #21   
이슈 트래킹 정리 글 : https://velog.io/@code-bebop/Github-Issue-Tracker%EC%99%80-Project-Board