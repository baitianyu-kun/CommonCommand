```shell
# git
# 首次
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
git init
git add .
# 平常
git commit -m "注释语句"
git remote add origin https://xxx.git
git push -u origin master 或git push -u origin localbranch:remotebranch
git push
# 代理
git config --global http.proxy http://127.0.0.1:8080
git config --global https.proxy https://127.0.0.1:8080
git config --global --unset http.proxy
git config --global --unset https.proxy
git config -l
```

