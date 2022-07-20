1.DNS解析
    -1.浏览器DNS缓存
    -2.本地系统DNS缓存
    -3.路由DNS缓存
    -4.网络运营商DNS缓存
    递归搜索: blog.baidu.com
    -.com域名下查找DNS解析
    -.baidu.com域名下查找DNS解析
    - blog.baidu.com域名下查找DNS解析
2.TCP三次连接: TCP三次握手
3.浏览器发送请求
4.服务器处理请求
5.浏览器接受响应
6.渲染页面
    -遇见HTML标记,浏览器调用HTML解析器解析成Token并构建DOM树;
    -遇见style/link标签,浏览器调用css解析器,处理css标记并构建cssom树;
    -遇见script标签,浏览器调用JavaScript解析器,处理js代码
    -将dom树和cssom树合并成一个渲染树
    -根据渲染树来计算布局,计算每个节点的几何信息(布局)
    -将各个节点的颜色绘制到屏幕上(渲染)
7.断开连接:TCP四次挥手