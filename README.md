# 一、搭建父工程
> new project -> springboot项目
1. 删除src等文件夹
2. pom文件添加需要用到的依赖

接下来就可以新建模块

# 二、创建公共模块common
> new Module
1. 同样删除src等文件
2. pom文件添加依赖

## 三、创建根据模块common_utils
> 在common模块下new Module
1. pom文件添加jwt依赖
2. 创建包com.atguigu.commonutils
3. 创建ResultCode接口，用于规定返回前端的code
4. 创建R类，用于规定返回前端的统一格式
5. 创建JwtUtils，用于生成和操作token
6. 创建MD5类，用于加密密码


