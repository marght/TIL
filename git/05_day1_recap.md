# 1일차 정리

## 기본적인 CLI 명령어

1. `ls`: 현재 폴더의 파일 목록 확인
2. `cd`: 다른 폴더로 이동
3. `mkdir`: 새로운 폴더 생성
4. `touch`: 새로운 파일 생성 (빈 파일)
5. `cp`: 파일 복사
6. `mv`: 파일 이동 (잘라내기 > 붙여넣기) + 파일 이름 변경
7. `rm`: 파일 삭제 (remove), 폴더도 삭제 가능
   - 만약에 폴더 안에 폴더가 있으면? > `rm -r` 내부의 폴더도 같이 삭제
   - `rm -r` + force: `rm -r -f` or `rm -rf` : 내부의 폴더도 삭제하면서 강제로 삭제

## Git 명령어

1. `git init`: 해당 폴더를 Repository로 만들겠다.(== git으로 관리하겠다!)
   - 앞으로 해당 폴더의 역사(commit, history)는 git이 관리한다!
   - (github.com) `New Repository` -> Repository 생성

2. `git status`: 현재 Repository의 상태를 보여준다.
   - 현재 브랜치, 현재 Working Directory, 현재 Staging Area
   - 자주 입력해서 항상 확인을 해야합니다.
3. `git add`: 특정 파일 및 폴더를 Staging Area로 올립니다.
   - Staging Area: commit을 남길 파일 및 폴더를 준비하는 곳!
4. `git commit`: Staging Area에 있는 파일 및 폴더의 스냅샷(기록)을 남긴다!
   - (필수) 기록을 남길때는, 메시지가 항상 같이 있어야 함!
     - `git commit -m '메시지'`

5. `git log`: 이 때까지 남긴 commit들을 확인합니다.
   - commit hash: 자동 생성(사람으로 치면 주민등록번호, 고유한 값)
   - commit 작성자 정보(이메일, 이름), 작성 시간, 작성 메시지

## Remote 관련 명령어 (GitHub)

1. `git remote add origin 주소`: Remote(GitHub) 주소를 origin이라는 별명으로 추가한다!
2. `git push origin master`: origin이라는 별명을 가진 주소로 master 브랜치(commit들)를 push 한다(== 올린다)!
3. `git pull origin master`: origin이라는 별명을 가진 주소로부터 master 브랜치(commit들)를 pull 한다(== 내려 받는다!)
4. `git clone 주소`: Remote 주소의 Repository를 clone 한다(== 내려받는다!)

## Markdown, README

- 지금 작성 중인게 마크다운이고, README라는 이름을 가지면 GitHub에서 나서서 보여준다!



## 그러면 오늘 할 내용

1. `pull & push`: 상황을 만들어서 + pull 또는 push가 안되는 상황
2. `restore & reset`: 취소하기
3. `gitignore`: 우리가 git으로 관리하고 싶지 않은 내용을 무시할 수 있게 하는 기능
4. `branch`: 왜 필요하고, 어떻게 쓰는지
5. `fork & PR`: GitHub의 기능, 다른 사람(제 3자)들과 협업을 하기 위해







