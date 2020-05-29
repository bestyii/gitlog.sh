# gitlog.sh
通过git生成CHANGELOG.md

将文件放到git项目的根目录下运行即可。

git提交的时候符合这种模版
```
 <type>(<scope>): <subject>
        <BLANK LINE>
        <body>
        <BLANK LINE>
        <footer>
```

## type 参数说明

- feat：新功能（feature）
- fix：修补bug
- docs：文档（documentation）
- style： 格式（不影响代码运行的变动）
- refactor：重构（即不是新增功能，也不是修改bug的代码变动）
- test：增加测试
- chore：构建过程或辅助工具的变动

如果`type`为`feat`和`fix`，则该 commit 将肯定出现在 Change log 之中。
