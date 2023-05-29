# Git && GItHub Basic Operation

## Git Operation

1. 建立远程仓库(GitHub、Gitee、Gitlab)

   > 此处可能会选择一些初始化文件，例如`LISENCE`、`README.md`、`.gitignore`

2. 初始化本地仓库

   ```sh
   git init
   ```

3. 绑定远程仓库

   ```sh
   git remote add [alias] [link]
   ```

4. 拉取远程仓库，更新本地仓库与远程仓库同步

   ```sh
   git pull [alias] [branch]
   ```

5. 添加本地文件到暂存区，并提交本地仓库

   ```sh
   git add <file>
   
   git commit -m [comment]
   ```

6. 推送到远程仓库

   ```sh
   git push [origin] [branch]
   ```

   



如果在git push 的时候出现了下面代码

```sh
error: failed to push some refs to 'github.com:99588WS/JavaNotes.git'
```

可以尝试以下代码 , 即现同步仓库在push

```sh
 git pull origin master
 git push origin master
```


## Github Operation

1. fork
2. issue
3. archive
4. pull request