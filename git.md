# Git

1. Git 시작하기

   ```sh
   $ git init
   ```

   이제부터 해당 디렉토리를 git으로 관리하겠다! 는 의미임

   

2. 상태 확인하기

   ```sh
   $ git status
   ```

    빨간 색으로 뜨는 파일은 아직 스테이지 위로 올라간 적 없는 파일임

   

3. 스테이지에 올리기

   ```sh
   $ git add 파일명
   ```

   

4. 커밋하기(사진찍기)

   ```sh
   $ git commit -m '메세지'
   ```

   git으로 메시지와 함께 커밋을 하겠다는 뜻

   

5. 기록 확인하기

   ```sh
   $ git log
   ```



6. 리모트(원격 저장소) 등록하기

   ```sh
   $ git remote add origin 원격저장소 주소
   ```



7. 파일 푸쉬하기(업로드하기)

   ```sh
   $ git push origin master
   ```



8. 