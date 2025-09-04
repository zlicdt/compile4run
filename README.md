# COMPILE4RUN

唉，我一直以为用不上了，给repo删了

然后又有人需要了，所以我找了好久从微信群里找到给Q酱发的脚本

那就写一条命令解决方案吧！老登自己改，你们都知道path搞不搞没意义随用随取

```bash
git clone https://github.com/zlicdt/compile4run.git && cd compile4run && mkdir ~/bin && mv ./compile4run ~/bin/ && chmod +x ~/bin/compile4run && echo "PATH=$PATH:~/bin/"
```

命令执行完之后，就可以用`compile4run`这条命令来快速编译&运行C代码了，支持多参数（就是后面你可以写好几个文件，多文件项目）

最后产生的二进制文件会自动删除，不影响提交Autolab
