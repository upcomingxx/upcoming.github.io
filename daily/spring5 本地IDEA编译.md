# Spring5 本地Idea编译

* 源码下载
  + 使用git 下载 git clone https://github.com/spring-projects/spring-framework.git
  + 直接下载zip包  https://github.com/spring-projects/spring-framework/archive/master.zip
* 导入idea
  1. 使用idea选择打开spring-framework项目的build.gradle
  2. 按照下图选择选项 ![idea](E:\学习总结\总结\idea.png)
  3. 选中 
     - [x] Use auto-import
     - [x] Use local Gradle distribution
  4. 设置 gradle home 、Gradle JVM、Global Gradle settings/service directory path
  5. 点击 Apply 或者 OK
* 开始检查配置、编译