PS C:\Users\Smartech\Desktop\192100158> git init
Initialized empty Git repository in C:/Users/Smartech/Desktop/192100158/.git/
PS C:\Users\Smartech\Desktop\192100158> echo "file 1 content" > file1.txt
PS C:\Users\Smartech\Desktop\192100158> echo "file 2 content" > file2.txt
PS C:\Users\Smartech\Desktop\192100158> echo "file 3 content" > file3.txt
PS C:\Users\Smartech\Desktop\192100158> git add file1.txt file2.txt file3.txt
PS C:\Users\Smartech\Desktop\192100158> git commit -m "Initial commit with three files"
[master (root-commit) 8daf764] Initial commit with three files
3 files changed, 0 insertions(+), 0 deletions(-)
create mode 100644 file1.txt
create mode 100644 file2.txt
create mode 100644 file3.txt
PS C:\Users\Smartech\Desktop\192100158> echo "first update in file 1" >> file1.txt
PS C:\Users\Smartech\Desktop\192100158> git add file1.txt
PS C:\Users\Smartech\Desktop\192100158> git commit -m "Updated file 1"
[master 3137773] Updated file 1
1 file changed, 1 insertion(+), 0 deletions(-)
PS C:\Users\Smartech\Desktop\192100158> echo "first update in file 2" >> file2.txt
PS C:\Users\Smartech\Desktop\192100158> git add file2.txt
PS C:\Users\Smartech\Desktop\192100158> git commit -m "Updated file 2"
[master b1f2a9d] Updated file 2
1 file changed, 1 insertion(+), 0 deletions(-)
PS C:\Users\Smartech\Desktop\192100158> echo "first update in file 3" >> file3.txt
PS C:\Users\Smartech\Desktop\192100158> git add file3.txt
PS C:\Users\Smartech\Desktop\192100158> git commit -m "Updated file 3"
[master 3c4b82e] Updated file 3
1 file changed, 1 insertion(+), 0 deletions(-)
PS C:\Users\Smartech\Desktop\192100158> echo "second update in file 1" >> file1.txt
PS C:\Users\Smartech\Desktop\192100158> git add file1.txt
PS C:\Users\Smartech\Desktop\192100158> git commit -m "Second update in file 1"
[master 4d9f23e] Second update in file 1
1 file changed, 1 insertion(+), 0 deletions(-)
PS C:\Users\Smartech\Desktop\192100158> git tag -a v1.0 -m "Tagging version 1.0"
PS C:\Users\Smartech\Desktop\192100158> git log --patch > patch_log.txt
PS C:\Users\Smartech\Desktop\192100158> git log --stat > stat_log.txt
PS C:\Users\Smartech\Desktop\192100158> git log --graph --all > graph_log.txt
PS C:\Users\Smartech\Desktop\192100158> git log --oneline > oneline_log.txt