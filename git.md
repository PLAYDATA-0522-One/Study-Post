깃허브 강의
### 1번
1.  맥 다운로드 방법 -> 현수정
2. 윈도우 다운로드 방법 -> 태웅님

### 2번
1.   리포지토리 폴더를 저장할 폴더 생성 방법 
2.  폴더 내에서 git bash 열기
3. 다운로드 완료 후 git 초기 설정(이메일, 아이디) -> 태웅님
```bash
git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```

### 3번
	4. 오가니제이션 생성 방법 -> 현수정
	5. 오가니제이션 맴버 추가 방법 -> 현수정
	6. ssh키 생성 및 적용 방법 -> 현수정
	7.  git clone 방법 -> 현수정 
	 
### 4번
8. git 브런치 생성 방법 
```bash
# 생성
git branch test
git branch test2

# 확인
git branch

```
9. 그림으로 브런치 보여주기
10. 각각의 브런치 들어가는 방법 
git switch test
git switch test2

### 5번
	11. 9. 각자 브런치에 텍스트 파일 생성 & git 커밋 방법(add, commit 메세지, push) -> 지혜님
```bash
# 이동
git switch test

# 파일 생성
touch test.txt

# git 올릴 파일 추가
git add test.txt

# git 커밋 메세지
git commit -m "init"

# git push **초기에는 터미널에 보여지는 명령어 푸시를 사용한다
git push

# 이동
git switch test2

# 파일 생성
touch test.txt

# git 올릴 파일 추가
git add test.txt

# git 커밋 메세지
git commit -m "init"

# git push **초기에는 터미널에 보여지는 명령어 푸시를 사용한다
git push

```

	12.  깃허브 리포지토리 사이트를 직접 들어가서 각자의 브런치가 생성되었는지 확인시켜주기 

	13. QnA -> 현수정 대답
