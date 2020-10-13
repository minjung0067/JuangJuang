# orange_D


민정 repo에 issue 발행 -> 이슈 번호 기억
터미널에서 경로 확인 (orange_D)안에

git branch issue/이슈번호 : 이슈번호새 브랜치 파기
git checkout 브랜치이름(issue/숫자) : 작업환경 전환 (이슈번호의 브랜치에서 작업하기)

git pull <neworigin/oorigin> main :최신 코드 pull 받기

코드 작성작성

저장
git add . (특정 파일만 add 할 거면 git add <파일이름>
git commit -m '커밋메세지' (커밋과 동시에 issue closed 할 거면 resolved #이슈번호)
git push neworigin/oorigin

해서 민정 레포에서 pull request 새로 만들고
민정repo의 main <- 내 레포 issue/이슈번호 브랜치랑 비교
머지 confirm시키기 ~_~


