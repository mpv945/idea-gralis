# idea-gralis
gralis 项目搭建

## 环境配置 grails （依赖gradle 不是使用maven项目）
  1. 官网下载http://grails.org/download.html；选择Binary下载；Grails Application Forge类似spring.io 可以创建骨架
  2. grails二进制包解压到目录 ；配置GRADLE_HOME:解压的目录；增加path 执行grails -v 验证。官网好像说需要groovy，我没安装好像也行，但是本地安装过gradle
  3. 打开idea ，新建项目，项目选择grails 创建，然后下载一大堆依赖，最后就能直接运行项目了