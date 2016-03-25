#安装express代码生成
> npm install -g express-generator

#生成项目
>express -e LM-blog[项目名]

#进入目录并安装依赖
>cd LM-blog && npm install

#设置环境变量并启动服务器
>SET DEBUG=LM-blog:* & npm start

#通过浏览器访问
>http://localhost:3000/

#提交代码
##初始化仓库
>git init

##添加文件到暂存区
>git add -A

##提交代码到历史去
>git commit -m"init"

##添加到远程仓库
>git remote add origin https://github.com/LM13716349652/LM-blog.git

##提交到远程仓库
>git push origin master
