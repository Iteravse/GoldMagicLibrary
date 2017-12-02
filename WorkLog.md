# GlodMagicLibrary
## 注册防肉鸡验证

    根据
    https://github.com/dchest/captcha 
    实现用户注册需要验证码的功能  
    (防肉鸡反复刷服务器刷爆)fork ZYG  
## 服务器合并  

    # 服务器创建自己的管理员账户
        使用群文件公布的Fuhrer账户登录服务器创建自己的账户
    # Gopath/src/ourproject下合并控制器
        控制器合并时备份老版本并标注备份日期
        例如：
        2017年12月2日092455
    # PublicAppProgram下合并static  
        static合并时复制老版本并重命名为【当前时间-作者】
        例如：
        ==2017年12月2日092455-MJ==
