```shell
# linux
# 批量解压:
	for f in *.tar; do tar xvf $f; done
	for f in *.tar.gz; do tar zxvf $f; done
	for f in *.tar.bz; do tar jxvf $f; done
	for f in *.rar; do unrar x $f; done
	for f in *.rar; do unrar x -p密码 $f; done
	for f in *.zip; do unzip $f; done
	for f in *.zip; do unzip -p密码 $f; done
	for f in *.7z; do 7z x $f -o./解压文件; done
	for f in *.7z; do 7z -p密码 x $f -o./解压文件; done
# 查看文件夹大小
	du -sh <文件夹名>
	# 查询当前文件夹的大小以及里面的文件和文件夹
	du -s
# 拷贝文件, r是文件夹复制, v是显示详细操作步骤
cp -rv src dst
# 创建文件并写入
echo "bai" > bai.txt
# 用cat以EOF为结尾创建文件
root@ls:~# cat << EOF > test.txt
> hello 
> EOF
root@ls:~# cat test.txt
hello 
```

