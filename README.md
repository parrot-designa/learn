# learn

一个学习的仓库

1. 使用 subtree 命令添加子项目

git subtree add --prefix=child git@github.com:parrot-designa/learn-react-core.git main

2. 使用 subtree 命令添加的子项目修改啥的可以被主项目实时检测到 相当于是一个目录

3. 修改子项目 进行提交

git subtree push --prefix=child git@github.com:parrot-designa/learn-react-core.git main

4. 拉取子项目

git subtree pull --prefix=child git@github.com:parrot-designa/learn-react-core.git main
