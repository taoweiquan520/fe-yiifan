# fe-yiifan
个人网站重构-前端部分

# 安装
  1. 克隆仓库 `git clone https://github.com/Mutefish0/fe-yiifan`
  2. 安装 `npm install`

# 编译部署 (服务器端)
  1. 拉取更新 `git pull`
  2. 编译 `npm run build` (如果package包更新了, 需要重新执行一遍 `npm install`, 不然会报错)
  3. 部署`public`文件夹即可

# 开发 (本地)
  1. 开启热加载和编译 `npm start`
  2. 浏览器访问`http://localhost:8080`

# 在线预览
  [Demo](http://yiifan.xyz)

# 注意
  在mac下需要给`localhost`配`127.0.0.1`的host, 因为`webpack-dev-server`默认用的`localhost`, 而mac不识别
