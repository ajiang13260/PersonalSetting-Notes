前端用到的 linux 常用命令有哪些
- 为什么要用 Linux 系统
     1. 公司的线上机器一般都是 Linux（参考阿里云）
     2. 测试机也需要保持一致，用 Linux
     3. 测试机或者线上机出了问题，本地又不能复现，需要去排查
- Linux 常用命令
     1. ssh work@192.168.10.21 回车输入密码，登入到线上机
     2. ls 查看文件（平铺形式）
     3. ls -a 查看所有文件（包括隐藏文件）
     4. ll 以列表形式查看文件
     5. clear 清屏
     6. mkdir abc 创建文件夹
     7. ll abc 查看 abc 文件夹中的文件
     8. rm -rf abc 删除 abc 文件夹，-rf 把文件夹里面所有内容全部删除
     9. rm a1.js 删除文件
     10. cd 更改当前目录
     11. mv 修改文件名 mv index.html index1.html
     12. mv 移动文件 mv index.html ../index.html 移动到上级目录
     13. cp a.js a1.js 拷贝复制文件
     14. touch d.js 创建新文件
     15. vi d.js 创建新文件并打开 vim 编辑（如果文件已存在，直接打开），点击 i 开启 insert 输入模式，点击 esc 退出输入模式，:w 保存写入， :q 退出编辑器，:q! 不保存强制退出。把 vi 替换成 vim 同样作用。
     16. vimtutor vim 教程
     17. cat package.json 打印文件内容
     18. head package.json 打印文件前面几行
     19. tail package.json 打印出文件末尾几行
     20. grep ‘babel” package.json 在 package 文件中查找 babel
