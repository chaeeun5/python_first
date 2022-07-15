# Today I Learn 2022/07/15
## vscode와 github 연동하기
---
✔️ 터미널을 사용할 때는 먼저 경로를 확인해 줘야 함

✔️ git에 commit할 때는 add를 먼저 해주고 commit해줘야 함

⭐ commit 하기전에 꼭 pull 을 통해서 원격 레포지토리와 로컬 레포지토리의 정보를 최신화

*git -> add -> commit*




## 💡 vscode

git init : 원하는 폴더 위치로 들어가서 저장소로 설정
git status : 현재 git으로 관리되고 있는 파일들의 상태를 알 수 있음

git add. : 추적 되지 않은 모든 파일과 추적 하고 있는 파일 중 수정 된 파일을 모두 Staging Area에 올림

- git폴더에 버전관리하고싶은 폴더를 추가하려면 git add해야함

- 그 후에 다시 status해보면 newfile로 등록된 걸 확인할 수 있음(원래는 no connits yet에 표시됨)


git config --global user.name "chaeeun5" : 깃허브에 가입한 유저네임 입력

git config --global user.email "jce0497@gmail.com" : 깃허브에 가입한 이메일 입력

git commit -m “넣고싶은 메시지” : 이름과 메일설정이 완료해야 커밋을 진행할 수 있음

git log : commit의 history를 볼 수 있음

git diff : 수정된 내용을 보여줌

git  remote add origin “repo url” : 어떤 원격저장소에 작업을 저장할 것인지 등록

git push origin master : 토큰입력까지하면 연동 완료

- git 인증 방법 : settings => developer settings => personal aceess tokens 가서 토큰 발급받기

## 💡git bash
git clone “repo url” : 새로운 폴더 만들고 git bash이용하여 이 명령문 사용하면 git이랑 연동!
- bash에서 붙여넣기 할 때 : shift + Insert
