### git 설정하기

```
git config --global usr.name "your_name"
git config --global user.email "your_email@example.com"
```

### git a new repository
```
echo "# sample" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:sherazzang/sample.git
git push -u origin master

```

### git 설정한 내용확인
```
git config --lsit
```



### remote:Permission to error

```
emote: Permission to gitest01/gitest01.github.io.git denied to xxxx.

fatal: unable to access 'https://github.com/yyyy/yyyy.github.io/': The requested URL returned error: 403

ssh 키 생성 안하고 진행하는 방법

제어판 > 사용자 계정 > 자격증명 관리자 > 일반자격증명 github.com 편집 바뀔 id 등록
```



### git permission denied (publickey) 해결방법
ssh key 생성
ssh-keygen -t rsa -b 4096 -C "이메일"

```
ssh-keygen -t rsa -b 4096 -C "shera31@naver.com"
C:\Users\[사용자]/.ssh/id_rsa.pub  파일에서 key 복사

github > settings> SSH and GPS keys --> New SSH KEY --> title 입력 -->  복사한 key 붙어넣기
```

