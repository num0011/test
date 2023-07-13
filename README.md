# test
## 학습내용
### 2023/07/05

- 처음 포크해왔을떄: 오너 리파지토리(num0011/test) 를 본인의 리파지토리(K-Shane)의 GitHub 으로 Fork하는 방법
1. 프로젝트 오너의 링크를 복사해서 자신이 로그인된 깃허브에 링크 붙여넣기
2. **(오너의 프로필과 자신의 프로필사이에서 혼동하지 않기!)**
오른쪽 위 포크 '초록색 버튼' 버튼 클릭 > 두번째 Fork라면 Synk Fork
3. 크리에이트 포크 '초록색 버튼' 클릭
4. K-Shane/test인 것을 확인

- 이후에 Sync Fork하는 방법
1. "This branch is up to date with num0011/test:main."이라는 문구가 뜨는지 확인.
2. 위 문구가 아닌 다른 문구가 떴을 경우 Sync Fork수행 필요.
3. "This branch is up to date with num0011/test:main." 옆에 Sync Fork 버튼 클릭

- 깃헙에 있는 저장소를 로컬 저장소로 clone하는 방법
1. 저장소(예시 https://github.com/NAGYUMIN/test) 화면 들어가기
2. code 누르고 open with github desktop을 클릭한다
3. local path를 고른다
4. clone을 누른다

### 2023/07/06
- github프로젝트에서 pull request하는 방법
1. 로컬 비주얼 스튜디어에서 작업한 변경사항 저장 
2. 깃허브 데스크탑에 표시되는 변경사항(초록: 추가된 내용, 빨강 : 삭제된 내용) 확인
3. 깃허브 데스크탑의 좌측 하단에 commit 제목과 설명을 적는다.
4.  commit to main 버튼, push origin 버튼 클릭
5. 로컬에서 깃헙(오리진)으로 넘어간 내용 확인 후, 내 깃헙에서"This branch is ~ of 프로젝트이름"내용 확인
6. Create pull request 초록 버튼 클릭 후 제목과 내용을 입력하고 pull request버튼 클릭
7. 내가 작성한 pull request내용을 확인하고,
아래에 뜨는 Merge pull request의 경우 작성한 pull request 가 여러개 일경우 한번에 제출하는 버튼임.

- github통해서 협업하는 방법
1. 한 사람이 프로젝트를 생성한다(오너)
2. 오너는 프로젝트 링크를 통해 팀원을 프로젝트에 초대한다.
3. 오너는 Issues에서 New Issues 버튼을 이용해 프로젝트의 역할을 분담한다. (Assignees에 담당자 지정) > Submit new issue
4. 프로젝트에 참여하는 사람은 오너 프로젝트(Upstream)에서 Fork를 한다.
5. 프로젝트에 참여자가 Fork한 깃허브 저장소(Origin)에서 Clone을 한다.
6. Local 저장소에서 프로젝트 변경 후 저장
7. 메세지와 함께 커밋
8. Local 저장소에서 Origin으로 Push한다.
9. Origin에서 Upstream으로 Pull reqest메세지에 3번에서 만든 이슈를 태그한 후 Pull reqest한다.
10. 오너가 머지한다.

### 2023/07/12

### 2023/07/13
- branch 생성하는 방법
1. code의 branches클릭
2. 오른쪽 초록색 New branch 클릭
3. branch이름 입력 후 Create new branch 클릭
