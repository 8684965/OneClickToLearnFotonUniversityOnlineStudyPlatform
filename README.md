![GitHub last commit](https://img.shields.io/github/last-commit/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform)
![GitHub top language](https://img.shields.io/github/languages/top/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform)
![GitHub repo size](https://img.shields.io/github/repo-size/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform)
# 一键学习Bot
* 本程序仅供交流学习，强烈不建议使用本程序，强烈建议好好学习。<br>
* 使用者默认接受Apache-2.0开源协议。<br>
* 如果你喜欢本程序，不妨点个star支持一下
## 使用说明<br>
1.  环境配置：<br>
* Python3.7（安装selenium和requests库）<br>
* geckodriver.exe添加到环境变量<br>
* Firefox浏览器 版本 ≥ 60<br>
2. 功能说明：<br>
##### 自定义选课学习：
* **StudyBotGUI.exe**&emsp;图形界面学习,exe须和geckodriver位于同级目录，一次可循环添加多门课程<br>
* **OneClickStudying.py**&emsp;一键秒学<br>
* **RobotLearner.py**&emsp;一键秒学+挂机学习（针对一些不能秒学的）<br>
* **OneClickAfterTest.py**&emsp;一键考试（依赖于补考）<br>
##### 根据学分批量选课学习：
* **ChooseCourseByCredit.py**&emsp;一键选课（比如你想选所有0.5学分的课）<br>
* **StudyByCredit.py**&emsp;一键学习（支持课前测试）<br>
* **ServerStudyBot.py**&emsp;云端一键学习（支持课前测试，支持推送学习进度到手机————依赖于Server酱）<br>
* **ServerStudyBotTG.py**&emsp;云端一键学习（支持课前测试，支持推送学习进度到手机————依赖于TelegramBot）<br>
* **CourseEvaluationBySelenium.py**&emsp;一键评价<br>
* **AfterTest.py**&emsp;一键考试<br>
### 示例图片
![一键学习](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/%E4%B8%80%E9%94%AE%E5%AD%A6%E4%B9%A0.JPG)<br>
![一键选课](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/%E4%B8%80%E9%94%AE%E9%80%89%E8%AF%BE.JPG)<br>
![挂机学习](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/%E6%8C%82%E6%9C%BA%E5%AD%A6%E4%B9%A0.JPG)<br>
![云端学习进度推送](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/%E4%BA%91%E7%AB%AF%E5%AD%A6%E4%B9%A0%E6%8E%A8%E9%80%81.jpg)<br>
![云端学习进度推送到TG](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/%E6%8E%A8%E9%80%81TG.jpg)<br>
![图形界面exe程序](https://github.com/Idealisten/OneClickToLearnFotonUniversityOnlineStudyPlatform/blob/master/Images/GUI.jpg)<br>
### 部分功能还不是很完善，发现bug请提issue，有空会更新
# TODOs
* - [ ] 课后测试题库
* - [x] 无GUI版本，挂在服务器上24h学习
* - [x] 发布GUI版本
