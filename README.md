### 哪吒探针 nezha v0面板安装脚本

## v0面板安装脚本
~~~
curl -L https://raw.githubusercontent.com/nezhahq/scripts/refs/heads/v0/install.sh -o nezha.sh && chmod +x nezha.sh && sudo ./nezha.sh
~~~
## agent安装脚本
~~~
curl -L https://raw.githubusercontent.com/nezhahq/scripts/v0/install.sh -o nezha.sh && chmod +x nezha.sh && ./nezha.sh install_agent 域名 端口 密钥 --tls --disable-force-update --disable-command-execute
~~~
# agent其他
记得加入--disable-force-update 禁用更新  
我同时喜欢加入 --disable-command-execute 禁止web ssh

## 其实后台的安装命令只需要更改一个地方就行
# 例如：
~~~
curl -L https://raw.githubusercontent.com/nezhahq/scripts/main/install.sh -o nezha.sh && chmod +x nezha.sh && ./nezha.sh install_agent xxx.nezha.com 5555 xxxxxxxxxxxxxx --tls
~~~
# 改为：
~~~
curl -L https://raw.githubusercontent.com/nezhahq/scripts/v0/install.sh -o nezha.sh && chmod +x nezha.sh && ./nezha.sh install_agent xxx.nezha.com 5555 xxxxxxxxxxxxxx --tls

~~~
---
感谢  https://www.nodeseek.com/post-209183-1#7 老哥

## v0文档

论坛老哥整的v0文档 https://nezha-v0.mereith.dev/

感谢https://www.nodeseek.com/post-209098-1 老哥

github仓库  https://github.com/nezhahq/nezhahq.github.io/tree/v0
互联网档案馆 https://web.archive.org/web/20240929125721/https://nezha.wiki/guide/dashboard.html
