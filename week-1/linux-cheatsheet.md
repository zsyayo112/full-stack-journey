# Linux 常用命令 20 条速查

| # | 命令 | 作用 | 自己的示例 |
|---|------|------|-----------|
| 1 | `pwd` | 显示当前目录 | `pwd` → /home/alan |
| 2 | 'ls -al| 列目录（含隐藏文件）|
| 3 | 'cd/cd - | 切换目录/返回上一个 |
| 4 | 'mkdir -p a/b | 递归建目录 | 
| 5 | 'touch file.txt' | 新建空文件
| 6 | 'cp -r src dst' | 复制文件/目录 | 
| 7 | 'move old new' | 移动或改名 |
| 8 | 'rm -rf dir' | 删除 |
| 9 | 'cat' | 打印文件全文 |
| 10 | 'less file' | 分页查看 |
| 11 | 'head -n 20/tail -n 20' | 前/后N行 |
| 12 | 'tail -f file' | 实时追日志 | 
| 13 | 'grep -i "error" file' | 关键词过滤 | 对日志文件查 ERROR
| 14 | ' find . -name "*.sh" | 递归找文件 |  在 /usr/bin 里找 *.py |
| 15 | 'chmod +x *.sh' | 改权限 | 写个 hello.sh 后赋可执行 |
| 16 | 'chown $USER file' | 改所有者 | 用 sudo touch root.txt 后再 chown |
| 17 | 'df -h' | 查看磁盘分区使用 | 观察WSL分区和挂载盘 |
| 18 | 'du -sh *' | 统计目录大小 | 对~目录看看哪个文件夹最大 | 
| 19 || 'ps aux | grep node' || 查进程 | 	启动 node -e "setInterval(()=>{},1)" 后检索 | 
| 20 | 'kill -9 PID' | 杀进程 | 把上一步的 Node 进程结束 |




| … | … | … | … |

## 本周收获
- …

## 疑问
- …
