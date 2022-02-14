###



### git permission denied (publickey) 해결방법
ssh key 생성
ssh-keygen -t rsa -b 4096 -C "이메일"

```
ssh-keygen -t rsa -b 4096 -C "shera31@naver.com"
C:\Users\[사용자]/.ssh/id_rsa.pub  파일에서 key 복사

github > settings> SSH and GPS keys --> New SSH KEY --> title 입력 -->  복사한 key 붙어넣기
```

