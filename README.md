## 基于node unblocker的通用web代理

##本工程是 [node-unblocker](https://github.com/nfriedly/node-unblocker) 的一个副本，只是修改了工程结构，以便于直接在Heroku上部署;  原作者的版本里, 所有的代理请求被到 http, 在这种场景下, URL中含有敏感域名会导致连接被GFW重置。因此，在该副本里，修改了代码让所有代理请求全使用https。

##在线试用： https://lit-savannah-22950.herokuapp.com/ 

##node-unblocker相对于PHP的web代理性能要好，且易于在Heroku上部署。 Heroku提供免费账号，且不需要绑定信用卡，部署简单。若您担心使用别人提供的服务器可能会泄漏个人隐私，可以通过一键部署搭建自己的Web代理。部署自己的代理，去中心化，小范围使用更不容易被GFW封锁。

删除原部分无用链接，保留新闻和常用链接


一键部署，请点击下方的"Deploy to Heroku"按钮， 具体步骤请参考 [WIKI](https://github.com/gfw-breaker/heroku-node-proxy/wiki)。

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

###### --End--
