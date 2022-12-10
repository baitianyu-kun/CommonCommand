```shell
# 创建环境
conda create -n env_name python=3.9
# 删除环境
conda env remove -n env_name
# conda删除索引，用于换源之后
conda clean -i
# 删除没有用的包
conda clean -p 
# 删除tar打包
conda clean -t
# 删除无用的包和缓存
conda clean --all
 #查看所有已经安装的包
conda list
# conda查看所有环境
conda env list

# 生成配置文件
conda config --set show_channel_urls yes
# 清华源 https://mirrors.tuna.tsinghua.edu.cn/help/anaconda/
# conda 设置proxy
proxy_servers:
  http: http://127.0.0.1:7890
  https: http://127.0.0.1:7890
```

```shell
# pip清除缓存:
	linux: rm -rf ~/.cache/pip
	windows: C:\Users\username\AppData\Local\pip\cache
# pip临时换源
pip install markdown -i https://pypi.tuna.tsinghua.edu.cn/simple
# pip永久换源
pip config set global.index-url https://pypi.douban.com/simple
# 换回默认源
pip config unset global.index-url
# pip镜像源:
清华源 https://pypi.tuna.tsinghua.edu.cn/simple
中国科学技术大学 https://pypi.mirrors.ustc.edu.cn/simple
阿里云 https://mirrors.aliyun.com/pypi/simple
豆瓣源 https://pypi.doubanio.com/simple
华为源 https://repo.huaweicloud.com/repository/pypi/simple
腾讯源 https://mirrors.cloud.tencent.com/pypi/simple
```
