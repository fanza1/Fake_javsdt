# Collect-Info-and-Fanart-for-JAV-
收集jav元数据，并规范本地文件（夹）的格式。  
Collect jav movies information, and finally build local movie library with emby.  
python3.7  

工作流程：  
1、用户选择文件夹，遍历路径下的所有文件。  
2、文件是jav，取车牌号，到javXXX网站搜索影片找到对应网页。  
3、获取网页源码找出“标题”“导演”“发行日期”等信息和DVD封面url。  
4、重命名影片文件。  
5、保存信息写入nfo。  
6、下载封面url作fanart.jpg，裁剪右半边作poster.jpg。  
7、重命名文件夹。  

目标效果：  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/图片1.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/图片2.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/图片3.png)  