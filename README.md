## hexo自动构建工具

### 1.需求描述：

构建工具一堆，vercel也能构建，但是我服务器有国内的，我希望自己部署在自己服务器上，自动构建比较难，所以用github action生成静态后，由服务器通过git拉取。如果嫌弃github慢。可以试试的方法，不建议用gitee。

### 2.整体描述:

Github action负责生成静态代码，并执行curl 的post请求指定服务器的接口，服务器接受请求后拉取静态文件。

或者直接Github action发送curl 的post请求指定服务器的接口，然后服务器通过源码自己构建（不建议）

### 3.Github action 自动构建

### 4.服务器post请求文件

#### 4.1 php版本

服务器post请求文件(php消耗少，暂定。虽然java一个方法就解决了，但是为了这一个方法不合适)

#### 4.2 java版本

### 5.在线文档编写

建议使用:   [hexoplusplus](https://hexoplusplus.js.org/)

好好看看文配置有点多: [官方文档](https://hexoplusplus.js.org/start/)

