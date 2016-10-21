这个工程只是为了记一下工程的目录结构

目录结构
|—Project
    |—Application： 存放AppDelegate和API定义
    |-Models： 数据实体类
    |—Controllers： 存放所有的view controller
        |—Base // 定义本项目中各种 Controller的基础类
        |—Main
        |—User
    |-Views： 存放一些定制的视图
    |-Categories： 类扩展
    |—Common：本项目的一些全局性代码，这些代码通常与本项目的业务逻辑存在一些耦合，所以不放在 Utility 目录中。
    |—Utils： 存放工具类，自己实现的一些通用性代码，这些代码本项目不存在耦合，可直接复用于其他项目。
    |—VendorVendor： 存放非CocoaPods管理的第三方库
    |—Resource： 存放除图片以外的资源文件，如html、css文件（图片资源存放在images.xcassets中)
