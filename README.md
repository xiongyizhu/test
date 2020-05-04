# test
> 注意：私有项目作为gh-pages是收费的
```bash
  git init
  git add .
  git commit -m '初始化'
  
  git checkout -b gh-pages # 新建gh-pages分支
  git branch # 查看当前分支情况
  git remote add origin https://github.com/username/test # 与github仓库建立连接
  git remote -v # 查看连接情况，如果不对，使用`git remote rm origin`移除
  git push origin gh-pages # push到远端仓库的分支hexo
```
### 必须包含index.html静态页面，不能是vue源文件（得打包成静态文件部署）


