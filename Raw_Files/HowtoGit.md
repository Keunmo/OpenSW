# git 사용법

1. 주인레포 깃에서 포크하기
   fork
2. 터미널에서 그 깃 레포 클론하기
   git clone https://github.com/jil8885/OpenSourceSW
3. 로컬 개인레포에서 코드/수정/md수정
   git add [수정한 파일 이름]
   git commit
4. 그 후 md파일이 vi로 뜸. 거기서 수정내역 메모로 남김.
   위에꺼 동시에 할려면 git commit -a
   이거 하고나면 git 아이디 치고 비번 쳐서 인증해야됨.
5. git push
   -> git 서버에 반영됨.
6. git에서 주인한테 pull request 보내기.
7. 주인레포 반영하기
   git remote add red_09 https://github.com/jil8885/OpenSourceSW
8. 주인레포 실시간 반영하기
   git remote add red_09 https://github.com/jil8885/OpenSourceSW
   git remote -v
9. 레포 이름 확인. 별명 지정할 경우 그걸로 됨
   git pull red_09
   git merge red_09/master
   그러면 이제 내 로컬 폴더에 변경된 주인 레포 반영됨