# dolry21-git 초기 명령어 테스트

1 로컬 Branch 생성
  > git init
  > git config --global user.email "dolry21@gmail.com"
  > git config --global user.name "SongKyoungBin"

2 생성파일 추가 및 커밋
  > git add README.txt
  > git commit -m "Git Hub File Add Test"

3 파일 History 확인 및 파일시점 전환
  > git log
  > git checkout 커밋ID값
  > git checkout - <최신 commit ID값 대체>

4 마스터 Branch에 추가
  > git remote add origin https://github.com/SongKyoungBin/dolry21.git
  > git push origin master

5  신규 디렉토리 생성 > git Clone 
  > git clone https://github.com/SongKyoungBin/dolry21.git .

6 원격저장소 > 로컬저장소 받아오기
  > git pull origin master

Trash Data Test