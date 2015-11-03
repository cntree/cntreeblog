title: hexo deploy 部署错误的解决方案
date: 2015-8-03 17:37:53
tags:
---
#1.ssh方式解决
步骤一：在本地生成git ssh-key 然后配置到你自己的github帐号中
步骤二：修改hexo项目中_config.yml文件中的deploy-repo项
```bash
  deploy:
    type: git
    repo: ssh://git@github.com/yourname/yourname.github.com.git
    branch: master
```
