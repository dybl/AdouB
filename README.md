# AdouB
## 简介：
萌新初次建站尝试，在arch Linux上跑nodejs+express.js，
前面挂个nginx做负载均衡,
数据交互有MongoDB和MariaDB,
前一个存储照片文本之类的，后一个放用户数据，
还有一些简单的测试。
## 架构：
|——AdouB
   |——app
      |——data
         |——lib.js
         |——backend_helper.js
         |——db.js
         |——user.js
      |——handlers
         |——lib.js
         |——helper.js
         |——pages.js
         |——users.js
      |——basic.html
      |——local.config.js
      |——package.json
      |——server.js
   |——static
      |——lib
         |——scripts
         |——style
         |——images
         |——fonts
      |——content
      |——templates
   |——test
      |——api_lib.js
   |——schema.sql   
   
## 就这样吧！（逃
