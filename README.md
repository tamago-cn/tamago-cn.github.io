## 开源学习笔记

### 我的项目
#### [基于go-ini的golang微服务简易配置管理模块](https://github.com/tamago-cn/cfg)
将每个模块的配置作为一个节(`section`)，有配置修改需求的模块可在模块的`init`方法中注册一个节，即可方便的使用配置文件修改配置，注册时的参数值将作为参数默认值, 注册的同时，将模块的初始化方法与析构方法传入，以便在进程启动时对模块做相应的初始化操作，进程正常退出时做必要的析构操作

#### [基于logrus的golang日志配置管理模块](https://github.com/tamago-cn/logger)
包含日志配置，日志热修改，日志回滚与压缩功能

#### [基于readline的简易命令行解释器](https://github.com/tamago-cn/cmdline)
跨平台，解释输入流，可灵活自定义业务命令

#### [基于golang的批量远程工具](https://github.com/tamago-cn/mssh)
针对多台服务器远程批量执行相同指令，附带文件上传下载的功能，提升服务部署效率

### 推荐链接
[SSH隧道技术----端口转发，socket代理](https://www.cnblogs.com/fbwfbi/p/3702896.html)
