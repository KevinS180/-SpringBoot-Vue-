# -SpringBoot-Vue-
本研究基于 Spring Boot+Vue 技术栈构建校园社团管理平台，采用前后端分离架
构整合 MyBatis、MySQL 等技术，实现社团管理效率与学生互动体验的双向提升。
本地部署方法：
1.后端部署:
（1）使用数据库可视化工具 Navicat 或者 HeidiSQL 运行 sql 文件，进行导入数
据库操作。
（2）使用 IDEA 打开项目后端文件然后依次点击左上角的 File——Project
Structure，然后配置 JDK 版本，建议使用 JDK17
（3）依次点击 File——Settings,然后在搜索框里搜索 Maven，配置好 Maven
（4）找到 pom.xml 文件右键点击，将它设置为 maven project
（5）找到 src 下的 SpringbootSchemaApplication.java 启动类，运行启动类即可运
行后端。
2.前端部署：
（1）下载安装 node14
（2）安装 Vue 脚手架，在终端运行 npm i -g @vue/cli
（3）在前端目录下打开终端，运行 npm i 拉取依赖
（4）在终端下运行 npm run serve 命令，或者在 package.json 中手动点击运行 serve
命令
![image](https://github.com/user-attachments/assets/da5a6b5d-8ce2-4bc0-a319-71937d082229)
![image](https://github.com/user-attachments/assets/88e277c6-0219-448a-8fee-a6046cbdd233)
