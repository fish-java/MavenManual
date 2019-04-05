## situation
- jar包要到处找，找完之后不知道放到哪里合适
- 下载后难以重复使用

## solution with maven
- maven帮我们直接下载
- 下载一次，到处引用

## subtance

- 验证 validate	验证项目	验证项目是否正确且所有必须信息是可用的
- 编译 compile	执行编译	源代码编译在此阶段完成
- 测试 Test	测试	使用适当的单元测试框架（例如JUnit）运行测试。
- 包装 package	打包	创建JAR/WAR包如在 pom.xml 中定义提及的包
- 检查 verify	检查	对集成测试的结果进行检查，以保证质量达标
- 安装 install	安装	安装打包的项目到本地仓库，以供其他项目使用
- 部署 deploy	部署	拷贝最终的工程包到远程仓库中，以共享给其他开发人员和工程