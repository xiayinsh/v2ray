# v2ray 部署在 RedHat OpenShift 


* openshift: 内存设置为256M，每 project 可配置 4 Pods。

* Docker 镜像：wangyi2005/v2ray:latest，wangyi2005/v2ray:core版本号

* ~~环境变量： CONFIG_JSON（配置）、CERT_PEM（证书）、KEY_PEM（私钥）~~
* 环境变量: UUID [Value](https://www.uuidgenerator.net)

* ~~用notepad++将上述变量中 \r\n 替换为\\\n，变成一行，导入容器。~~

* ~~客户端： android Actinium、windows v2ray 可用同一个服务端。~~
* 客户端: ios配置如下图
![ios-v2ray-config](raw.githubusercontent.com/greatislee/myblogImages/master/OpenShiftLearn/v2ray-ios-config.png)

* ~~具体配置: 见 issues。~~
