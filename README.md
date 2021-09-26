# Quotations

## README

以前的目录，用来记录家璇同学的经典语录。最近发现，同学们都刻进 DNA 的说话方式。最近保研也顺利结束了，在紧张的研0生活之余，希望大家，对此项目进行补充。

## 贡献代码
管理员需要开权限，申请一下即可。

1. 将代码 clone 到本地

```shell
git clone git@github.com:whoru007/quotations.git
```

2. 创建自己的分支

```shell
git branch -b branch_name
```

3. 对文件进行修改

4. 提交修改，有时需要手动解决版本冲突

```shell
git commit -m "details"
```

5. 一周内可能多次 commit，希望进行对提交进行压缩 rebase ，这样最终的版本控制看的会很优雅。

```shell
git rebase -i HEAD~i # 合并最近 i 次的提交
# or
git rebase -i master # 和 master合并
```

其中 HEAD 相当于一个指针，指向 master 的最新版本，需要手动解决冲突

6. 提交到远程分支

```shell
git push origin branch_name1:branch_name2 
```

branch_name2 是你远程分支名。


7. 提交 merge request，网页操作