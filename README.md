# nodejs-hexo-blog   
http://blog.fens.me/hexo-blog-github/
this is first try.cool

关于 git 的上传 还是有坑的：
=============
如果出现了“ERROR Deployer not found : github”，别急，看这里：

deploy的type改成git，然后运行下npm install hexo-deployer-git --save
再hexo g
hexo d
-------------
比如ssh key的配置，目前是在mac下配置成功了，借助 <https://help.github.com/articles/generating-ssh-keys/> 此文档；
<https://help.github.com/articles/set-up-git/> 也看这个；
