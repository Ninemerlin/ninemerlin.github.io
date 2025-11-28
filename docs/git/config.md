配置个人信息

` git config --global user.email "100360593+Ninemerlin@users.noreply.github.com"`

`git config --global user.name "Ninemerlin"`

记得在GitHub的个人页面的SSH和GPG keys页面添加公钥。



在win上检出代码将LF换行符换为CRLF，提交时换回去

`git config --global core.autocrlf true`





检查你的主分支。现在主分支应为main而不是master——使用如下命令修改

`git branch -M main`