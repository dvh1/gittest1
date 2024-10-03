## 환경만들기
깃허브 아이디
1. 운영자 dvh1
2. 개인

1. 운영자: repository Settings에서 직원1의 아이디를 추가한다.
2. 직원1: Issue에서 [New issue] 버튼을 누르고 제목입력, Assignees assign yourself 하여 새 이슈를 만든다.
3. 직원1: 만든 새이슈에 오른쪽탭에 Development에 new branch만드는게 뜨니 만든다. 이름은 이슈번호-issue title이 자동세팅되며 수정가능하다.(예시 1-issuetitle)
4. 인텔리제이에서 버전관리에 있는 프로젝트>
   - git: https://github.com/dvh1/gittest1.git
   - 폴더: 전에 사용하던 인텔리제이 폴더가 e:/intellijProject/gittest1 이 기본으로 세팅되고 다른 폴더(e:/repos)에 설정하려면 e:/repos로 설정하고 뒤에 /gittest1 추가
   - 빈 폴더여야함
5. 인: 이슈로 만든 새 브랜치로 변경 1-issuetitle
   - 로컬 1-issuetitle로 체크아웃


## 운영(main)이 다른사람으로 다른 파일이 업데이트 되었을떄, 내가 수정한 파일이 있든없든 우선 그 다른 파일을 푸시하는 법

- 로컬 main 업데이트> 커밋내용: 예:Update README.md >오른쪽마우스> 브랜치'main'>i-issuetitle에 main병합
- 로컬 main은 업데이트하면 자동으로 최신 적용됨 다른거 할필요없음.
- main에서 받은 커밋들 커밋 푸시
- 푸시를 안해도 나중에 직원1이 수정한 커밋할때 같이 올라가긴 함
