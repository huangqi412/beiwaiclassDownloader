## 北外网课下载器
北外网课这段时间所有的课程都免费领取了 https://www.beiwaiclass.com/

使用方法：

> 1. nodejs
> 2. npm安装包：request, fs, child_process
> 3. node down.js courseCode

courseCode获取方法：

1. 在Chrome在网站内点开任一个课程（不用登陆，不用领取课程
2. 网址格式应为`https://www.beiwaiclass.com/products/detail-*.html`，按F12打开开发者工具后选择console
3. 在console中输入`console.log(courseCode)`然后回车就可以获得courseCode
4. 在powershell里进入存放down.js的文件夹 运行`node down.js courseCode`即可开始下载


系统环境：Windows10，其他系统需要自行安装gohls.exe

