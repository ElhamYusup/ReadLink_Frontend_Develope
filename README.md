# **ReakLink图书借阅系统**
## 前段代码

  ~~这是~~ReadLink图书借阅系统的前段代码，包括了node_modules依赖，因为依赖文件小文件不是一般的多，上传很久都失败了，所以打算上传zip文件，用的node版本是16.13.2，在根目录跑`npm run dev`就可以跑项目了，借口和后端代码的借口都一一对应，
linux或MacOS系统记得给node_modules/.bin/vue-cli-service 这个shell脚本可执行权限`chmod 777 vue-cli-service`。然后把后端访问路径改成自己的局域网里的ip地址或localhost的9111端口，例如127.0.0.1:9111（在src/utils/request.js第13行）。
这样前段项目就可以跑起来了，node_modules下依赖都下好了的，启动很快的
