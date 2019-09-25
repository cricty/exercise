 
Git 
================

----------------

##### 1. 创建版本库  ```git init```

##### 2. 添加跟踪文件  ```git add <file>```
  ~~~
  git add *.php   // 添加当前目录下的所有 PHP 文件
  ~~~
  
##### 3. 提交更改 ```git commit -m 'commit message'```
  ~~~
  git commit -m '修改用户组权限'
  ~~~
  
##### 4. 克隆 ```git clone <repo> <directory>```  
  ~~~
  git clone git@github.com:laravel/laravel.git
  // 也可以重命名项目文件夹名称
  git clone git@github.com:laravel/laravel.git mylaravel
  ~~~
  可以使用 git ssh http(s) 协议
  ~~~
  git clone git://github.com/laravel/laravel.git      // git
  git clone git@github.com:laravel/laravel.git        // ssh
  git clone https://github.com/laravel/laravel.git    // https
  ~~~
  
##### 5. 查看文件状态 ```git status (-s)```
   > -s 表示获取简短的信息，不加该参数会输出详细内容
  
##### 6. 查看改动 ```git diff```

  + 尚未缓存的改动 
    ~~~
    git diff
    ~~~
    
  + 已缓存的改动
    ~~~
    git diff --cached
    ~~~  
      
  + 已缓存的改动
    ~~~
    git diff HEAD
    ~~~
    
  + 只显示摘要
    ~~~
    git diff --stat
    ~~~